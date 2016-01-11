#### Test 55613145e2b298d_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
--------- beginning of /dev/log/main
D/AndroidRuntime( 7183): 
D/AndroidRuntime( 7183): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7183): CheckJNI is OFF
D/AndroidRuntime( 7183): setted country_code = Poland
D/AndroidRuntime( 7183): setted countryiso_code = PL
D/AndroidRuntime( 7183): setted sales_code = PLS
D/AndroidRuntime( 7183): readGMSProperty: start
D/AndroidRuntime( 7183): readGMSProperty: already setted!!
D/AndroidRuntime( 7183): readGMSProperty: end
D/AndroidRuntime( 7183): addProductProperty: start
D/dalvikvm( 7183): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7183): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7183): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7183): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7183): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7183): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7183): failed to load memtrack module: -2
D/dalvikvm( 7183): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7183): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 7211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7211):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7183): Shutting down VM
D/dalvikvm( 7183): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7211):  
I/SELinux ( 7211):  
I/SELinux ( 7211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7211): >>>>> Normal User
E/dalvikvm( 7211): >>>>> com.test.thalitest [ userId:0 | appId:10610 ]
E/SELinux ( 7211): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7211): in addTimaSignatureService
D/TimaKeyStoreProvider( 7211): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7211): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4173): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4173): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7211): GC_CONCURRENT freed 3014K, 30% free 9558K/13472K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7211): Binding Chromium to the background looper Looper (main, tid 1) {42234260}
I/chromium( 7211): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7211): Initializing chromium process, renderers=0
W/chromium( 7211): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7211): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7211): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7211): Mali API Version : 401
,I/Mali    ( 7211): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7211): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7211): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7211): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2419): tr p:7211,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7211): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7211): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7211): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7211): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7211): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7211): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7211): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:7211,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7211): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7211): Enabling debug mode 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 7211): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7211): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/JsMessageQueue( 7211): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7211): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222c7f8
,D/dalvikvm( 7211): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4222c7f8
D/jxcore_app_log( 7211): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030968344
,D/JX-Cordova( 7211): jxcore cordova android initializing
,D/dalvikvm( 7211): GC_CONCURRENT freed 1288K, 17% free 11343K/13528K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7211): GC_CONCURRENT freed 1923K, 16% free 14960K/17796K, paused 1ms+2ms, total 42ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 5396K, 29% free 16255K/22748K, paused 57ms, total 57ms
,D/dalvikvm( 7211): GC_CONCURRENT freed 6710K, 31% free 17711K/25344K, paused 3ms+12ms, total 86ms
D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm( 7211): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 1331K, 31% free 17540K/25344K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7211): Grow heap (frag case) to 21.544MB for 3713210-byte allocation
,D/dalvikvm( 7211): GC_FOR_ALLOC freed 2448K, 36% free 18718K/28972K, paused 50ms, total 50ms
,W/jxcore-log( 7211): Initializing JXcore engine
,W/jxcore-log( 7211): JXcore engine is ready
,W/jxcore-log( 7211): Starting JXcore engine
,W/jxcore-log( 7211): Platform android
W/jxcore-log( 7211): 
,W/jxcore-log( 7211): Process ARCH arm
W/jxcore-log( 7211): 
,I/jxcore-log( 7211): JXcore Cordova bridge is ready!
I/jxcore-log( 7211): 
W/jxcore-log( 7211): JXcore engine is started
I/chromium( 7211): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/jxcore-log( 7211): Toggling radios to true
I/jxcore-log( 7211): 
,D/BluetoothAdapter( 7211): enable(): BT is already enabled..!
,I/WifiManager( 7211): packageName : com.test.thalitest
,I/WifiManager( 7211): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7211, uid=10610
,W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7211, uid=10610 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7211, uid=10610 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2419): disconnect: pid=7211, uid=10610
I/jxcore-log( 7211): Radios toggled
I/jxcore-log( 7211): 
I/wpa_supplicant( 3977): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7211): Received device characteristics:
I/jxcore-log( 7211): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7211): Bluetooth name: S5mini-1
I/jxcore-log( 7211): Device name: samsung-SM-G800F
I/jxcore-log( 7211): 
,I/wpa_supplicant( 3977): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7211): Perf Test app loaded loaded
I/jxcore-log( 7211): 
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3977): First Scan Start
,I/wpa_supplicant( 3977): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
,I/jxcore-log( 7211): check test folder
I/jxcore-log( 7211): 
D/WifiP2pService( 2419): InactiveState{ what=143375 }
,I/jxcore-log( 7211): found test : ./testFindPeers.js
I/jxcore-log( 7211): 
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3977): Skip scan - already scanning
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2419): Attempting to switch to mobile
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7259):  
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/jxcore-log( 7211): found test : ./testSendData.js
I/jxcore-log( 7211): 
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/SELinux ( 7259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7259):  
I/SELinux ( 7259):  
,I/SELinux ( 7259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
W/NetworkManagementService( 2419): route cmd failed: 
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
E/dalvikvm( 7259): >>>>> Normal User
E/dalvikvm( 7259): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2419): Error! unhandled message{ when=-60ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/WifiStateMachine( 2419): Error! unhandled message{ when=-63ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
E/WifiStateMachine( 2419): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 7259): in addTimaSignatureService
D/TimaKeyStoreProvider( 7259): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7259): Added TimaKesytore provider
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x784a7f28 clazz=0x61a00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,V/NativeCrypto( 2847): Read error: ssl=0x7c185760: I/O error during system call, Connection timed out
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7c185760: I/O error during system call, Broken pipe
,D/dalvikvm( 7259): GC_CONCURRENT freed 2993K, 29% free 9573K/13468K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 12ms
,E/SPPClientService( 5546): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5546): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5546): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
E/SPPClientService( 5546): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5546): [b] ResponseMap empty
,I/System.out( 7259): Inside WakeupProvider
,I/System.out( 7259): Inside onCreate() of WakeupTriggerProvide
D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): updateIfacesLocked()
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/chromium( 7211): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 34ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/VlingoApplication( 7259): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7259): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7259): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,I/ActivityManager( 2419): Killing 6174:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7259): initQueue()
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): noConnectivity : true
,I/DBG_DM  ( 4757): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7288): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7288):  
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7288): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7288):  
I/SELinux ( 7288):  
,I/SELinux ( 7288): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7288): >>>>> Normal User
,E/dalvikvm( 7288): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7288): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7288): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7288): Added TimaKesytore provider
,I/wpa_supplicant( 3977): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3977): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3977): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/dalvikvm( 7288): GC_CONCURRENT freed 2997K, 29% free 9567K/13464K, paused 3ms+2ms, total 34ms
,D/dalvikvm( 7288): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): Associated with C0.AA.48
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3977): freq(2412) increment count 2
,I/wpa_supplicant( 3977): meet head of list.
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
I/ActivityManager( 2419): Killing 6244:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3977): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3977): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/SELinux ( 7302): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7302):  
,I/SELinux ( 7302): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7302):  
I/SELinux ( 7302):  
,I/SELinux ( 7302): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7302): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7302): >>>>> Normal User
,E/dalvikvm( 7302): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7302): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7302): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7302): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7302): Added TimaKesytore provider
,D/dalvikvm( 7302): GC_CONCURRENT freed 3000K, 29% free 9565K/13464K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7302): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/dhcpcd  ( 7314): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7314): bssid match
,I/ActivityManager( 2419): Killing 6318:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7321):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 10% free 9502K/10448K, paused 4ms+4ms, total 45ms
,I/SELinux ( 7321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7321):  
I/SELinux ( 7321):  
,I/SELinux ( 7321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7321): >>>>> Normal User
,E/dalvikvm( 7321): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9502K/10448K, paused 3ms+4ms, total 36ms
,D/TimaKeyStoreProvider( 7321): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7321): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7321): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9502K/10448K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 7321): GC_CONCURRENT freed 2997K, 29% free 9572K/13468K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/KLMS-2.3.201 : ( 7321): KLMSValidator() : checkQATesting()
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7321): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452523425058
,I/KLMS-2.3.201 : ( 7321): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6351:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7333): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7333):  
,I/SELinux ( 7333): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7333):  
I/SELinux ( 7333):  
,I/SELinux ( 7333): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7333): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7333): >>>>> Normal User
,E/dalvikvm( 7333): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7333): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7333): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7333): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7333): Added TimaKesytore provider
,D/dalvikvm( 7333): GC_CONCURRENT freed 2990K, 29% free 9576K/13468K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7333): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/SO_AGENT( 7333): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7333): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5809): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5809): [BDLM] already registered in spp
,I/SA      ( 5809): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5809): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5809): [OR] == isSIMCardReady false ==
,I/SA      ( 5809): [SCU] == networkStateCheck == false
,I/SA      ( 5809): [OR] onReceive END
I/ActivityManager( 2419): Killing 6263:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7345): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7345):  
,I/SELinux ( 7345): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7345):  
I/SELinux ( 7345):  
,I/SELinux ( 7345): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7345): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7345): >>>>> Normal User
,E/dalvikvm( 7345): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7345): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7345): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7345): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7345): Added TimaKesytore provider
,D/dalvikvm( 7345): GC_CONCURRENT freed 2994K, 29% free 9570K/13464K, paused 3ms+1ms, total 28ms
,D/dalvikvm( 7345): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/sCloudBackupApp( 7345): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7345): Other Intent
I/ActivityManager( 2419): Killing 6392:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7358): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7358):  
,I/SELinux ( 7358): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7358):  
I/SELinux ( 7358):  
,I/SELinux ( 7358): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7358): >>>>> Normal User
,E/dalvikvm( 7358): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7358): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7358): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7358): Added TimaKesytore provider
,D/dalvikvm( 7358): GC_CONCURRENT freed 2998K, 29% free 9570K/13472K, paused 5ms+2ms, total 43ms
,D/dalvikvm( 7358): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7358): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7358): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/daemonapp( 5343): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7358): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5343): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7358): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5343): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 5590:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5873): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5873): getCountryCode(): countryCode = PL
,D/Headlines( 5873): Breath.onCreate
,D/Headlines( 5873): Breath timer started. interval : 30000
,I/SELinux ( 7392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7392):  
,V/AlarmManager( 2419): waitForAlarm result :8
D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5873): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5873): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5873): requestUpdateNewsWelcomeCard !!! no welcome card
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/SELinux ( 7392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7392):  
I/SELinux ( 7392):  
,I/SELinux ( 7392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7392): >>>>> Normal User
,E/dalvikvm( 7392): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,D/WifiStateMachine( 2419): VerifyingLinkState enter
,E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/TimaKeyStoreProvider( 7392): in addTimaSignatureService
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/TimaKeyStoreProvider( 7392): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7392): Added TimaKesytore provider
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,D/dalvikvm( 2419): GC_CONCURRENT freed 4399K, 71% free 25603K/86832K, paused 10ms+25ms, total 298ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 162ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 161ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 162ms
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,D/dalvikvm( 7392): GC_CONCURRENT freed 3001K, 29% free 9564K/13468K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7392): WAIT_FOR_CONCURRENT_GC blocked 24ms
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 25ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/WebViewChromium( 7392): Binding Chromium to the background looper Looper (main, tid 1) {422310e0}
,I/chromium( 7392): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7392): Initializing chromium process, renderers=0
,W/chromium( 7392): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7392): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7392): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7392): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7392): Mali API Version : 401
,I/Mali    ( 7392): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7392): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ContextImpl( 7392): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7392): Starting up...
,I/iu.Environment( 5941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,V/QuickConnect[1.1][2] ( 5145): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422694f0
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7446): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7446):  
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7446): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7446):  
I/SELinux ( 7446):  
,I/SELinux ( 7446): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7446): >>>>> Normal User
,E/dalvikvm( 7446): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7446): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7446): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7446): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7446): Added TimaKesytore provider
,D/dalvikvm( 7446): GC_CONCURRENT freed 2991K, 29% free 9571K/13464K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7446): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 7446): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): stay LED for fully charged
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,I/SELinux ( 7466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7466):  
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/ActivityManager( 2419): Killing 6297:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7466):  
I/SELinux ( 7466):  
,I/SELinux ( 7466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7466): >>>>> Normal User
,E/dalvikvm( 7466): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7478):  
,D/TimaKeyStoreProvider( 7466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7466): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6324:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7478):  
I/SELinux ( 7478):  
,I/SELinux ( 7478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7478): >>>>> Normal User
,E/dalvikvm( 7478): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7478): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7478): Added TimaKesytore provider
,D/dalvikvm( 7466): GC_CONCURRENT freed 3009K, 29% free 9565K/13472K, paused 3ms+3ms, total 33ms
,D/dalvikvm( 7466): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/BadgeProvider( 7466): onCreate
,D/BadgeProvider( 7466): DatabaseHelper
,D/BadgeProvider( 7466): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7466): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7466): sendNotify, [notify] : null
D/BadgeProvider( 7466): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7466): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7466): update, [UpdateCount] : 1
,D/Launcher.Model( 2767): reloadBadges entered.
,D/dalvikvm( 7478): GC_CONCURRENT freed 3013K, 30% free 9558K/13472K, paused 5ms+5ms, total 40ms
,D/dalvikvm( 7478): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/dalvikvm( 7211): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 7211): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7211): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 7211): Shutting down VM
,W/dalvikvm( 7211): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,D/hcjo    ( 5962): AutoUpdateManager:IDLE:execute
E/AndroidRuntime( 7211): FATAL EXCEPTION: main
E/AndroidRuntime( 7211): Process: com.test.thalitest, PID: 7211
E/AndroidRuntime( 7211): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7211): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7211): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7211): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7211): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7211): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7211): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 7211): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7211): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7211): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7211): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7211): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7211): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7211): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7211): 	at dalvik.system.NativeStart.main(Native Method)
D/InitializeManagerStateMachine( 5962): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5962): exit::IDLE
,D/InitializeManagerStateMachine( 5962): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5962): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5962): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5962): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5962): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5962): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5962): entry::SUCCESS
,D/hcjo    ( 5962): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5962): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5962): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5962): exit::SUCCESS
,D/InitializeManagerStateMachine( 5962): entry::IDLE
,W/ActivityManager( 2419):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2419): Killing 5983:com.android.calendar/u0a144 (adj 15): empty #43
,I/Process ( 7211): Sending signal. PID: 7211 SIG: 9
,D/CrashAnrDetector( 2419): processName: com.test.thalitest
,D/CrashAnrDetector( 2419): broadcastEvent : com.test.thalitest data_app_crash
,E/SPPClientService( 5546): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5546): [SystemStateMoniter] Current Time : 277427
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,W/ActivityManager( 2419): mDVFSHelper.acquire()
E/SPPClientService( 5546): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5546): [[SystemStateMonitorService]] No Active Internet
,I/DBG_DM  ( 4757): [3.19.140541][Line:408][onResume] 
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
I/WindowState( 2419): WIN DEATH: Window{439d6720 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/ActivityManager( 2419): Process com.test.thalitest (pid 7211) (adj 9) has died.
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4757): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
E/SPPClientService( 5546): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5546): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5873): Breath 1977 latestRequest time : 1452523426192 current time : 1452523428169
,I/DBG_DM  ( 4757): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:418][onResume] Postpone Count : 29
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/SPPClientService( 5546): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4757): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,E/SPPClientService( 5546): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/DBG_DM  ( 4757): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4757): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
I/DBG_DM  ( 4757): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4757): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,E/SPPClientService( 5546): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/DBG_DM  ( 4757): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4757): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4757): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4757): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,I/DBG_DM  ( 4757): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4757): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4757): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2419): semi p:4757,o:t
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
,E/SPPClientService( 5546): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,E/SPPClientService( 5546): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7211 uid 10610
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/KLMS-2.3.201 : ( 7321): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7321): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452523428529
,I/KLMS-2.3.201 : ( 7321): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7333): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3438): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3438): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3438): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7333): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3438): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3566): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7503): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7503):  
,I/SELinux ( 7507): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7507):  
I/SELinux ( 7503): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7503):  
I/SELinux ( 7503):  
,I/SELinux ( 7503): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7503): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7503): >>>>> Normal User
,E/dalvikvm( 7503): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7503): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7503): in addTimaSignatureService
,I/SA      ( 5809): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5809): [BDLM] already registered in spp
,I/SA      ( 5809): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5809): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/TimaKeyStoreProvider( 7503): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5809): [OR] == isSIMCardReady false ==
I/SA      ( 5809): [SCU] == networkStateCheck == true
D/ActivityThread( 7503): Added TimaKesytore provider
,I/SA      ( 5809): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5809): isChinaCountryCode : false
,I/SA      ( 5809): [OR] == networkStateCheck true ==
I/SELinux ( 7507): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7507):  
I/SELinux ( 7507):  
,I/SELinux ( 7507): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7507): >>>>> Normal User
,E/dalvikvm( 7507): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7507): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5809): [OR] GetMyCountryZoneTask
,I/SA      ( 5809): [OR] onReceive END
,I/SA      ( 5809): [SRS] prepareGetMyCountryZone
,I/SA      ( 5809): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5809): [SSP] query invoked
,I/SA      ( 5809): [TPMU] GetMccFromDB : null
I/SA      ( 5809): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5809): [TPM] isNoProxy(default) : true
,I/SA      ( 5809): [RC New] Execute method=[GET] start
,D/TimaKeyStoreProvider( 7507): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7507): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7507): Added TimaKesytore provider
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7345): Other Intent
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7358): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
D/dalvikvm( 7503): GC_CONCURRENT freed 2992K, 29% free 9573K/13464K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7503): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Headlines( 5873): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5873): getCountryCode(): countryCode = PL
,D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5873): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5873): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5873): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5873): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7507): GC_FOR_ALLOC freed 3019K, 30% free 9549K/13468K, paused 20ms, total 20ms
,I/System.out( 7302): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/iu.Environment( 5941): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/dalvikvm( 7507): GC_CONCURRENT freed 233K, 30% free 9560K/13468K, paused 3ms+1ms, total 16ms
,D/dalvikvm( 7507): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/System.out( 7302): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7302): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5145): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5145): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422694f0
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,V/KVNProvider( 7507): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7507): getFindoCursor query string : 
,D/dalvikvm( 5941): GC_CONCURRENT freed 508K, 6% free 26845K/28260K, paused 7ms+4ms, total 64ms
,D/dalvikvm( 5941): WAIT_FOR_CONCURRENT_GC blocked 54ms
,V/KVNProvider( 7507): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5962): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5962): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5962): exit::IDLE
,D/InitializeManagerStateMachine( 5962): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5962): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5962): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5962): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5962): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5962): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5962): entry::SUCCESS
,D/hcjo    ( 5962): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5962): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5962): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5962): exit::SUCCESS
,D/InitializeManagerStateMachine( 5962): entry::IDLE
,E/SPPClientService( 5546): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5546): [SystemStateMoniter] Current Time : 278233
,E/SPPClientService( 5546): [SystemStateMoniter] No Connect : false
,I/System.out( 7302): AsyncTask #1 calls detatch()
,W/System.err( 7302): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7302): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7302): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7302): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7302): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7302): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7302): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7302): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7302): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7302): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7302): Caused by: java.lang.NullPointerException
W/System.err( 7302): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7302): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7302): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7302): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7302): 	... 8 more
,I/ActivityManager( 2419): Killing 6161:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 5546): GC_CONCURRENT freed 2019K, 23% free 10433K/13448K, paused 2ms+2ms, total 39ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,I/SA      ( 5809): [RC New] [v2liruge] api execute + 1423
,I/SA      ( 5809): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5809): AsyncTask #2 calls detatch()
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5809): [TPMU] getNetworkMcc : 
,I/SA      ( 5809): [SCU] saveMccToPreferece Start
,I/SA      ( 5809): [SCU] RegionMCC : 260
,I/SA      ( 5809): [SSP] query invoked
,I/SA      ( 5809): [TPMU] GetMccFromDB : null
,I/SA      ( 5809): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5809): [SCU] saveMccToPreferece End
I/SA      ( 5809): [RC New] executeRequest [v2liruge] end. 1459
,I/SA      ( 5809): [RC New] Execute end
,I/SA      ( 5809): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5809): [OR] GetMyCountryZoneTask Success
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 10
,E/SPPClientService( 5546): [b] __InitReply__
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
I/ActivityManager( 2419): Killing 6196:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 281117
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
,D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3477)
,I/GAV2    ( 7392): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6591): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6591): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6591): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6591): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6591): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6591): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6591): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5962): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5962): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5962): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5962): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5962): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5962): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5962): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5962): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5962): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5962): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5962): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5962): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5962): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5962): entry::IDLE
,E/Watchdog( 2419): !@Sync 9
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{4341cea0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43831258 u0 com.sec.spp.push/.PushClientService}
,I/PowerManagerService( 2419): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5873): Breath 27441 latestRequest time : 1452523428767 current time : 1452523456208
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2419): initializing...
,I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): device_id = 0x0
,I/TZ: mc_tlc_communication( 2419): tlc_open() was called
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7859
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7870
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 10
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 11
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7976): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7976):  
,I/SELinux ( 7976): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7976):  
I/SELinux ( 7976):  
,I/SELinux ( 7976): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7976): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7976): >>>>> Normal User
,E/dalvikvm( 7976): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7976): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7976): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7976): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7976): Added TimaKesytore provider
,D/dalvikvm( 7976): GC_CONCURRENT freed 3000K, 29% free 9565K/13464K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7976): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5873): Breath 76811 latestRequest time : 1452523428767 current time : 1452523505578
,I/ActivityManager( 2419): Killing 6534:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5873): Breath 87439 latestRequest time : 1452523428767 current time : 1452523516207
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 12
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8158): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8158):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 10% free 9502K/10448K, paused 5ms+4ms, total 45ms
,I/SELinux ( 8158): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8158):  
I/SELinux ( 8158):  
,I/SELinux ( 8158): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8158): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,E/dalvikvm( 8158): >>>>> Normal User
,E/dalvikvm( 8158): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8158): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8158): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9502K/10448K, paused 3ms+5ms, total 41ms
,D/TimaKeyStoreProvider( 8158): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8158): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9502K/10448K, paused 4ms+4ms, total 39ms
,D/dalvikvm( 8158): GC_CONCURRENT freed 3004K, 29% free 9566K/13472K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 8158): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SPPClientService( 8158): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8158): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8158): PushLog.txt file is not deleted.
D/SPPClientService( 8158): PushLog.txt file is not deleted.
,D/SPPClientService( 8158): ============PushLog. stop!
,I/ActivityManager( 2419): Killing 6452:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,E/SPPClientService( 5546): [b] __PingReply__
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5873): Breath 117439 latestRequest time : 1452523428767 current time : 1452523546206
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 13
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5873): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5873): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5873): Breath 147445 latestRequest time : 1452523428767 current time : 1452523576213
,D/Headlines( 5873): stop 
,D/Headlines( 5873): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6564:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 15
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 4338K, 71% free 25199K/85744K, paused 12ms+20ms, total 222ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 16
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,E/Watchdog( 2419): !@Sync 17
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2580): GC_CONCURRENT freed 15732K, 33% free 33863K/50492K, paused 19ms+8ms, total 165ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 18
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 19
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 21
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/GAV2    ( 5633): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5633): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2419): !@Sync 22
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4079): GC_CONCURRENT freed 2891K, 29% free 9725K/13516K, paused 27ms+2ms, total 96ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
,D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3283): Aggregate from 1452522138028 (log), 1452522138028 (data)
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3283): GC_CONCURRENT freed 2184K, 20% free 12671K/15756K, paused 7ms+11ms, total 104ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3960K, 71% free 25061K/85744K, paused 8ms+20ms, total 222ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2767): GC_CONCURRENT freed 7042K, 38% free 18944K/30388K, paused 9ms+7ms, total 99ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5546): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3920K, 71% free 24960K/85744K, paused 20ms+19ms, total 235ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
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
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4079): GC_CONCURRENT freed 2050K, 29% free 9722K/13516K, paused 4ms+2ms, total 34ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 50
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5546): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,E/SPPClientService( 5546): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 3875K, 71% free 24975K/85744K, paused 9ms+16ms, total 204ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 175ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 176ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 11625
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 60
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 63ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2016-01-11-00-28-00.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2419): Killing 6446:com.sec.knox.bridge/1000 (adj 15): empty for 1816s
,I/ActivityManager( 2419): Killing 4867:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1816s
,I/ActivityManager( 2419): Killing 6432:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1816s
,I/ActivityManager( 2419): Killing 6409:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6751:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6737:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1827s
I/ActivityManager( 2419): Killing 6725:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1827s
,I/ActivityManager( 2419): Killing 6713:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1827s
I/ActivityManager( 2419): Killing 6700:com.samsung.helphub/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 6687:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 6674:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 6661:com.sec.android.service.cm/u0a82 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 6368:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 5700:com.android.mms/u0a49 (adj 15): empty for 1828s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 6635:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1828s
,I/ActivityManager( 2419): Killing 6002:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1829s
,I/ActivityManager( 2419): Killing 6605:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1829s
,I/ActivityManager( 2419): Killing 6577:com.android.musicfx/u0a24 (adj 15): empty for 1830s
,D/CountryDetector( 2419): No listener is left
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryService( 2419): stay LED for fully charged
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x3)
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 51ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12050): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12050):  
,I/SELinux (12050): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12050):  
I/SELinux (12050):  
,I/SELinux (12050): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12050): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12050): >>>>> Normal User
,E/dalvikvm(12050): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12050): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12050): in addTimaSignatureService
,D/TimaKeyStoreProvider(12050): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12050): Added TimaKesytore provider
,D/dalvikvm(12050): GC_CONCURRENT freed 2997K, 29% free 9569K/13468K, paused 3ms+2ms, total 30ms
,D/dalvikvm(12050): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/@ WidgetProvider(12050): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12050): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12050): Widget random data : 9
,D/@ WidgetProvider(12050): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12050): Widget random data : 1
,E/dalvikvm(12050): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12050): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12050): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12050): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12050): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12050): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12050): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12050): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12050): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12050): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12050): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12050): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12050): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12050): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12050): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12050): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 2847): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2847): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2847): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2847): VFY: replacing opcode 0x1f at 0x0011
I/dalvikvm( 2847): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2847): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2847): VFY: replacing opcode 0x6e at 0x003d
,I/System.out(12050): Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 2847): Thread-56(HTTPLog):isShipBuild true
,I/System.out( 2847): Thread-56(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(12050): Thread-675(ApacheHTTPLog):isShipBuild true
,I/System.out(12050): Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2847): GC_CONCURRENT freed 1826K, 21% free 10860K/13664K, paused 5ms+5ms, total 54ms
,I/System.out(12050): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12050): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12050): Max ALLOWED memory (MB): 128
,V/ImageManager(12050): Max SHOULD USE memory (MB): 128
,V/ImageManager(12050): Max Image Cache memory (MB): 32
,I/System.out(12050): AsyncNetworking-1-thread-1 calls detatch()
,D/skia    (12050): getTotalSize : Do not get file length
,D/@ WidgetProvider(12050): Building widget : 5
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 67
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
D/AndroidRuntime(12279): 
D/AndroidRuntime(12279): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12279): CheckJNI is OFF
D/AndroidRuntime(12279): setted country_code = Poland
D/AndroidRuntime(12279): setted countryiso_code = PL
D/AndroidRuntime(12279): setted sales_code = PLS
D/AndroidRuntime(12279): readGMSProperty: start
D/AndroidRuntime(12279): readGMSProperty: already setted!!
D/AndroidRuntime(12279): readGMSProperty: end
D/AndroidRuntime(12279): addProductProperty: start
D/dalvikvm(12279): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12279): Added shared lib libjavacore.so 0x0
D/dalvikvm(12279): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12279): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12279): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12279): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12279): failed to load memtrack module: -2
D/dalvikvm(12279): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12279): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2419): START PACKAGE DELETE: observer{1125150952}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2419): !@killApplicatoin: 10610, uninstall pkg
I/ActivityManager( 2419): Killing 7321:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7302:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 5749:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7288:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 6591:com.sec.pcw.device/1000 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 2831:com.android.settings/1000 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7466:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7333:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7259:com.vlingo.midas/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 6619:com.policydm/1000 (adj 15): empty for 1800s
W/PackageSettings( 2419): Skipping PackageSetting{4250ef08 com.example.hello/10600} due to missing metadata
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10610, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 3283): GC_EXPLICIT freed 417K, 22% free 12401K/15756K, paused 6ms+8ms, total 92ms
D/dalvikvm( 2954): GC_EXPLICIT freed 1467K, 26% free 10035K/13468K, paused 9ms+6ms, total 89ms
D/dalvikvm( 2419): GC_CONCURRENT freed 3826K, 71% free 25042K/85744K, paused 10ms+24ms, total 269ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 116ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 119ms
D/PackageManager( 2419): queryIntentReceivers - Execution time: 136 ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10610, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/SamsungIME( 3013): mOCRHelper is null
I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
D/QuickConnect[1.1][2] ( 5145): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
I/SELinux (12293): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12293):  
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/SELinux (12293): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12293):  
I/SELinux (12293):  
I/SELinux (12293): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux (12293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12293): >>>>> Normal User
E/dalvikvm(12293): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12293): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12293): in addTimaSignatureService
I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
D/TimaKeyStoreProvider(12293): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12293): Added TimaKesytore provider
D/RegisteredServicesCache( 2756): empty dynamic service
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12293): GC_CONCURRENT freed 2986K, 29% free 9572K/13464K, paused 3ms+1ms, total 22ms
D/dalvikvm(12293): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
D/dalvikvm( 2419): GC_EXPLICIT freed 892K, 72% free 24851K/85744K, paused 10ms+36ms, total 312ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 284ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(12293): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(12293): ELMEngine.ELMEngine( context ).
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
D/elm:14132(12293): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2756): GC_CONCURRENT freed 1210K, 27% free 10615K/14360K, paused 7ms+4ms, total 88ms
D/dalvikvm( 2756): WAIT_FOR_CONCURRENT_GC blocked 75ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
D/elm:14132(12293): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(12293): ElmAgentService : onCreate()
D/RCPManagerService( 2419): PackageReceiver onReceive()
D/elm:14132(12293): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12293): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12293): MDMBridge.getInstance()
D/elm:14132(12293): MDMBridge.getAllLicenseInfoFromSDK()
I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132(12293): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12306):  
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(12293): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux (12306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12306):  
I/SELinux (12306):  
I/SELinux (12306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12306): >>>>> Normal User
E/dalvikvm(12306): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12306): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/elm:14132(12293): ElmAgentService : onDestroy().
I/ActivityManager( 2419): Killing 5809:com.osp.app.signin/u0a44 (adj 15): empty for 1800s
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12306): in addTimaSignatureService
D/TimaKeyStoreProvider(12306): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12306): Added TimaKesytore provider
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12306): GC_CONCURRENT freed 2998K, 29% free 9568K/13468K, paused 5ms+2ms, total 39ms
D/dalvikvm(12306): WAIT_FOR_CONCURRENT_GC blocked 29ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10610 #1
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12321):  
D/dalvikvm( 2419): GC_EXPLICIT freed 830K, 71% free 25016K/85744K, paused 13ms+33ms, total 527ms
I/ActivityManager( 2419): Killing 7503:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
I/SELinux (12321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12321):  
I/SELinux (12321):  
I/SELinux (12321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12321): >>>>> Normal User
E/dalvikvm(12321): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12321): in addTimaSignatureService
D/TimaKeyStoreProvider(12321): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12321): Added TimaKesytore provider
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12321): GC_CONCURRENT freed 3001K, 29% free 9567K/13468K, paused 4ms+2ms, total 29ms
D/dalvikvm(12321): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/PackageManager( 2419): delete sourFile : 
W/ApplicationsProvider( 2954): Could not fetch usage stats
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
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2419): delete native library directory: 
D/PackageManager( 2419): return delete result to caller: 1125150952
D/PackageManager( 2419): returnCode: 1
D/AndroidRuntime(12279): Shutting down VM
D/dalvikvm(12279): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 5ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12335): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12335):  
I/ActivityManager( 2419): Killing 7345:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1801s
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12335): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12335):  
I/SELinux (12335):  
I/SELinux (12335): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12335): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12335): >>>>> Normal User
E/dalvikvm(12335): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12335): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12335): in addTimaSignatureService
D/TimaKeyStoreProvider(12335): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12335): Added TimaKesytore provider
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2419): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2419): clearDefaults: com.test.thalitest
D/dalvikvm(12335): GC_CONCURRENT freed 2998K, 29% free 9572K/13472K, paused 4ms+2ms, total 31ms
D/dalvikvm(12335): WAIT_FOR_CONCURRENT_GC blocked 22ms
I/SELinux (12350): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12350):  
I/SELinux (12350): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12350):  
I/SELinux (12350):  
I/SELinux (12350): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12350): >>>>> Normal User
E/dalvikvm(12350): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (12350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12350): Enabling JNI app bug workarounds for target SDK version 8...
I/ActivityManager( 2419): Killing 7507:com.sec.android.app.voicenote/1000 (adj 15): empty for 1801s
D/TimaKeyStoreProvider(12350): in addTimaSignatureService
D/TimaKeyStoreProvider(12350): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12350): Added TimaKesytore provider
D/dalvikvm(12350): GC_CONCURRENT freed 3008K, 30% free 9560K/13472K, paused 3ms+2ms, total 26ms
D/dalvikvm(12350): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12350): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12350): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12350): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12350): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12350): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12350): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12350): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12350): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12350): Shutting down VM
W/dalvikvm(12350): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12350): FATAL EXCEPTION: main
E/AndroidRuntime(12350): Process: com.sec.pcw.device, PID: 12350
E/AndroidRuntime(12350): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12350): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12350): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12350): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12350): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12350): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12350): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12350): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12350): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12350): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12350): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12350): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12350): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12350): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12350): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12350): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12350): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12350): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12350): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12350): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12350): 	... 12 more
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
I/SELinux (12364): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12364):  
I/Process (12350): Sending signal. PID: 12350 SIG: 9
I/ActivityManager( 2419): Process com.sec.pcw.device (pid 12350) (adj 0) has died.
I/SELinux (12364): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12364):  
I/SELinux (12364):  
I/SELinux (12364): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12364): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12364): >>>>> Normal User
E/dalvikvm(12364): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12364): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12364): in addTimaSignatureService
D/TimaKeyStoreProvider(12364): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12364): Added TimaKesytore provider
D/dalvikvm(12364): GC_CONCURRENT freed 2996K, 29% free 9572K/13472K, paused 2ms+2ms, total 28ms
D/dalvikvm(12364): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/System.err(12364): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12364): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12364): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12364): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12364): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12364): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12364): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12364): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12364): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12364): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12364): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12364): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12364): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12364): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12364): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12364): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12364): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12364): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12364): 	at libcore.io.Posix.open(Native Method)
W/System.err(12364): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12364): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12364): 	... 21 more
D/GalaxyFinderApplication(12364): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12364): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12378):  
I/ActivityManager( 2419): Killing 7358:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1802s
I/SELinux (12378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12378):  
I/SELinux (12378):  
I/SELinux (12378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12378): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12378): >>>>> Normal User
E/dalvikvm(12378): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12378): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12378): in addTimaSignatureService
D/TimaKeyStoreProvider(12378): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12378): Added TimaKesytore provider
D/dalvikvm(12378): GC_CONCURRENT freed 3000K, 29% free 9571K/13472K, paused 4ms+1ms, total 26ms
D/dalvikvm(12378): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/ContextImpl(12378): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12378): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12378): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12378): ContentProvider is not null
W/ResourceType(12378): No package identifier when getting value for resource number 0x00000000
I/System.out(12378): resource Id::2131361807
E/SQLiteDatabase(12378): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12378): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12378): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12378): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12378): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12378): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12378): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12378): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12378): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12378): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12378): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12378): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12378): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12378): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12378): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12378): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12378): Shutting down VM
W/dalvikvm(12378): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12378): FATAL EXCEPTION: main
E/AndroidRuntime(12378): Process: com.sec.android.app.shealth, PID: 12378
E/AndroidRuntime(12378): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12378): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12378): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12378): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12378): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12378): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12378): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12378): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12378): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12378): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12378): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12378): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12378): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12378): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12378): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12378): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12378): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12378): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12378): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12378): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12378): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12378): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12378): 	... 10 more
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
I/SELinux (12398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12398):  
I/Process (12378): Sending signal. PID: 12378 SIG: 9
I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 12378) (adj 0) has died.
D/HeadlinesChannelApplication( 5873): HeadlinesChannelApplication.onTrimMemory(). level : 60
I/SELinux (12398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12398):  
I/SELinux (12398):  
I/SELinux (12398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12398): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(12398): >>>>> Normal User
E/dalvikvm(12398): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
V/SamsungIME( 3013): onTrimMeomory Level = 5
E/SELinux (12398): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
I/EsApplication( 5941): Trimming memory (onTrimMemory 40)
E/rsC++   ( 2767): RS Message thread exiting.
W/GeoLookout( 3089): at (DisasterAlertApplication.java:67) [onTrimMemory()]
E/OpenGLRenderer( 2767): SFEffectCache:clear(), mSize = 0

```
