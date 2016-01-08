#### Test 55467363832a26e_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7527): 
D/AndroidRuntime( 7527): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7527): CheckJNI is OFF
D/AndroidRuntime( 7527): setted country_code = Poland
D/AndroidRuntime( 7527): setted countryiso_code = PL
D/AndroidRuntime( 7527): setted sales_code = PLS
D/AndroidRuntime( 7527): readGMSProperty: start
D/AndroidRuntime( 7527): readGMSProperty: already setted!!
D/AndroidRuntime( 7527): readGMSProperty: end
D/AndroidRuntime( 7527): addProductProperty: start
D/dalvikvm( 7527): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7527): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7527): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7527): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7527): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7527): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7527): failed to load memtrack module: -2
D/dalvikvm( 7527): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7527): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
I/SurfaceFlinger( 1921): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1921): id=20 createSurf (16x16),-1 flag=20004, EimLayer
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 7557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7557):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7527): Shutting down VM
D/dalvikvm( 7527): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7557):  
I/SELinux ( 7557):  
I/SELinux ( 7557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7557): >>>>> Normal User
E/dalvikvm( 7557): >>>>> com.test.thalitest [ userId:0 | appId:10598 ]
E/SELinux ( 7557): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7557): in addTimaSignatureService
D/TimaKeyStoreProvider( 7557): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7557): Added TimaKesytore provider
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4181): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4181): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1921): id=9 Removed Mauncher (-2/10)
D/Launcher( 2762): onTrimMemory. Level: 20
D/dalvikvm( 7557): GC_CONCURRENT freed 3000K, 30% free 9566K/13492K, paused 2ms+2ms, total 19ms
D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7557): Binding Chromium to the background looper Looper (main, tid 1) {4223cf30}
I/chromium( 7557): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7557): Initializing chromium process, renderers=0
W/chromium( 7557): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7557): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7557): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7557): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7557): Mali API Version : 401
,I/Mali    ( 7557): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7557): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7557): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7557): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7557): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:7557,o:f
,W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7557): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7557): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7557): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7557): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7557): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7557): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7557): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7557): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2419): semi p:7557,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7557): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7557): Enabling debug mode 0
,W/AwContents( 7557): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,V/AlarmManager( 2419): waitForAlarm result :8
,W/AwContents( 7557): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2419): mDVFSHelper.release()
W/IInputConnectionWrapper( 7557): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/JsMessageQueue( 7557): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7557): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4223dcf8
D/dalvikvm( 7557): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4223dcf8
D/jxcore_app_log( 7557): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027602096
D/JX-Cordova( 7557): jxcore cordova android initializing
D/dalvikvm( 7557): GC_CONCURRENT freed 1307K, 17% free 11333K/13560K, paused 2ms+3ms, total 28ms
D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 7557): GC_CONCURRENT freed 1856K, 16% free 14927K/17724K, paused 1ms+2ms, total 46ms
,D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7557): GC_FOR_ALLOC freed 5455K, 29% free 16250K/22804K, paused 48ms, total 48ms
,D/dalvikvm( 7557): GC_CONCURRENT freed 6670K, 31% free 17699K/25364K, paused 1ms+9ms, total 65ms
,D/dalvikvm( 7557): WAIT_FOR_CONCURRENT_GC blocked 55ms
,D/dalvikvm( 7557): GC_FOR_ALLOC freed 1378K, 31% free 17526K/25364K, paused 51ms, total 51ms
,I/dalvikvm-heap( 7557): Grow heap (frag case) to 21.553MB for 3713210-byte allocation
,D/dalvikvm( 7557): GC_FOR_ALLOC freed 46K, 28% free 21105K/28992K, paused 47ms, total 47ms
,I/PowerManagerService( 2419): [PWL] Off : 225s ago
,W/jxcore-log( 7557): Initializing JXcore engine
,W/jxcore-log( 7557): JXcore engine is ready
,W/jxcore-log( 7557): Starting JXcore engine
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/jxcore-log( 7557): Platform android
W/jxcore-log( 7557): 
,W/jxcore-log( 7557): Process ARCH arm
W/jxcore-log( 7557): 
,I/jxcore-log( 7557): JXcore Cordova bridge is ready!
I/jxcore-log( 7557): 
,W/jxcore-log( 7557): JXcore engine is started
,I/chromium( 7557): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7557): Toggling radios to true
I/jxcore-log( 7557): 
,D/BluetoothAdapter( 7557): enable(): BT is already enabled..!
,I/WifiManager( 7557): packageName : com.test.thalitest
,I/WifiManager( 7557): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7557, uid=10598
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7557, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7557, uid=10598 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7557, uid=10598
I/jxcore-log( 7557): Radios toggled
I/jxcore-log( 7557): 
,I/wpa_supplicant( 3960): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3960): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log( 7557): Received device characteristics:
I/jxcore-log( 7557): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7557): Bluetooth name: S5mini-1
I/jxcore-log( 7557): Device name: samsung-SM-G800F
I/jxcore-log( 7557): 
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3960): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3960): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3960): First Scan Start
,I/jxcore-log( 7557): Perf Test app loaded loaded
I/jxcore-log( 7557): 
W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3960): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/jxcore-log( 7557): check test folder
I/jxcore-log( 7557): 
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
I/wpa_supplicant( 3960): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3960): Skip scan - already scanning
,I/jxcore-log( 7557): found test : ./testFindPeers.js
I/jxcore-log( 7557): 
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2419): InactiveState{ what=143375 }
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2419): Attempting to switch to mobile
D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7603): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7603):  
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 10% free 9503K/10472K, paused 4ms+7ms, total 52ms
,V/RouteController( 1915): RTNETLINK answers: No such process
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
I/SELinux ( 7603): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7603):  
I/SELinux ( 7603):  
I/SELinux ( 7603): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7603): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7603): >>>>> Normal User
E/dalvikvm( 7603): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
I/jxcore-log( 7557): found test : ./testSendData.js
I/jxcore-log( 7557): 
E/SELinux ( 7603): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2419): Error! unhandled message{ when=-96ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-95ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 3ms+4ms, total 35ms,
W/NetworkManagementService( 2419): route cmd failed: ,
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2419): '
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2419): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
,W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2419): 	at android.os.Handler.dispatchMessage(Handler.java:102),
W/NetworkManagementService( 2419): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1,
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-24ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,D/TimaKeyStoreProvider( 7603): in addTimaSignatureService,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 2ms+4ms, total 33ms
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7603): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7603): Added TimaKesytore provider,
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x7b963568 clazz=0x61c00001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,V/NativeCrypto( 2849): Read error: ssl=0x7bad18d8: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7bad18d8: I/O error during system call, Broken pipe
,D/dalvikvm( 7603): GC_CONCURRENT freed 2997K, 30% free 9573K/13492K, paused 3ms+1ms, total 30ms
,D/dalvikvm( 7603): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SPPClientService( 5513): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5513): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5513): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.,
,E/SPPClientService( 5513): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5513): [b] ResponseMap empty,
,I/System.out( 7603): Inside WakeupProvider,
,I/System.out( 7603): Inside onCreate() of WakeupTriggerProvide,
,V/NetworkStats( 2419): updateIfacesLocked(),
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 29ms
I/chromium( 7557): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/VlingoApplication( 7603): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7603): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7603): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2821): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7603): initQueue()
I/ActivityManager( 2419): Killing 5363:com.google.android.talk/u0a109 (adj 15): empty #43
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2821): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2821): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7632): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7632):  
,I/SELinux ( 7632): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7632):  
I/SELinux ( 7632):  
,I/SELinux ( 7632): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7632): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7632): >>>>> Normal User
,E/dalvikvm( 7632): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7632): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7632): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7632): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7632): Added TimaKesytore provider
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2419): updateDataUsageMap
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7632): GC_CONCURRENT freed 2990K, 29% free 9577K/13488K, paused 4ms+3ms, total 55ms
,D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 46ms
,I/dalvikvm( 7632): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7632): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0008,
,I/wpa_supplicant( 3960): nl80211: Received scan results (7 BSSes),
I/wpa_supplicant( 3960): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3960): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/dalvikvm( 7632): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7632): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0000
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,E/dalvikvm( 7632): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
,W/dalvikvm( 7632): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0037
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3960): Associated with C0.AA.48
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3960): freq(2412) increment count 2
,I/wpa_supplicant( 3960): meet head of list.
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3960): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3960): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3960): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7632): Link of class 'Ldqp;' failed
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7632): Link of class 'Ldqp;' failed
I/dalvikvm( 7632): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0000
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/dalvikvm( 7632): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7632): Link of class 'Ldqp;' failed
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7632): Link of class 'Ldqp;' failed
I/dalvikvm( 7632): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7632): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7632): Link of class 'Ldqp;' failed
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7632): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7632): Link of class 'Ldqp;' failed
,I/dalvikvm( 7632): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7632): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7632): Link of class 'Lax;' failed
E/dalvikvm( 7632): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7632): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7632): Link of class 'Laz;' failed
E/dalvikvm( 7632): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7632): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7632): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7632): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0006
,I/dalvikvm( 7632): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7632): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7632): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7632): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7632): VFY: replacing opcode 0x72 at 0x0000
,I/dalvikvm( 7632): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7632): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7632): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7632): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x23 at 0x0005
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/dalvikvm( 7632): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7632): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7632): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7632): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7632): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7632): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7632): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7632): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7632): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7632): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,W/dalvikvm( 7632): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7632): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7632): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7632): Link of class 'Lax;' failed
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7632): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7632): Link of class 'Laz;' failed
D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/dalvikvm( 7632): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227f830
,D/dalvikvm( 7632): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x4227f830
,I/dalvikvm( 7632): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 7632): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7632): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7632): MmsConfig.loadMmsSettings
I/Babel_SMS( 7632): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7632): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7632): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7632): MmsConfig.loadFromResources
,E/Babel_SMS( 7632): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7632): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/dhcpcd  ( 7646): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7646): bssid match
,W/dalvikvm( 7632): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7632): Link of class 'Lfzc;' failed
E/dalvikvm( 7632): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7632): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7632): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7632): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7632): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7632): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7632): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7632): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7632): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7632): Link of class 'Lfzc;' failed
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,W/Settings( 7632): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
I/Babel_Crash( 7632): startup - clean
,D/dalvikvm( 7632): GC_CONCURRENT freed 1796K, 21% free 10855K/13572K, paused 4ms+5ms, total 43ms
D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/Babel   ( 7632): deleted: false for 0
,I/dalvikvm( 7632): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
,W/dalvikvm( 7632): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7632): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7632): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7632): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7632): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7632): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7632): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7632): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7632): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 7632): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7632): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): noConnectivity : true
I/dalvikvm( 7632): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7632): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7632): VFY: replacing opcode 0x6e at 0x0074
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/vclib   ( 7632): onServiceConnected
,W/Babel   ( 7632): Attempted to change video mute state without an active call.
I/ActivityManager( 2419): Killing 6261:com.sec.phone/1001 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,D/dalvikvm( 7632): GC_CONCURRENT freed 961K, 14% free 11904K/13804K, paused 3ms+3ms, total 45ms
,D/dalvikvm( 7632): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7665): Added TimaKesytore provider
,D/dalvikvm( 7632): GC_FOR_ALLOC freed 488K, 15% free 12397K/14572K, paused 37ms, total 37ms
,D/dalvikvm( 7632): GC_FOR_ALLOC freed 1759K, 21% free 12768K/16156K, paused 37ms, total 37ms
,D/dalvikvm( 7665): GC_CONCURRENT freed 2987K, 30% free 9573K/13488K, paused 4ms+2ms, total 33ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/ActivityManager( 2419): Killing 6475:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 7684): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7684):  
,I/SELinux ( 7684): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7684):  
I/SELinux ( 7684):  
,I/SELinux ( 7684): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7684): >>>>> Normal User
,E/dalvikvm( 7684): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7684): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7684): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7684): Added TimaKesytore provider
,D/dalvikvm( 7684): GC_CONCURRENT freed 2997K, 30% free 9566K/13488K, paused 6ms+2ms, total 43ms
,D/dalvikvm( 7684): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/KLMS-2.3.201 : ( 7684): KLMSValidator() : checkQATesting(),
,D/WifiP2pService( 2419): InactiveState{ what=143375 },
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2419): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check,
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling,
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/KLMS-2.3.201 : ( 7684): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452272229450
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/KLMS-2.3.201 : ( 7684): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2419): Killing 6282:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/SELinux ( 7710): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7710):  
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
I/SELinux ( 7710): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7710):  
I/SELinux ( 7710):  
,I/SELinux ( 7710): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7710): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7710): >>>>> Normal User
,E/dalvikvm( 7710): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7710): [DEBUG] seapp_context_lookup: seinfoCategory = release
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
E/Watchdog( 2419): !@Sync 11
,D/TimaKeyStoreProvider( 7710): in addTimaSignatureService,
V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
D/TimaKeyStoreProvider( 7710): Cannot add TimaSignature Service, License check Failed
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,D/ActivityThread( 7710): Added TimaKesytore provider,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2419): updateIfacesLocked(),
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,V/NetworkStats( 2419): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): performPollLocked() took 19ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,I/jxcore-log( 7557): Connected to the server!,
I/jxcore-log( 7557): 
,I/chromium( 7557): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63),
D/dalvikvm( 7710): GC_CONCURRENT freed 3001K, 30% free 9566K/13488K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 7710): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7710): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/SO_AGENT( 7710): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available,
,I/SA      ( 5778): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
I/SA      ( 5778): [BDLM] already registered in spp
,I/SA      ( 5778): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5778): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5778): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5778): [OR] == isSIMCardReady false ==
,I/SA      ( 5778): [SCU] == networkStateCheck == true
,I/SA      ( 5778): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5778): isChinaCountryCode : false
,I/SA      ( 5778): [OR] == networkStateCheck true ==
,I/SA      ( 5778): [OR] GetMyCountryZoneTask
I/SA      ( 5778): [OR] onReceive END
,I/SA      ( 5778): [SRS] prepareGetMyCountryZone
,I/SA      ( 5778): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5778): [SSP] query invoked,
I/ActivityManager( 2419): Killing 6525:com.samsung.android.scloud.backup/u0a62 (adj 15): empty #43
,I/SA      ( 5778): [TPMU] GetMccFromDB : null,
I/SA      ( 5778): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5778): [TPM] isNoProxy(default) : true
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive,
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SA      ( 5778): [RC New] Execute method=[GET] start,
,I/SELinux ( 7741): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7741):  
,I/SELinux ( 7741): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7741):  
I/SELinux ( 7741):  
,I/SELinux ( 7741): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7741): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7741): >>>>> Normal User
,E/dalvikvm( 7741): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7741): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7741): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7741): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7741): Added TimaKesytore provider
,D/dalvikvm( 7741): GC_CONCURRENT freed 3005K, 30% free 9564K/13492K, paused 3ms+1ms, total 30ms
,D/dalvikvm( 7741): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/dalvikvm( 2419): GC_CONCURRENT freed 4220K, 56% free 24910K/56044K, paused 10ms+20ms, total 231ms
,I/sCloudBackupApp( 7741): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7741): Other Intent
I/ActivityManager( 2419): Killing 6488:com.android.chrome/u0a85 (adj 15): empty #43
,I/SELinux ( 7755): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7755):  
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4733): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7755): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7755):  
I/SELinux ( 7755):  
,I/SELinux ( 7755): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7755): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7755): >>>>> Normal User
,E/dalvikvm( 7755): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7755): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7755): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7755): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7755): Added TimaKesytore provider
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7755): GC_CONCURRENT freed 2991K, 30% free 9574K/13492K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7755): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7755): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7755): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5309): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7755): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5309): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7755): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5309): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6505:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,D/Headlines( 5846): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5846): getCountryCode(): countryCode = PL
,D/Headlines( 5846): Breath.onCreate
,D/Headlines( 5846): Breath timer started. interval : 30000
,I/SELinux ( 7768): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7768):  
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5846): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5846): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5846): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7768): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7768):  
I/SELinux ( 7768):  
,I/SELinux ( 7768): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7768): >>>>> Normal User
,E/dalvikvm( 7768): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7768): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7768): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7768): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7768): Added TimaKesytore provider
,D/dalvikvm( 7768): GC_CONCURRENT freed 2995K, 30% free 9576K/13496K, paused 5ms+3ms, total 37ms
,D/dalvikvm( 7768): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/SA      ( 5778): [RC New] [v2liruge] api execute + 987
,I/SA      ( 5778): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5778): AsyncTask #2 calls detatch()
,I/SA      ( 5778): [TPMU] getNetworkMcc : 
I/SA      ( 5778): [SCU] saveMccToPreferece Start
I/SA      ( 5778): [SCU] RegionMCC : 260,
,I/SA      ( 5778): [SSP] query invoked,
,I/SA      ( 5778): [TPMU] GetMccFromDB : null,
,I/SA      ( 5778): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5778): [SCU] saveMccToPreferece End,
I/SA      ( 5778): [RC New] executeRequest [v2liruge] end. 1011
,I/SA      ( 5778): [RC New] Execute end
I/SA      ( 5778): [OR] GetMyCountryZoneTask mcc = 260,
,I/SA      ( 5778): [OR] GetMyCountryZoneTask Success
,V/WebViewChromium( 7768): Binding Chromium to the background looper Looper (main, tid 1) {42239ea0}
,I/chromium( 7768): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7768): Initializing chromium process, renderers=0
,W/chromium( 7768): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7768): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7768): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7768): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7768): Mali API Version : 401
,I/Mali    ( 7768): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/GAV2    ( 7768): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7768): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
,I/NSApplication( 7768): Starting up...,
,I/jxcore-log( 7557): --- start :testFindPeers.js---
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): testFindPeers created [object Object]
I/jxcore-log( 7557): 
,I/jxcore-log( 7557): serverPort is 8876
I/jxcore-log( 7557): 
,I/iu.Environment( 5910): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/dalvikvm( 7557): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7557): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7557): setDiscoveryMode: Mode set to BLE
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7557): setDiscoveryMode: Mode set to BLE_AND_WIFI
D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/QuickConnect[1.1][2] ( 5112): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7557): start: Peer ID: 00:F4:6F:30:E0:6C, peer name: S5mini-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7557): bind: Binding a new listener
,I/QuickConnect[1.1][2] ( 5112): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5112): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42243770
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7557): initialize: My bluetooth address is 00:F4:6F:30:E0:6C
,I/SELinux ( 7806): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7806):  
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7557): verifyIdentityString: Identity string created: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"S5mini-1"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7557): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7557): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 4000): SOCK FLAG = 0 ***********************
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7557): Waiting for incoming connections...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7557): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7557): start: OK
,I/io.jxcore.node.ConnectionHelper( 7557): start: Using peer discovery mode: BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7557): start: Peer ID: 00:F4:6F:30:E0:6C, peer name: S5mini-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7557): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7557): bind: Binding a new listener
,W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 7557): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
W/dalvikvm( 7557): VFY: unable to resolve new-instance 427 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
,D/dalvikvm( 7557): VFY: replacing opcode 0x22 at 0x0013
W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
I/dalvikvm( 7557): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
W/dalvikvm( 7557): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0002
E/dalvikvm( 7557): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 7557): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 7557): VFY: replacing opcode 0x22 at 0x002d
,W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 7557): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 7557): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
W/dalvikvm( 7557): VFY: unable to resolve virtual method 1808: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 7557): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
W/dalvikvm( 7557): VFY: unable to resolve virtual method 1809: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
,D/dalvikvm( 7557): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
,D/dalvikvm( 7557): DexOpt: unable to opt direct call 0x0709 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
W/dalvikvm( 7557): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 7557): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
D/dalvikvm( 7557): DexOpt: unable to opt direct call 0x072a at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
I/SELinux ( 7806): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7806):  
I/SELinux ( 7806):  
,I/SELinux ( 7806): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 7557): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
D/dalvikvm( 7557): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
E/SELinux ( 7806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7806): >>>>> Normal User
,E/dalvikvm( 7806): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7806): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/AndroidRuntime( 7557): Shutting down VM
,W/dalvikvm( 7557): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at android.os.Looper.loop(Looper.java:146)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7557): 	at dalvik.system.NativeStart.main(Native Method)
,D/TimaKeyStoreProvider( 7806): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7806): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7806): Added TimaKesytore provider
,D/dalvikvm( 7806): GC_CONCURRENT freed 2992K, 29% free 9582K/13496K, paused 4ms+1ms, total 31ms
,D/dalvikvm( 7806): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7826): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7826):  
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2419): Killing 6311:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7826): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7826):  
I/SELinux ( 7826):  
,I/SELinux ( 7826): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/SELinux ( 7830): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7830):  
E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7826): >>>>> Normal User
,E/dalvikvm( 7826): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7826): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7826): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7826): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7826): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 5956:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7830): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7830):  
I/SELinux ( 7830):  
,I/SELinux ( 7830): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7830): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7830): >>>>> Normal User
,E/dalvikvm( 7830): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7830): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7830): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7830): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7830): Added TimaKesytore provider
,D/dalvikvm( 7826): GC_CONCURRENT freed 2996K, 30% free 9566K/13488K, paused 4ms+1ms, total 35ms
,D/dalvikvm( 7826): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/BadgeProvider( 7826): onCreate
,D/BadgeProvider( 7826): DatabaseHelper
,D/BadgeProvider( 7826): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7830): GC_CONCURRENT freed 3000K, 30% free 9566K/13488K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7830): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Launcher.Model( 2762): reloadBadges entered.
D/BadgeProvider( 7826): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7826): sendNotify, [notify] : null
D/BadgeProvider( 7826): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7826): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7826): update, [UpdateCount] : 1
,D/WaitQueueForNetworkActivate( 6806): notifyNetworkActivated
,W/ContextImpl( 6806): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2419): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7632): Thread-653(HTTPLog):isShipBuild true
,I/System.out( 7632): Thread-653(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/Babel   ( 7632): connection state changed from UNKNOWN to CONNECTED
,D/hcjo    ( 6806): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6806): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6806): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6806): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6806): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6806): exit::IDLE
,D/InitializeManagerStateMachine( 6806): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6806): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6806): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6806): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6806): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6806): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6806): entry::SUCCESS
,D/hcjo    ( 6806): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6806): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6806): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6806): exit::SUCCESS
,D/InitializeManagerStateMachine( 6806): entry::IDLE
,E/SPPClientService( 5513): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5513): [SystemStateMoniter] Current Time : 351070
,E/SPPClientService( 5513): [SystemStateMoniter] No Connect : true
I/ActivityManager( 2419): Killing 6296:com.android.providers.calendar/u0a45 (adj 15): empty #43
,E/SPPClientService( 5513): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5513): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5513): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5513): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2821): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2821): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2821): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5513): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=22 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5513): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5513): [a] [ConnectionManager] Connection is already disconnected.
D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/NearbySettings( 2821): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2821): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5513): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/KLMS-2.3.201 : ( 7684): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/KLMS-2.3.201 : ( 7684): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452272233026
,I/KLMS-2.3.201 : ( 7684): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7710): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3255): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7710): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3255): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3255): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3255): [Slink platform] The state of Slink geocode service is true
,I/SA      ( 5778): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5778): [BDLM] already registered in spp
,I/SA      ( 5778): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5778): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5778): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5778): [OR] == isSIMCardReady false ==
,I/SA      ( 5778): [SCU] == networkStateCheck == true
I/SA      ( 5778): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5778): isChinaCountryCode : false
,I/SA      ( 5778): [OR] == networkStateCheck true ==
,I/SA      ( 5778): [OR] GetMyCountryZoneTask
I/SA      ( 5778): [OR] onReceive END
,I/SA      ( 5778): [SRS] prepareGetMyCountryZone
I/SA      ( 5778): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5778): [SSP] query invoked
,I/SELinux ( 7866): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7866):  
,I/GallerySearchProvider( 3383): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SA      ( 5778): [TPMU] GetMccFromDB : null
,I/SA      ( 5778): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5778): [TPM] isNoProxy(default) : true
,I/SA      ( 5778): [RC New] Execute method=[GET] start
D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 10% free 9503K/10472K, paused 3ms+5ms, total 44ms
,I/SCloudBackupReceiver( 7741): Other Intent
,I/SELinux ( 7866): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7866):  
I/SELinux ( 7866):  
,I/SELinux ( 7866): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7866): >>>>> Normal User
,E/dalvikvm( 7866): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7866): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 2ms+5ms, total 34ms
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7755): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 7866): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7866): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7866): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 3ms+4ms, total 35ms
,I/SELinux ( 7881): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7881):  
,D/Headlines( 5846): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5846): getCountryCode(): countryCode = PL
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5846): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5846): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5846): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5846): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7881): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7881):  
I/SELinux ( 7881):  
,I/SELinux ( 7881): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7881): >>>>> Normal User
,E/dalvikvm( 7881): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7881): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/iu.Environment( 5910): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/TimaKeyStoreProvider( 7881): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7881): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7881): Added TimaKesytore provider
,D/dalvikvm( 7866): GC_CONCURRENT freed 2997K, 30% free 9573K/13492K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7866): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/QuickConnect[1.1][2] ( 5112): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5112): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5112): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42243770
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/hcjo    ( 6806): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6806): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6806): exit::IDLE
,D/InitializeManagerStateMachine( 6806): entry::NETWORK_CHECK
,D/dalvikvm( 7881): GC_CONCURRENT freed 3013K, 30% free 9560K/13496K, paused 3ms+1ms, total 36ms
,D/dalvikvm( 7881): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/InitializeManagerStateMachine( 6806): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6806): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6806): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6806): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6806): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6806): entry::SUCCESS
,D/hcjo    ( 6806): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/System.out( 7665): Thread-645(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/hcjo    ( 6806): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6806): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6806): exit::SUCCESS
,D/InitializeManagerStateMachine( 6806): entry::IDLE
,I/System.out( 7665): Thread-645(ApacheHTTPLog):isShipBuild true
,I/System.out( 7665): Thread-645(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/KVNProvider( 7881): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7881): getFindoCursor query string : 
,E/SPPClientService( 5513): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5513): [SystemStateMoniter] Current Time : 352191
,E/SPPClientService( 5513): [SystemStateMoniter] No Connect : false
,V/KVNProvider( 7881): getTagSearchCursor() tagSearchCursor count : 0
,D/dalvikvm( 5513): GC_CONCURRENT freed 2027K, 23% free 10438K/13484K, paused 4ms+7ms, total 58ms
,D/dalvikvm( 5513): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/System.out( 7665): AsyncTask #1 calls detatch(),
,W/System.err( 7665): com.sec.android.fota.osp.http.RestClientException,
,W/System.err( 7665): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7665): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7665): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7665): ,	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7665): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7665): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7665): ,	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7665): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7665): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7665): Caused by: java.lang.NullPointerException,
W/System.err( 7665): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7665): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7665): ,	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7665): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7665): ,	... 8 more
,I/ActivityManager( 2419): Killing 6134:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43,
,I/SA      ( 5778): [RC New] [v2liruge] api execute + 691,
I/SA      ( 5778): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5778): AsyncTask #3 calls detatch(),
,I/SA      ( 5778): [TPMU] getNetworkMcc : ,
I/SA      ( 5778): [SCU] saveMccToPreferece Start
I/SA      ( 5778): [SCU] RegionMCC : 260
,I/SA      ( 5778): [SSP] query invoked,
I/SA      ( 5778): [TPMU] GetMccFromDB : null
I/SA      ( 5778): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5778): [SCU] saveMccToPreferece End
I/SA      ( 5778): [RC New] executeRequest [v2liruge] end. 704
I/SA      ( 5778): [RC New] Execute end
,I/SA      ( 5778): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5778): [OR] GetMyCountryZoneTask Success
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7896): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7896):  
,I/SELinux ( 7896): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7896):  
I/SELinux ( 7896):  
,I/SELinux ( 7896): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7896): >>>>> Normal User
,E/dalvikvm( 7896): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7896): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7896): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7896): Added TimaKesytore provider
,D/dalvikvm( 7896): GC_CONCURRENT freed 2994K, 30% free 9576K/13496K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7896): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 1843 latestRequest time : 1452272233299 current time : 1452272235142
,I/ActivityManager( 2419): Killing 6170:com.google.android.music:main/u0a125 (adj 15): empty #43
,E/SPPClientService( 5513): [b] __InitReply__
,I/GAV2    ( 7768): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=22 Removed Uoast (-2/11)
I/ActivityManager( 2419): Killing 5561:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 354766
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
,D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3467)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6612): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6612): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6612): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6612): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6612): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6612): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6612): [ensureRegistration] - No Samsung account
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false,
,D/PreloadUpdateManagerStateMachine( 6806): execute::IDLE:EXECUTE,
,D/PreloadUpdateManagerStateMachine( 6806): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6806): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6806): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6806): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6806): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6806): entry::IDLE,
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 6806): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6806): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6806): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 6806): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6806): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6806): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6806): entry::IDLE,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{448685d0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43d9d3f0 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4000): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 12
,V/AlarmManager( 2419): waitForAlarm result :8,
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 41666 latestRequest time : 1452272233299 current time : 1452272274966
,I/SELinux ( 8169): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8169):  
,I/SELinux ( 8169): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8169):  
I/SELinux ( 8169):  
,I/SELinux ( 8169): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8169): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8169): >>>>> Normal User
,E/dalvikvm( 8169): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8169): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8169): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8169): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8169): Added TimaKesytore provider
,D/dalvikvm( 8169): GC_CONCURRENT freed 3008K, 30% free 9556K/13488K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 8169): WAIT_FOR_CONCURRENT_GC blocked 21ms
,E/SPPClientService( 8169): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8169): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8169): PushLog.txt file is not deleted.
D/SPPClientService( 8169): PushLog.txt file is not deleted.
,D/SPPClientService( 8169): ============PushLog. stop!
,I/ActivityManager( 2419): Killing 6340:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/dalvikvm( 2419): GC_EXPLICIT freed 1885K, 56% free 24855K/56044K, paused 16ms+20ms, total 240ms
,E/SPPClientService( 5513): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2580): GC_CONCURRENT freed 15709K, 33% free 33886K/50516K, paused 20ms+10ms, total 169ms
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 13
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 57260 latestRequest time : 1452272233299 current time : 1452272290559
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 14
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 87260 latestRequest time : 1452272233299 current time : 1452272320560
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 15
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 117260 latestRequest time : 1452272233299 current time : 1452272350559
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 16
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5846): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5846): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5846): Breath 147263 latestRequest time : 1452272233299 current time : 1452272380563
,D/Headlines( 5846): stop 
,D/Headlines( 5846): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6451:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 17
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 18
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 19
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 21
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/GAV2    ( 5605): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5605): Thread[disconnect check,5,main]: Disconnected from service
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 22
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4076): GC_CONCURRENT freed 2880K, 29% free 9727K/13528K, paused 22ms+3ms, total 94ms
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 23
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2419, ws=WorkSource{10012}) (elapsedTime=36)
,I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'Event Log Handoff' (uid=10012, pid=3445, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=7)
,I/EventLogService( 3445): Aggregate from 1452270740621 (log), 1452270740621 (data)
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2419): LightSensor enable = 0
D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 24
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 25
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2419): GC_CONCURRENT freed 3797K, 56% free 24810K/56044K, paused 16ms+18ms, total 230ms
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 26
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 27
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9647
,E/Watchdog( 2419): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2762): GC_CONCURRENT freed 7167K, 39% free 18928K/30644K, paused 12ms+7ms, total 101ms
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3739K, 56% free 24801K/56044K, paused 20ms+18ms, total 245ms
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SPPClientService( 5513): [b] __PingReply__
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2419): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
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
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4076): GC_CONCURRENT freed 2048K, 29% free 9725K/13528K, paused 2ms+3ms, total 25ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5513): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5513): [b] __PingReply__
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3682K, 56% free 24841K/56044K, paused 16ms+16ms, total 210ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 42ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2016-01-08-02-27-00.bin
,I/ProcessStatsService( 2419): Prepared write state in 62ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
V/AlarmManager( 2419): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x3)
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/NetworkStats( 2419): performPollLocked() took 45ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12395):  
,I/SELinux (12395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12395):  
I/SELinux (12395):  
,I/SELinux (12395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12395): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12395): >>>>> Normal User
,E/dalvikvm(12395): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12395): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12395): in addTimaSignatureService
,D/TimaKeyStoreProvider(12395): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12395): Added TimaKesytore provider
,D/dalvikvm(12395): GC_CONCURRENT freed 3012K, 30% free 9556K/13496K, paused 3ms+2ms, total 25ms
,D/dalvikvm(12395): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/@ WidgetProvider(12395): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12395): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12395): Widget random data : 1
,D/@ WidgetProvider(12395): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12395): Widget random data : 9
,E/dalvikvm(12395): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12395): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12395): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12395): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12395): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12395): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12395): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12395): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12395): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12395): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12395): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12395): VFY: replacing opcode 0x22 at 0x0038
I/ActivityManager( 2419): Killing 6586:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/dalvikvm(12395): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(12395): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12395): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12395): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dalvikvm( 2849): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,E/dalvikvm( 2849): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2849): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
,D/dalvikvm( 2849): VFY: replacing opcode 0x1f at 0x0011
,I/dalvikvm( 2849): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2849): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
,D/dalvikvm( 2849): VFY: replacing opcode 0x6e at 0x003d
,I/System.out(12395): Thread-684(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12395): Thread-684(ApacheHTTPLog):isShipBuild true
,I/System.out(12395): Thread-684(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out( 2849): Thread-55(HTTPLog):isShipBuild true
,I/System.out( 2849): Thread-55(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12395): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12395): AsyncNetworking-1-thread-1 calls detatch()
,D/dalvikvm( 2849): GC_CONCURRENT freed 1914K, 22% free 10853K/13760K, paused 8ms+6ms, total 62ms
,V/ImageManager(12395): Max ALLOWED memory (MB): 128
V/ImageManager(12395): Max SHOULD USE memory (MB): 128
,V/ImageManager(12395): Max Image Cache memory (MB): 32
,D/skia    (12395): getTotalSize : Do not get file length
,D/@ WidgetProvider(12395): Building widget : 5
,I/SELinux (12416): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12416):  
,I/SELinux (12416): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12416):  
I/SELinux (12416):  
,I/SELinux (12416): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12416): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm(12416): >>>>> Normal User
,E/dalvikvm(12416): >>>>> com.google.android.youtube [ userId:0 | appId:10175 ]
,E/SELinux (12416): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider(12416): in addTimaSignatureService
,D/TimaKeyStoreProvider(12416): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12416): Added TimaKesytore provider
,D/dalvikvm(12416): GC_CONCURRENT freed 3016K, 30% free 9553K/13492K, paused 3ms+2ms, total 27ms
,D/dalvikvm(12416): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/dalvikvm(12416): Could not find class 'android.app.Notification$Action$Builder', referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve new-instance 406 (Landroid/app/Notification$Action$Builder;) in Lb;
,D/dalvikvm(12416): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm(12416): Unable to resolve superclass of Lal; (749)
W/dalvikvm(12416): Link of class 'Lal;' failed
E/dalvikvm(12416): Could not find class 'al', referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve new-instance 304 (Lal;) in Lb;
,D/dalvikvm(12416): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm(12416): Unable to resolve superclass of Lan; (749)
W/dalvikvm(12416): Link of class 'Lan;' failed
E/dalvikvm(12416): Could not find class 'an', referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve new-instance 358 (Lan;) in Lb;
,D/dalvikvm(12416): VFY: replacing opcode 0x22 at 0x002a
I/dalvikvm(12416): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve virtual method 5407: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm(12416): Could not find method android.view.View.getTransitionName, referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve virtual method 5231: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0006
,W/dalvikvm(12416): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
,E/dalvikvm(12416): Could not find class 'android.app.RemoteInput[]', referenced from method b.a
W/dalvikvm(12416): VFY: unable to resolve new-array 12200 ([Landroid/app/RemoteInput;) in Lb;
,D/dalvikvm(12416): VFY: replacing opcode 0x23 at 0x0005
,D/dalvikvm(12416): DexOpt: unable to opt direct call 0x090f at 0x0e in Lb;.a
,W/dalvikvm(12416): Unable to resolve superclass of Lal; (749)
W/dalvikvm(12416): Link of class 'Lal;' failed
D/dalvikvm(12416): DexOpt: unable to opt direct call 0x068d at 0x08 in Lb;.a
W/dalvikvm(12416): Unable to resolve superclass of Lan; (749)
W/dalvikvm(12416): Link of class 'Lan;' failed
,D/dalvikvm(12416): DexOpt: unable to opt direct call 0x0802 at 0x2c in Lb;.a
,D/dalvikvm(12416): DexOpt: unable to opt direct call 0x0957 at 0x13 in Lb;.a
,I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method dyp.a
,W/dalvikvm(12416): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(12416): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(12416): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(12416): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm(12416): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm(12416): VFY: unable to resolve instance field 36
,D/dalvikvm(12416): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm(12416): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm(12416): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm(12416): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm(12416): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm(12416): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm(12416): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422e4ef0
,D/dalvikvm(12416): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422e4ef0
,D/dalvikvm(12416): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422e4ef0, skipping init
,D/dalvikvm(12416): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422e4ef0
,D/dalvikvm(12416): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422e4ef0
,V/JNIHelp (12416): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm(12416): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x000d
,D/dalvikvm(12416): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422e4ef0
,D/dalvikvm(12416): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422e4ef0
D/dalvikvm(12416): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422e4ef0
,D/dalvikvm(12416): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422e4ef0
,I/dalvikvm(12416): Could not find method android.security.NetworkSecurityPolicy.getInstance, referenced from method com.google.android.gms.ads.internal.t.e.a
W/dalvikvm(12416): VFY: unable to resolve static method 1032: Landroid/security/NetworkSecurityPolicy;.getInstance ()Landroid/security/NetworkSecurityPolicy;
,D/dalvikvm(12416): VFY: replacing opcode 0x71 at 0x004e
,D/dalvikvm(12416): DexOpt: --- BEGIN 'ads-1046697416.jar' (bootstrap=0) ---
,I/ProviderInstaller(12416): Installed default security provider GmsCore_OpenSSL
,D/dalvikvm(12443): DexOpt: load 5ms, verify+opt 18ms, 194052 bytes
,D/dalvikvm(12416): DexOpt: --- END 'ads-1046697416.jar' (success) ---
,D/dalvikvm(12416): DEX prep '/data/data/com.google.android.youtube/cache/ads-1046697416.jar': unzip in 0ms, rewrite 127ms
,E/YouTube MDX(12416): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/dalvikvm(12416): GC_CONCURRENT freed 1886K, 21% free 10704K/13496K, paused 6ms+5ms, total 53ms
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12416): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(12416): VFY: unable to resolve virtual method 2614: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/ComponentName;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getActivityBanner, referenced from method agv.getActivityBanner
W/dalvikvm(12416): VFY: unable to resolve virtual method 2615: Landroid/content/pm/PackageManager;.getActivityBanner (Landroid/content/Intent;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(12416): VFY: unable to resolve virtual method 2622: Landroid/content/pm/PackageManager;.getApplicationBanner (Landroid/content/pm/ApplicationInfo;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getApplicationBanner, referenced from method agv.getApplicationBanner
W/dalvikvm(12416): VFY: unable to resolve virtual method 2623: Landroid/content/pm/PackageManager;.getApplicationBanner (Ljava/lang/String;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getLeanbackLaunchIntentForPackage, referenced from method agv.getLeanbackLaunchIntentForPackage
W/dalvikvm(12416): VFY: unable to resolve virtual method 2639: Landroid/content/pm/PackageManager;.getLeanbackLaunchIntentForPackage (Ljava/lang/String;)Landroid/content/Intent;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method agv.getPackageInstaller
W/dalvikvm(12416): VFY: unable to resolve virtual method 2643: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getUserBadgedDrawableForDensity, referenced from method agv.getUserBadgedDrawableForDensity
W/dalvikvm(12416): VFY: unable to resolve virtual method 2659: Landroid/content/pm/PackageManager;.getUserBadgedDrawableForDensity (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;Landroid/graphics/Rect;I)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getUserBadgedIcon, referenced from method agv.getUserBadgedIcon
W/dalvikvm(12416): VFY: unable to resolve virtual method 2660: Landroid/content/pm/PackageManager;.getUserBadgedIcon (Landroid/graphics/drawable/Drawable;Landroid/os/UserHandle;)Landroid/graphics/drawable/Drawable;
D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
I/dalvikvm(12416): Could not find method android.content.pm.PackageManager.getUserBadgedLabel, referenced from method agv.getUserBadgedLabel
W/dalvikvm(12416): VFY: unable to resolve virtual method 2661: Landroid/content/pm/PackageManager;.getUserBadgedLabel (Ljava/lang/CharSequence;Landroid/os/UserHandle;)Ljava/lang/CharSequence;
,D/dalvikvm(12416): VFY: replacing opcode 0x6e at 0x0002
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl(12416): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12416): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl(12416): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/InstanceID/Rpc(12416): Found 10012
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl(12416): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/System.out(12416): Thread-748(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12416): Thread-748(ApacheHTTPLog):isShipBuild true
,I/System.out(12416): Thread-748(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(12416): Thread-748 calls detatch()
,D/dalvikvm(12416): GC_CONCURRENT freed 1312K, 17% free 11320K/13576K, paused 5ms+5ms, total 47ms
,I/System.out(12416): Thread-740 calls detatch()
,I/ActivityManager( 2419): Killing 6600:com.android.musicfx/u0a24 (adj 15): empty #43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2419): GC_CONCURRENT freed 3702K, 56% free 24915K/56044K, paused 8ms+16ms, total 210ms
,I/ActivityManager( 2419): Killing 5664:com.android.mms/u0a49 (adj 15): empty for 1800s
,I/ActivityManager( 2419): Killing 6659:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1800s
,I/ActivityManager( 2419): Killing 5980:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1800s
,I/ActivityManager( 2419): Killing 6628:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1801s
,I/ActivityManager( 2419): Killing 6357:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1800s
,D/CountryDetector( 2419): No listener is left
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Killing 6437:com.sec.knox.bridge/1000 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 4836:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 6400:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1824s
,I/ActivityManager( 2419): Killing 6775:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1825s
,I/ActivityManager( 2419): Killing 6761:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1826s
I/ActivityManager( 2419): Killing 6749:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6737:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6724:com.samsung.helphub/1000 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6711:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6699:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1826s
,I/ActivityManager( 2419): Killing 6685:com.sec.android.service.cm/u0a82 (adj 15): empty for 1827s
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 67
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 69
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 70
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4076): GC_CONCURRENT freed 2045K, 28% free 9725K/13380K, paused 2ms+3ms, total 31ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 2030s ago
,E/Watchdog( 2419): !@Sync 71
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(13093): 
D/AndroidRuntime(13093): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13093): CheckJNI is OFF
D/AndroidRuntime(13093): setted country_code = Poland
D/AndroidRuntime(13093): setted countryiso_code = PL
D/AndroidRuntime(13093): setted sales_code = PLS
D/AndroidRuntime(13093): readGMSProperty: start
D/AndroidRuntime(13093): readGMSProperty: already setted!!
D/AndroidRuntime(13093): readGMSProperty: end
D/AndroidRuntime(13093): addProductProperty: start
D/dalvikvm(13093): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13093): Added shared lib libjavacore.so 0x0
D/dalvikvm(13093): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13093): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13093): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13093): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13093): failed to load memtrack module: -2
D/dalvikvm(13093): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13093): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2419): START PACKAGE DELETE: observer{1119131688}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2419): !@killApplicatoin: 10598, uninstall pkg
I/ActivityManager( 2419): Killing 7557:com.test.thalitest/u0a598 (adj 0): stop com.test.thalitest
I/ActivityManager( 2419): Killing 7826:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1800s
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1921): id=20 Removed EimLayer (5/10)
I/SurfaceFlinger( 1921): id=20 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1921): id=19 Removed EimLayer (4/9)
I/SurfaceFlinger( 1921): id=19 Removed EimLayer (-2/9)
V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
W/InputDispatcher( 2419): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2419): channel ~ Channel is unrecoverably broken and will be disposed!
E/bt-btif ( 4000): bta_jv_rfcomm_stop_server
W/InputDispatcher( 2419): Attempted to unregister already unregistered input channel
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (6/8)
D/Launcher( 2762): onRestart, Launcher: 1113604048
D/Launcher( 2762): onStart, Launcher: 1113604048
D/Launcher.HomeView( 2762): onStart
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/8)
I/WindowState( 2419): WIN DEATH: Window{430f3108 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/8)
I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
W/PackageSettings( 2419): Skipping PackageSetting{42595538 com.example.hello/10594} due to missing metadata
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:2762,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:2762,o:f
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7557 uid 10598
D/PackageManager( 2419): checkUidPermission - Execution time: 154 ms
D/PackageManager( 2419): checkUidPermission - Execution time: 111 ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10598, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
D/dalvikvm( 6423): GC_EXPLICIT freed 562K, 27% free 9984K/13512K, paused 6ms+6ms, total 73ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10598, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2947): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5112): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
I/SELinux (13124): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13124):  
D/dalvikvm( 3445): GC_EXPLICIT freed 1787K, 19% free 12589K/15404K, paused 19ms+42ms, total 190ms
D/dalvikvm( 2984): GC_EXPLICIT freed 1474K, 26% free 10037K/13488K, paused 32ms+8ms, total 175ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13124): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13124):  
I/SELinux (13124):  
I/SELinux (13124): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13124): >>>>> Normal User
E/dalvikvm(13124): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13124): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
D/TimaKeyStoreProvider(13124): in addTimaSignatureService
D/TimaKeyStoreProvider(13124): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13124): Added TimaKesytore provider
D/RegisteredServicesCache( 2757): empty dynamic service
D/dalvikvm( 2419): GC_EXPLICIT freed 3187K, 56% free 24945K/56044K, paused 19ms+29ms, total 340ms
D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 259ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2419): PackageReceiver onReceive()
I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13124): GC_CONCURRENT freed 3009K, 30% free 9559K/13492K, paused 3ms+2ms, total 37ms
D/dalvikvm(13124): WAIT_FOR_CONCURRENT_GC blocked 32ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13124): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13124): ELMEngine.ELMEngine( context ).
D/elm:14132(13124): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2419): Killing 2821:com.android.settings/1000 (adj 15): empty for 1800s
D/elm:14132(13124): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13124): ElmAgentService : onCreate()
D/elm:14132(13124): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13124): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13124): MDMBridge.getInstance()
D/elm:14132(13124): MDMBridge.getAllLicenseInfoFromSDK()
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(13124): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13139): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13139):  
I/ActivityManager( 2419): Killing 5717:com.sec.android.diagmonagent/1000 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 5703:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 6612:com.sec.pcw.device/1000 (adj 15): empty for 1800s
D/dalvikvm( 2757): GC_CONCURRENT freed 1210K, 27% free 10615K/14388K, paused 14ms+3ms, total 127ms
D/dalvikvm( 2757): WAIT_FOR_CONCURRENT_GC blocked 75ms
I/SELinux (13139): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13139):  
I/SELinux (13139):  
I/SELinux (13139): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13139): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13139): >>>>> Normal User
E/dalvikvm(13139): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13139): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
D/elm:14132(13124): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/TimaKeyStoreProvider(13139): in addTimaSignatureService
D/TimaKeyStoreProvider(13139): Cannot add TimaSignature Service, License check Failed
D/elm:14132(13124): ElmAgentService : onDestroy().
D/ActivityThread(13139): Added TimaKesytore provider
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10598 #1
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13139): GC_CONCURRENT freed 3007K, 30% free 9569K/13496K, paused 4ms+2ms, total 42ms
D/dalvikvm(13139): WAIT_FOR_CONCURRENT_GC blocked 35ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm( 2419): GC_EXPLICIT freed 1298K, 56% free 25014K/56044K, paused 12ms+34ms, total 517ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13154): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13154):  
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2419): Killing 6642:com.policydm/1000 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7710:com.sec.android.soagent/u0a38 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7603:com.vlingo.midas/u0a34 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7684:com.samsung.klmsagent/u0a18 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7665:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 5778:com.osp.app.signin/u0a44 (adj 15): empty for 1800s
I/SELinux (13154): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13154):  
I/SELinux (13154):  
I/SELinux (13154): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13154): >>>>> Normal User
E/dalvikvm(13154): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13154): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13154): in addTimaSignatureService
D/TimaKeyStoreProvider(13154): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13154): Added TimaKesytore provider
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2419): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2419): clearDefaults: com.test.thalitest
D/dalvikvm(13154): GC_CONCURRENT freed 3003K, 30% free 9558K/13488K, paused 2ms+1ms, total 25ms
D/dalvikvm(13154): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/PackageManager( 2419): delete sourFile : 
D/PackageManager( 2419): delete native library directory: 
D/PackageManager( 2419): return delete result to caller: 1119131688
D/AndroidRuntime(13093): Shutting down VM
D/PackageManager( 2419): returnCode: 1
D/dalvikvm(13093): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/SELinux (13168): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13168):  
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/ActivityManager( 2419): Killing 7866:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7755:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1800s
I/ActivityManager( 2419): Killing 7741:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1800s
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13168): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13168):  
I/SELinux (13168):  
I/SELinux (13168): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13168): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13168): >>>>> Normal User
E/dalvikvm(13168): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13168): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
W/ApplicationsProvider( 2984): Could not fetch usage stats
W/ApplicationsProvider( 2984): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2984): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2984): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2984): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2984): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2984): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2984): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2984): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2984): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2984): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2984): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2984): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/TimaKeyStoreProvider(13168): in addTimaSignatureService
D/TimaKeyStoreProvider(13168): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13168): Added TimaKesytore provider
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(13168): GC_CONCURRENT freed 3003K, 30% free 9569K/13496K, paused 3ms+2ms, total 32ms
D/dalvikvm(13168): WAIT_FOR_CONCURRENT_GC blocked 28ms
I/SELinux (13181): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13181):  
I/SELinux (13181): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13181):  
I/SELinux (13181):  
I/SELinux (13181): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13181): >>>>> Normal User
E/dalvikvm(13181): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13181): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(13181): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13181): in addTimaSignatureService
D/TimaKeyStoreProvider(13181): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13181): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 7768:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1800s
D/dalvikvm(13181): GC_CONCURRENT freed 3006K, 30% free 9568K/13496K, paused 3ms+2ms, total 27ms
D/dalvikvm(13181): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(13181): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13181): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13181): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13181): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13181): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13181): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13181): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13181): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13181): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13181): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13181): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13181): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13181): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13181): Shutting down VM
W/dalvikvm(13181): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13181): FATAL EXCEPTION: main
E/AndroidRuntime(13181): Process: com.sec.pcw.device, PID: 13181
E/AndroidRuntime(13181): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13181): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13181): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13181): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13181): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13181): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13181): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13181): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13181): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13181): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13181): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13181): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13181): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13181): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13181): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13181): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13181): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13181): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13181): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13181): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13181): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13181): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13181): 	... 12 more
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (13197): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13197):  
I/Process (13181): Sending signal. PID: 13181 SIG: 9
I/ActivityManager( 2419): Process com.sec.pcw.device (pid 13181) (adj 0) has died.
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9503K/10472K, paused 4ms+4ms, total 42ms
I/SELinux (13197): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13197):  
I/SELinux (13197):  
I/SELinux (13197): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13197): >>>>> Normal User
E/dalvikvm(13197): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13197): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 3ms+4ms, total 36ms
D/TimaKeyStoreProvider(13197): in addTimaSignatureService
D/TimaKeyStoreProvider(13197): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13197): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10472K, paused 3ms+4ms, total 34ms
D/dalvikvm(13197): GC_CONCURRENT freed 3015K, 30% free 9559K/13496K, paused 3ms+2ms, total 26ms
D/dalvikvm(13197): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/System.err(13197): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13197): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13197): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13197): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13197): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13197): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13197): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13197): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13197): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13197): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13197): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13197): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13197): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13197): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13197): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13197): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13197): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13197): 	at libcore.io.Posix.open(Native Method)
W/System.err(13197): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13197): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13197): 	... 21 more
D/GalaxyFinderApplication(13197): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13197): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13211): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13211):  
I/ActivityManager( 2419): Killing 5910:com.google.android.apps.plus/u0a133 (adj 15): empty for 1800s
I/SELinux (13211): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13211):  
I/SELinux (13211):  
I/SELinux (13211): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13211): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13211): >>>>> Normal User
E/dalvikvm(13211): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13211): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13211): in addTimaSignatureService
D/TimaKeyStoreProvider(13211): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13211): Added TimaKesytore provider
D/dalvikvm(13211): GC_CONCURRENT freed 2990K, 30% free 9579K/13496K, paused 2ms+1ms, total 23ms
D/dalvikvm(13211): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(13211): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13211): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13211): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13211): ContentProvider is not null
W/ResourceType(13211): No package identifier when getting value for resource number 0x00000000
I/System.out(13211): resource Id::2131361807
E/SQLiteDatabase(13211): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13211): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13211): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13211): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13211): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13211): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13211): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13211): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13211): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13211): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13211): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13211): Shutting down VM
W/dalvikvm(13211): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13211): FATAL EXCEPTION: main
E/AndroidRuntime(13211): Process: com.sec.android.app.shealth, PID: 13211
E/AndroidRuntime(13211): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(13211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13211): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13211): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13211): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13211): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13211): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13211): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13211): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13211): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(13211): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(13211): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(13211): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(13211): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(13211): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(13211): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(13211): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(13211): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(13211): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(13211): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHeal
```
