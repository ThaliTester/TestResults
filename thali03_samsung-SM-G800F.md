#### Test 54970261fc259e9_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
--------- beginning of /dev/log/main
D/AndroidRuntime( 7616): 
D/AndroidRuntime( 7616): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7616): CheckJNI is OFF
D/AndroidRuntime( 7616): setted country_code = Poland
D/AndroidRuntime( 7616): setted countryiso_code = PL
D/AndroidRuntime( 7616): setted sales_code = PLS
D/AndroidRuntime( 7616): readGMSProperty: start
D/AndroidRuntime( 7616): readGMSProperty: already setted!!
D/AndroidRuntime( 7616): readGMSProperty: end
D/AndroidRuntime( 7616): addProductProperty: start
D/dalvikvm( 7616): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7616): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7616): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7616): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7616): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7616): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7616): failed to load memtrack module: -2
D/dalvikvm( 7616): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7616): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1919): id=21 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1919): id=22 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7646): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7646):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7616): Shutting down VM
D/dalvikvm( 7616): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7646): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7646):  
I/SELinux ( 7646):  
I/SELinux ( 7646): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7646): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7646): >>>>> Normal User
E/dalvikvm( 7646): >>>>> com.test.thalitest [ userId:0 | appId:10586 ]
E/SELinux ( 7646): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7646): in addTimaSignatureService
D/TimaKeyStoreProvider( 7646): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7646): Added TimaKesytore provider
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4179): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4179): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1919): id=19 Removed Mauncher (8/10)
I/SurfaceFlinger( 1919): id=19 Removed Mauncher (-2/10)
D/Launcher( 2773): onTrimMemory. Level: 20
D/dalvikvm( 7646): GC_CONCURRENT freed 3014K, 31% free 9558K/13712K, paused 2ms+2ms, total 18ms
D/dalvikvm( 7646): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7646): Binding Chromium to the background looper Looper (main, tid 1) {4226a380}
I/chromium( 7646): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7646): Initializing chromium process, renderers=0
W/chromium( 7646): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7646): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7646): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7646): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7646): Mali API Version : 401
,I/Mali    ( 7646): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7646): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7646): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7646): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7646): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7646): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7646): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2419): tr p:7646,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/dalvikvm( 7646): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7646): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7646): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7646): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7646): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7646): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7646): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7646): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7646): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7646): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7646): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7646): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7646): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:7646,o:f
,I/SurfaceFlinger( 1919): id=23 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7646): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7646): Enabling debug mode 0
,W/AwContents( 7646): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7646): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7646): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7646): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7646): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42263180
,D/dalvikvm( 7646): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42263180
D/jxcore_app_log( 7646): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027677768
,D/JX-Cordova( 7646): jxcore cordova android initializing
,D/dalvikvm( 7646): GC_CONCURRENT freed 1266K, 18% free 11364K/13768K, paused 2ms+2ms, total 23ms
D/dalvikvm( 7646): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 7646): GC_CONCURRENT freed 1953K, 18% free 14999K/18112K, paused 2ms+2ms, total 41ms
D/dalvikvm( 7646): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
D/dalvikvm( 7646): GC_FOR_ALLOC freed 5292K, 30% free 16275K/22972K, paused 51ms, total 51ms
,D/dalvikvm( 7646): GC_CONCURRENT freed 6708K, 31% free 17734K/25604K, paused 3ms+11ms, total 70ms
,D/dalvikvm( 7646): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/dalvikvm( 7646): GC_FOR_ALLOC freed 1102K, 32% free 17658K/25604K, paused 38ms, total 39ms
,I/dalvikvm-heap( 7646): Grow heap (frag case) to 21.871MB for 3688532-byte allocation
,D/dalvikvm( 7646): GC_FOR_ALLOC freed 2402K, 36% free 18857K/29208K, paused 44ms, total 44ms
,W/jxcore-log( 7646): Initializing JXcore engine
,W/jxcore-log( 7646): JXcore engine is ready
,W/jxcore-log( 7646): Starting JXcore engine
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/jxcore-log( 7646): Platform android
W/jxcore-log( 7646): 
,W/jxcore-log( 7646): Process ARCH arm
W/jxcore-log( 7646): 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7646): JXcore Cordova bridge is ready!
I/jxcore-log( 7646): 
,W/jxcore-log( 7646): JXcore engine is started
,I/chromium( 7646): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7646): Toggling radios to true
I/jxcore-log( 7646): 
,D/BluetoothAdapter( 7646): enable(): BT is already enabled..!
,I/WifiManager( 7646): packageName : com.test.thalitest
,I/WifiManager( 7646): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7646, uid=10586
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7646, uid=10586 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7646, uid=10586 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7646, uid=10586
,I/wpa_supplicant( 3967): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7646): Radios toggled
I/jxcore-log( 7646): 
,I/wpa_supplicant( 3967): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3967): First Scan Start
,I/wpa_supplicant( 3967): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): Skip scan - already scanning
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2419): Attempting to switch to mobile
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7691):  
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1914): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-78ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-77ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1914): RTNETLINK answers: No such process
V/RouteController( 1914): /system/bin/ip -6 rule del table 2 2>&1
I/SELinux ( 7691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7691):  
I/SELinux ( 7691):  
,I/SELinux ( 7691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7691): >>>>> Normal User
,E/dalvikvm( 7691): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,W/NetworkManagementService( 2419): route cmd failed: 
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,D/TimaKeyStoreProvider( 7691): in addTimaSignatureService
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7691): Added TimaKesytore provider
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x77b2abe0 clazz=0x62500001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,V/NativeCrypto( 2847): Read error: ssl=0x74632598: I/O error during system call, Connection timed out
,D/dalvikvm( 7691): GC_CONCURRENT freed 2994K, 31% free 9572K/13704K, paused 26ms+2ms, total 87ms
,D/dalvikvm( 7691): WAIT_FOR_CONCURRENT_GC blocked 18ms
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x74632598: I/O error during system call, Broken pipe
,E/SPPClientService( 5562): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5562): [e] exceptionCaught(). NET_TIMEOUT
,D/dalvikvm( 2419): GC_CONCURRENT freed 4309K, 58% free 25366K/59752K, paused 15ms+17ms, total 354ms
,E/SPPClientService( 5562): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5562): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5562): [b] ResponseMap empty
,D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): updateIfacesLocked()
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 25ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/System.out( 7691): Inside WakeupProvider
,I/System.out( 7691): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7691): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7691): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7691): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2816): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2816): MountReceiver.onReceive - Set preference state off
I/ActivityManager( 2419): Killing 6320:com.sec.phone/1001 (adj 15): empty #43
,V/NearbySettings( 2816): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7691): initQueue()
,D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2816): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2816): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2816): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7719): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7719):  
,I/SELinux ( 7719): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7719):  
I/SELinux ( 7719):  
,I/SELinux ( 7719): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7719): >>>>> Normal User
,E/dalvikvm( 7719): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7719): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7719): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7719): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7719): Added TimaKesytore provider
,D/dalvikvm( 7719): GC_CONCURRENT freed 2990K, 31% free 9576K/13708K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7719): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/dalvikvm( 7719): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
,W/dalvikvm( 7719): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7719): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7719): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0000
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4767): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,E/dalvikvm( 7719): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7719): Link of class 'Ldqp;' failed
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7719): Link of class 'Ldqp;' failed
I/dalvikvm( 7719): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0000
,I/wpa_supplicant( 3967): nl80211: Received scan results (6 BSSes)
I/wpa_supplicant( 3967): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,E/dalvikvm( 7719): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7719): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0000
,W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7719): Link of class 'Ldqp;' failed
W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7719): Link of class 'Ldqp;' failed
I/dalvikvm( 7719): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7719): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7719): Link of class 'Ldqp;' failed
W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7719): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7719): Link of class 'Ldqp;' failed
I/dalvikvm( 7719): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7719): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7719): Link of class 'Lax;' failed
E/dalvikvm( 7719): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0006
,W/dalvikvm( 7719): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7719): Link of class 'Laz;' failed
E/dalvikvm( 7719): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7719): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7719): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7719): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0006
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/dalvikvm( 7719): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
,W/dalvikvm( 7719): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7719): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7719): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7719): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7719): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7719): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7719): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7719): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7719): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x23 at 0x0005
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/dalvikvm( 7719): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7719): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0009
I/wpa_supplicant( 3967): Associated with C0.AA.48
I/wpa_supplicant( 3967): freq(2412) increment count 2
I/wpa_supplicant( 3967): meet head of list.
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/WifiNative( 2419): callSECApiVoid - ID [50]
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,W/dalvikvm( 7719): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7719): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7719): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7719): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7719): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7719): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7719): VFY: replacing opcode 0x1f at 0x000c
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7719): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7719): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7719): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
,W/dalvikvm( 7719): Unable to resolve superclass of Lax; (841)
,W/dalvikvm( 7719): Link of class 'Lax;' failed
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
,W/dalvikvm( 7719): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7719): Link of class 'Laz;' failed
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7719): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422647c0
,D/dalvikvm( 7719): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x422647c0
,I/dalvikvm( 7719): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7719): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7719): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7719): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7719): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7719): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7719): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7719): MmsConfig.loadFromResources
,E/Babel_SMS( 7719): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7719): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7719): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7719): Link of class 'Lfzc;' failed
,E/dalvikvm( 7719): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7719): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,I/dalvikvm( 7719): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
,W/dalvikvm( 7719): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7719): VFY: replacing opcode 0x74 at 0x006d
,I/dalvikvm( 7719): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
,W/dalvikvm( 7719): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0033
,I/dalvikvm( 7719): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
,W/dalvikvm( 7719): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0030
,W/dalvikvm( 7719): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7719): Link of class 'Lfzc;' failed
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
,E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,E/SensorService( 2419): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1923): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1923): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1923): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1923): DEBUG:duration time(    1 msec):(HAL_getCameraInfo)
,I/dhcpcd  ( 7741): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7741): bssid match
,D/dalvikvm( 7719): GC_CONCURRENT freed 1763K, 22% free 10846K/13748K, paused 4ms+4ms, total 34ms
,W/Settings( 7719): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
I/Babel_Crash( 7719): startup - clean
,I/Babel   ( 7719): deleted: false for 0
,I/dalvikvm( 7719): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7719): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7719): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x004e
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7719): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7719): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7719): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,E/dalvikvm( 7719): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7719): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7719): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7719): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7719): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
,I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): noConnectivity : true
,I/dalvikvm( 7719): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7719): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7719): VFY: replacing opcode 0x6e at 0x0074
,I/vclib   ( 7719): onServiceConnected
,I/ActivityManager( 2419): Killing 5767:com.sec.android.diagmonagent/1000 (adj 15): empty #43
W/Babel   ( 7719): Attempted to change video mute state without an active call.
,I/SELinux ( 7751): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7751):  
,I/SELinux ( 7751): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7751):  
I/SELinux ( 7751):  
,I/SELinux ( 7751): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7751): >>>>> Normal User
,E/dalvikvm( 7751): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7751): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7751): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7751): Added TimaKesytore provider
,D/dalvikvm( 7719): GC_CONCURRENT freed 992K, 16% free 11890K/14032K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7719): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7751): GC_CONCURRENT freed 3002K, 31% free 9567K/13708K, paused 2ms+3ms, total 21ms
,D/dalvikvm( 7751): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 7719): GC_FOR_ALLOC freed 496K, 17% free 12395K/14800K, paused 24ms, total 24ms
,D/dalvikvm( 7719): GC_FOR_ALLOC freed 1759K, 23% free 12766K/16384K, paused 22ms, total 23ms
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/ActivityManager( 2419): Killing 6390:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7764): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7764):  
,I/SELinux ( 7764): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7764):  
I/SELinux ( 7764):  
,I/SELinux ( 7764): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7764): >>>>> Normal User
,E/dalvikvm( 7764): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7764): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7764): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7764): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7764): Added TimaKesytore provider
,D/dalvikvm( 7764): GC_CONCURRENT freed 3005K, 31% free 9565K/13712K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7764): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/KLMS-2.3.201 : ( 7764): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7764): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452011403504
,I/KLMS-2.3.201 : ( 7764): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6005:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7776): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7776):  
,I/SELinux ( 7776): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7776):  
I/SELinux ( 7776):  
,I/SELinux ( 7776): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7776): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7776): >>>>> Normal User
,E/dalvikvm( 7776): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7776): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7776): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7776): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7776): Added TimaKesytore provider
,D/dalvikvm( 7776): GC_CONCURRENT freed 3002K, 31% free 9572K/13712K, paused 4ms+1ms, total 24ms
,D/dalvikvm( 7776): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/SO_AGENT( 7776): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7776): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5827): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5827): [BDLM] already registered in spp
,I/SA      ( 5827): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5827): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5827): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5827): [OR] == isSIMCardReady false ==
I/SA      ( 5827): [SCU] == networkStateCheck == false
,I/SA      ( 5827): [OR] onReceive END
I/ActivityManager( 2419): Killing 6179:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6612): Other Intent
,I/SELinux ( 7788): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7788):  
,I/SELinux ( 7788): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7788):  
I/SELinux ( 7788):  
,I/SELinux ( 7788): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7788): >>>>> Normal User
,E/dalvikvm( 7788): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7788): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7788): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7788): Added TimaKesytore provider
,D/dalvikvm( 7788): GC_CONCURRENT freed 2988K, 31% free 9580K/13712K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7788): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7788): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5358): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7788): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5358): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7788): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5358): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6216:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/Headlines( 5894): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5894): getCountryCode(): countryCode = PL
,D/Headlines( 5894): Breath.onCreate
,D/Headlines( 5894): Breath timer started. interval : 30000
,I/SELinux ( 7803): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7803):  
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5894): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5894): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5894): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7803):  
I/SELinux ( 7803):  
I/SELinux ( 7803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7803): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7803): >>>>> Normal User
,E/dalvikvm( 7803): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7803): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7803): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7803): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7803): Added TimaKesytore provider
,D/dalvikvm( 7803): GC_CONCURRENT freed 2992K, 31% free 9571K/13704K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7803): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/WebViewChromium( 7803): Binding Chromium to the background looper Looper (main, tid 1) {42270e10}
,I/chromium( 7803): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7803): Initializing chromium process, renderers=0
,W/chromium( 7803): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7803): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7803): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7803): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7803): Mali API Version : 401
,I/Mali    ( 7803): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2419): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1914): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 7803): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 7803): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
V/RouteController( 1914): RTNETLINK answers: No such file or directory
V/RouteController( 1914): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1914): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 16ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/NSApplication( 7803): Starting up...
,I/iu.Environment( 5959): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5160): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a5828
,I/SELinux ( 7874): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7874):  
,I/SELinux ( 7874): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7874):  
I/SELinux ( 7874):  
,I/SELinux ( 7874): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7874): >>>>> Normal User
,E/dalvikvm( 7874): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7874): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7874): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7874): Added TimaKesytore provider
,D/dalvikvm( 7874): GC_CONCURRENT freed 2996K, 31% free 9574K/13708K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7874): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4767): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7893): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7893):  
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/ActivityManager( 2419): Killing 6549:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 7893): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7893):  
I/SELinux ( 7893):  
,I/SELinux ( 7893): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7893): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7893): >>>>> Normal User
,E/dalvikvm( 7893): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7893): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7903): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7903):  
,D/TimaKeyStoreProvider( 7893): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7893): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7893): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6339:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/SELinux ( 7903): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7903):  
I/SELinux ( 7903):  
D/dalvikvm( 1920): GC_EXPLICIT freed 42K, 12% free 9502K/10688K, paused 3ms+3ms, total 35ms
I/SELinux ( 7903): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 1920): WAIT_FOR_CONCURRENT_GC blocked 1ms
E/SELinux ( 7903): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7903): >>>>> Normal User
E/dalvikvm( 7903): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7903): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 12% free 9502K/10688K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7903): in addTimaSignatureService
D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 20
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 12% free 9502K/10688K, paused 2ms+3ms, total 26ms
D/dalvikvm( 7893): GC_CONCURRENT freed 3000K, 31% free 9565K/13708K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 7893): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/TimaKeyStoreProvider( 7903): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7903): Added TimaKesytore provider
,D/BadgeProvider( 7893): onCreate
,D/BadgeProvider( 7893): DatabaseHelper
,D/BadgeProvider( 7893): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2773): reloadBadges entered.
D/BadgeProvider( 7893): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7893): sendNotify, [notify] : null
D/BadgeProvider( 7893): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7893): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7893): update, [UpdateCount] : 1
,D/dalvikvm( 7903): GC_CONCURRENT freed 2997K, 31% free 9572K/13708K, paused 3ms+2ms, total 36ms
,D/dalvikvm( 7903): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/hcjo    ( 5983): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5983): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5983): exit::IDLE
,D/InitializeManagerStateMachine( 5983): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5983): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5983): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5983): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5983): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5983): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5983): entry::SUCCESS
,D/hcjo    ( 5983): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5983): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5983): exit::SUCCESS
,D/InitializeManagerStateMachine( 5983): entry::IDLE
,E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 347349
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5562): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2816): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2816): MountReceiver.onReceive - Keep current state
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2816): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2816): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2816): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2816): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2816): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5562): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/System.out( 7719): Thread-659(HTTPLog):isShipBuild true
,I/System.out( 7719): Thread-659(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,E/SPPClientService( 5562): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1919): id=24 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/NearbySettings( 2816): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2816): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SELinux ( 7925): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7925):  
,I/Babel   ( 7719): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5562): [g] getNetMCC return empty string
,I/SELinux ( 7925): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7925):  
I/SELinux ( 7925):  
,I/SELinux ( 7925): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7925): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7925): >>>>> Normal User
,E/dalvikvm( 7925): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
,E/SELinux ( 7925): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7925): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7925): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7925): Added TimaKesytore provider
,D/dalvikvm( 7925): GC_CONCURRENT freed 2996K, 31% free 9567K/13708K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7925): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/DBG_DIAGMONDM( 7925): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,I/DBG_DIAGMONDM( 7925): [1.140541.0531][Line:48][onCreate] myUserId : 0
,I/DBG_DIAGMONDM( 7925): [1.140541.0531][Line:376][xdbDMffs_Init] 
,I/DBG_DIAGMONDM( 7925): [1.140541.0531][Line:70][onCreate] nStatus : 0
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7764): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7764): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452011406438
,I/KLMS-2.3.201 : ( 7764): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 7751): Total arena pages for JIT: 11
,I/dalvikvm( 7751): Total arena pages for JIT: 12
I/dalvikvm( 7751): Total arena pages for JIT: 13
,I/dalvikvm( 7751): Total arena pages for JIT: 14
,I/dalvikvm( 7751): Total arena pages for JIT: 15
I/dalvikvm( 7751): Total arena pages for JIT: 16
,I/dalvikvm( 7751): Total arena pages for JIT: 17
,D/SO_AGENT( 7776): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7776): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7944): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7944):  
,I/SELinux ( 7944): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7944):  
I/SELinux ( 7944):  
I/SELinux ( 7944): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7944): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7944): >>>>> Normal User
E/dalvikvm( 7944): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7944): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7944): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7944): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7944): Added TimaKesytore provider
,I/SELinux ( 7956): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7956):  
,I/SELinux ( 7956): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7956):  
I/SELinux ( 7956):  
,I/SELinux ( 7956): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7956): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7956): >>>>> Normal User
,E/dalvikvm( 7956): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7956): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5827): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5827): [BDLM] already registered in spp
I/SA      ( 5827): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5827): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5827): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5827): [OR] == isSIMCardReady false ==
,I/SA      ( 5827): [SCU] == networkStateCheck == true
I/SA      ( 5827): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5827): isChinaCountryCode : false
,I/SA      ( 5827): [OR] == networkStateCheck true ==
,D/TimaKeyStoreProvider( 7956): in addTimaSignatureService
,I/SA      ( 5827): [OR] GetMyCountryZoneTask
,D/TimaKeyStoreProvider( 7956): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7956): Added TimaKesytore provider
,I/SA      ( 5827): [OR] onReceive END
,I/SA      ( 5827): [SRS] prepareGetMyCountryZone
,I/System.out( 7751): Thread-651(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 5827): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5827): [SSP] query invoked
,E/Watchdog( 2419): !@Sync 11
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
D/dalvikvm( 7944): GC_CONCURRENT freed 2994K, 31% free 9573K/13712K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 7944): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/SCloudBackupReceiver( 6612): Other Intent
,I/SA      ( 5827): [TPMU] GetMccFromDB : null
I/SA      ( 5827): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5827): [TPM] isNoProxy(default) : true
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7788): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5827): [RC New] Execute method=[GET] start
I/System.out( 7751): Thread-651(ApacheHTTPLog):isShipBuild true
,I/System.out( 7751): Thread-651(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Headlines( 5894): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5894): getCountryCode(): countryCode = PL
,D/dalvikvm( 7956): GC_CONCURRENT freed 3004K, 31% free 9566K/13708K, paused 3ms+1ms, total 40ms
,D/dalvikvm( 7956): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5894): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5894): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5894): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5894): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 5562): GC_CONCURRENT freed 1938K, 24% free 10508K/13688K, paused 6ms+6ms, total 52ms
,I/System.out( 7751): AsyncTask #1 calls detatch()
,W/System.err( 7751): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7751): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7751): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7751): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7751): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7751): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7751): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7751): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7751): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7751): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7751): Caused by: java.lang.NullPointerException
,W/System.err( 7751): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7751): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7751): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7751): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7751): 	... 8 more
,D/dalvikvm( 2419): GC_EXPLICIT freed 2014K, 58% free 25426K/59752K, paused 17ms+18ms, total 223ms
,V/KVNProvider( 7956): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7956): getFindoCursor query string : 
,I/iu.Environment( 5959): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
I/ActivityManager( 2419): Killing 6563:com.android.chrome/u0a85 (adj 15): empty #43
,I/ActivityManager( 2419): Killing 6580:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5160): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422a5828
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/dalvikvm( 2721): GC_EXPLICIT freed 360K, 28% free 9970K/13696K, paused 7ms+6ms, total 52ms
,V/KVNProvider( 7956): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5983): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5983): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5983): exit::IDLE
,D/InitializeManagerStateMachine( 5983): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5983): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5983): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5983): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5983): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5983): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5983): entry::SUCCESS
,D/hcjo    ( 5983): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5983): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5983): exit::SUCCESS
,D/InitializeManagerStateMachine( 5983): entry::IDLE
,E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 348977
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : false
I/ActivityManager( 2419): Killing 6245:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5827): [RC New] [v2liruge] api execute + 679
,I/SA      ( 5827): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5827): AsyncTask #2 calls detatch()
,I/SA      ( 5827): [TPMU] getNetworkMcc : 
,I/SA      ( 5827): [SCU] saveMccToPreferece Start
I/SA      ( 5827): [SCU] RegionMCC : 260
,I/SA      ( 5827): [SSP] query invoked
,I/SA      ( 5827): [TPMU] GetMccFromDB : null
I/SA      ( 5827): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5827): [SCU] saveMccToPreferece End
,I/SA      ( 5827): [RC New] executeRequest [v2liruge] end. 698
I/SA      ( 5827): [RC New] Execute end
I/SA      ( 5827): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5827): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5562): [b] __InitReply__
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/SurfaceFlinger( 1919): id=24 Removed Uoast (10/11)
I/ActivityManager( 2419): Killing 6488:com.google.android.partnersetup/u0a14 (adj 15): empty #43
D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 351031
D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3476)
,I/GAV2    ( 7803): Thread[GAThread,5,main]: No campaign data found.
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6665): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6665): [ensureRegistration] - No Samsung account
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7980): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7980):  
,I/SELinux ( 7980): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7980):  
I/SELinux ( 7980):  
,I/SELinux ( 7980): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7980): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7980): >>>>> Normal User
,E/dalvikvm( 7980): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7980): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7980): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7980): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7980): Added TimaKesytore provider
,D/dalvikvm( 7980): GC_CONCURRENT freed 3002K, 31% free 9565K/13708K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7980): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 7214 latestRequest time : 1452011406835 current time : 1452011414049
,I/ActivityManager( 2419): Killing 6639:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/jxcore-log( 7646): Test app app.js loaded
I/jxcore-log( 7646): 
,I/Choreographer( 7646): Skipped 827 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7646): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 340, Delta = 10
,D/PreloadUpdateManagerStateMachine( 5983): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5983): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5983): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5983): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5983): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5983): entry::IDLE
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5983): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5983): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5983): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5983): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5983): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5983): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5983): entry::IDLE
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{451d3b20 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43e9f508 u0 com.sec.spp.push/.PushClientService}
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -20
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 225s ago
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 27290 latestRequest time : 1452011406835 current time : 1452011434125
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 12
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 57287 latestRequest time : 1452011406835 current time : 1452011464122
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 13
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 275s ago
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 87287 latestRequest time : 1452011406835 current time : 1452011494124
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 14
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 117284 latestRequest time : 1452011406835 current time : 1452011524119
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 15
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5894): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5894): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5894): Breath 147281 latestRequest time : 1452011406835 current time : 1452011554116
,D/Headlines( 5894): stop 
,D/Headlines( 5894): Breath.onDestroy : 
,I/ActivityManager( 2419): Killing 6651:com.android.musicfx/u0a24 (adj 15): empty #43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 16
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 17
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 18
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 19
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 21
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,I/GAV2    ( 5653): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5653): Thread[disconnect check,5,main]: Disconnected from service
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 22
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/dalvikvm( 4085): GC_CONCURRENT freed 2889K, 30% free 9725K/13752K, paused 29ms+3ms, total 124ms
,D/dalvikvm( 2419): GC_CONCURRENT freed 4025K, 58% free 25335K/59752K, paused 10ms+18ms, total 222ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 23
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 24
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 25
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 26
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
,D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3161): Aggregate from 1452010044274 (log), 1452010044274 (data)
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3161): GC_CONCURRENT freed 1722K, 19% free 12694K/15556K, paused 6ms+11ms, total 100ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 27
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 28
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 29
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2419): !@Sync 31
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 32
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=63)
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 33
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 34
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 35
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 36
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,E/SPPClientService( 5562): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 37
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3846K, 58% free 25347K/59752K, paused 16ms+17ms, total 228ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 38
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 39
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,E/Watchdog( 2419): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,I/PowerManagerService( 2419): [PWL]   PowerManagerService.WakeLocks: ref count=1
,I/PowerManagerService( 2419): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2419): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=78)
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4085): GC_CONCURRENT freed 2048K, 30% free 9722K/13752K, paused 4ms+11ms, total 77ms
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 11979
,E/Watchdog( 2419): !@Sync 50
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/dalvikvm( 2419): GC_CONCURRENT freed 3968K, 58% free 25241K/59752K, paused 20ms+14ms, total 261ms
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 12544
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 70ms
,I/ProcessStatsService( 2419): Prepared write state in 31ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2016-01-05-01-38-48.bin
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
I/ActivityManager( 2419): Killing 6919:com.google.android.youtube/u0a175 (adj 15): empty for 1810s
,I/ActivityManager( 2419): Killing 5610:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 6482:com.sec.knox.bridge/1000 (adj 15): empty for 1824s
,I/ActivityManager( 2419): Killing 4885:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1824s
,I/ActivityManager( 2419): Killing 5717:com.android.mms/u0a49 (adj 15): empty for 1832s
,I/ActivityManager( 2419): Killing 6445:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6829:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6813:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6801:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6789:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6776:com.samsung.helphub/1000 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6763:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1836s
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 6751:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6735:com.sec.android.service.cm/u0a82 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6403:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6710:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1837s
,I/ActivityManager( 2419): Killing 6023:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1837s
,I/ActivityManager( 2419): Killing 6680:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1838s
,D/CountryDetector( 2419): No listener is left
,D/dalvikvm( 2773): GC_CONCURRENT freed 9159K, 41% free 18059K/30116K, paused 7ms+7ms, total 90ms
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3885K, 58% free 25199K/59752K, paused 21ms+17ms, total 263ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x3)
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 55ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (13396): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13396):  
,I/SELinux (13396): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13396):  
I/SELinux (13396):  
,I/SELinux (13396): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13396): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13396): >>>>> Normal User
,E/dalvikvm(13396): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13396): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13396): in addTimaSignatureService
,D/TimaKeyStoreProvider(13396): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13396): Added TimaKesytore provider
,D/dalvikvm(13396): GC_CONCURRENT freed 3006K, 31% free 9558K/13708K, paused 3ms+2ms, total 28ms
,D/dalvikvm(13396): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(13396): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13396): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13396): Widget random data : 0
,D/@ WidgetProvider(13396): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13396): Widget random data : 10
,E/dalvikvm(13396): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13396): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13396): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(13396): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13396): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13396): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(13396): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13396): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13396): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13396): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13396): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13396): VFY: replacing opcode 0x22 at 0x0038
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
,D/dalvikvm(13396): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/dalvikvm(13396): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/dalvikvm(13396): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(13396): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2847): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(13396): Thread-687(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13396): Thread-687(ApacheHTTPLog):isShipBuild true
,I/System.out(13396): Thread-687(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(13396): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13396): AsyncNetworking-1-thread-1 calls detatch()
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,V/ImageManager(13396): Max ALLOWED memory (MB): 128
V/ImageManager(13396): Max SHOULD USE memory (MB): 128
,V/ImageManager(13396): Max Image Cache memory (MB): 32
,D/skia    (13396): getTotalSize : Do not get file length
,D/@ WidgetProvider(13396): Building widget : 5
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 67
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 69
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13694
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13696
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13697
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13699
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13701
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13702
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13704
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13706
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13707
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 13708
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2578): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4085): GC_CONCURRENT freed 2042K, 30% free 9725K/13744K, paused 15ms+2ms, total 42ms
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
,V/HeadsetService( 4003): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4003): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 71
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(13873): 
D/AndroidRuntime(13873): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(13873): CheckJNI is OFF
D/AndroidRuntime(13873): setted country_code = Poland
D/AndroidRuntime(13873): setted countryiso_code = PL
D/AndroidRuntime(13873): setted sales_code = PLS
D/AndroidRuntime(13873): readGMSProperty: start
D/AndroidRuntime(13873): readGMSProperty: already setted!!
D/AndroidRuntime(13873): readGMSProperty: end
D/AndroidRuntime(13873): addProductProperty: start
D/dalvikvm(13873): Trying to load lib libjavacore.so 0x0
D/dalvikvm(13873): Added shared lib libjavacore.so 0x0
D/dalvikvm(13873): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(13873): Added shared lib libnativehelper.so 0x0
D/dalvikvm(13873): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(13873): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(13873): failed to load memtrack module: -2
D/dalvikvm(13873): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(13873): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2419): START PACKAGE DELETE: observer{1110326352}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2419): !@killApplicatoin: 10586, uninstall pkg
I/ActivityManager( 2419): Killing 7646:com.test.thalitest/u0a586 (adj 0): stop com.test.thalitest
I/ActivityManager( 2419): Killing 6694:com.policydm/1000 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7776:com.sec.android.soagent/u0a38 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7691:com.vlingo.midas/u0a34 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7764:com.samsung.klmsagent/u0a18 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7751:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7925:com.sec.android.diagmonagent/1000 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 5753:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 6665:com.sec.pcw.device/1000 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 2816:com.android.settings/1000 (adj 15): empty for 1803s
I/ActivityManager( 2419): Killing 7893:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1804s
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1919): id=22 Removed EimLayer (5/10)
I/SurfaceFlinger( 1919): id=22 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1919): id=21 Removed EimLayer (4/9)
I/SurfaceFlinger( 1919): id=21 Removed EimLayer (-2/9)
I/SurfaceFlinger( 1919): id=23 Removed NainActivit (6/8)
I/SurfaceFlinger( 1919): id=23 Removed NainActivit (-2/8)
I/SurfaceFlinger( 1919): id=23 Removed NainActivit (-2/8)
I/WindowState( 2419): WIN DEATH: Window{43054988 u0 com.test.thalitest/com.test.thalitest.MainActivity}
V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/Launcher( 2773): onRestart, Launcher: 1110057312
D/Launcher( 2773): onStart, Launcher: 1110057312
D/Launcher.HomeView( 2773): onStart
I/SurfaceFlinger( 1919): id=25 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/StatusBarManagerService( 2419): tr p:2773,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:2773,o:f
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7646 uid 10586
W/PackageSettings( 2419): Skipping PackageSetting{4252ee38 com.example.hello/10580} due to missing metadata
D/PackageManager( 2419): checkUidPermission - Execution time: 202 ms
D/PackageManager( 2419): checkUidPermission - Execution time: 153 ms
D/PackageManager( 2419): checkUidPermission - Execution time: 103 ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10586, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6468): GC_EXPLICIT freed 562K, 28% free 9982K/13756K, paused 15ms+6ms, total 82ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10586, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 3161): GC_EXPLICIT freed 440K, 21% free 12397K/15556K, paused 10ms+13ms, total 127ms
D/dalvikvm( 2962): GC_EXPLICIT freed 1468K, 27% free 10033K/13708K, paused 14ms+9ms, total 114ms
E/SamsungIME( 2976): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5160): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/SELinux (13904): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13904):  
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2733): Ignoring removeGeofence because network location is disabled.
I/SELinux (13904): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13904):  
I/SELinux (13904):  
I/SELinux (13904): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13904): >>>>> Normal User
E/dalvikvm(13904): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (13904): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(13904): in addTimaSignatureService
D/TimaKeyStoreProvider(13904): Cannot add TimaSignature Service, License check Failed
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
D/ActivityThread(13904): Added TimaKesytore provider
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2419): GC_EXPLICIT freed 2888K, 58% free 25340K/59752K, paused 18ms+23ms, total 337ms
D/PackageManager( 2419): queryIntentReceivers - Execution time: 165 ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RegisteredServicesCache( 2755): empty dynamic service
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2419): PackageReceiver onReceive()
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/dalvikvm(13904): GC_CONCURRENT freed 3003K, 31% free 9565K/13712K, paused 4ms+2ms, total 29ms
D/dalvikvm(13904): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
D/elm:14132(13904): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(13904): ELMEngine.ELMEngine( context ).
D/elm:14132(13904): MDMBridge.setEnterpriseBridge()
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(13904): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(13904): ElmAgentService : onCreate()
D/elm:14132(13904): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(13904): MainReceiver.listeningToPackageRemoved()
D/elm:14132(13904): MDMBridge.getInstance()
D/elm:14132(13904): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(13904): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (13917): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13917):  
D/elm:14132(13904): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(13904): ElmAgentService : onDestroy().
I/SELinux (13917): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13917):  
I/SELinux (13917):  
I/SELinux (13917): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/ActivityManager( 2419): Killing 7944:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1803s
E/SELinux (13917): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13917): >>>>> Normal User
E/dalvikvm(13917): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (13917): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(13917): in addTimaSignatureService
D/TimaKeyStoreProvider(13917): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13917): Added TimaKesytore provider
D/dalvikvm( 2755): GC_CONCURRENT freed 2341K, 26% free 10262K/13732K, paused 18ms+5ms, total 186ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(13917): GC_CONCURRENT freed 2996K, 31% free 9571K/13708K, paused 3ms+1ms, total 25ms
D/dalvikvm(13917): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/dalvikvm( 2419): GC_EXPLICIT freed 1123K, 58% free 25307K/59752K, paused 9ms+57ms, total 614ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10586 #1
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (13932): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13932):  
I/ActivityManager( 2419): Killing 5827:com.osp.app.signin/u0a44 (adj 15): empty for 1804s
W/ApplicationsProvider( 2962): Could not fetch usage stats
W/ApplicationsProvider( 2962): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2962): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2962): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2962): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2962): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2962): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2962): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2962): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2962): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2962): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux (13932): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13932):  
I/SELinux (13932):  
I/SELinux (13932): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13932): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13932): >>>>> Normal User
E/dalvikvm(13932): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (13932): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2419): delete sourFile : 
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13932): in addTimaSignatureService
D/TimaKeyStoreProvider(13932): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13932): Added TimaKesytore provider
D/PackageManager( 2419): delete native library directory: 
D/PackageManager( 2419): return delete result to caller: 1110326352
D/PackageManager( 2419): returnCode: 1
D/AndroidRuntime(13873): Shutting down VM
D/dalvikvm(13873): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 6ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "sms"
D/dalvikvm(13932): GC_CONCURRENT freed 3010K, 31% free 9560K/13712K, paused 3ms+2ms, total 34ms
D/dalvikvm(13932): WAIT_FOR_CONCURRENT_GC blocked 25ms
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (13947): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13947):  
I/ActivityManager( 2419): Killing 7956:com.sec.android.app.voicenote/1000 (adj 15): empty for 1804s
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
I/SELinux (13947): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13947):  
I/SELinux (13947):  
I/SELinux (13947): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13947): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13947): >>>>> Normal User
E/dalvikvm(13947): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (13947): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(13947): in addTimaSignatureService
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/TimaKeyStoreProvider(13947): Cannot add TimaSignature Service, License check Failed
I/CrashAnrDetector( 2419): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2419): clearDefaults: com.test.thalitest
D/ActivityThread(13947): Added TimaKesytore provider
D/dalvikvm(13947): GC_CONCURRENT freed 3004K, 31% free 9568K/13712K, paused 4ms+2ms, total 43ms
D/dalvikvm(13947): WAIT_FOR_CONCURRENT_GC blocked 36ms
I/SELinux (13963): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13963):  
I/SELinux (13963): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13963):  
I/SELinux (13963):  
I/SELinux (13963): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13963): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13963): >>>>> Normal User
E/dalvikvm(13963): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (13963): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2419): Killing 6612:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1804s
I/dalvikvm(13963): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(13963): in addTimaSignatureService
D/TimaKeyStoreProvider(13963): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13963): Added TimaKesytore provider
D/dalvikvm(13963): GC_CONCURRENT freed 3006K, 31% free 9566K/13712K, paused 4ms+2ms, total 26ms
D/dalvikvm(13963): WAIT_FOR_CONCURRENT_GC blocked 21ms
E/SQLiteDatabase(13963): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(13963): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(13963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(13963): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(13963): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(13963): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13963): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13963): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13963): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13963): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(13963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(13963): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(13963): Shutting down VM
W/dalvikvm(13963): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(13963): FATAL EXCEPTION: main
E/AndroidRuntime(13963): Process: com.sec.pcw.device, PID: 13963
E/AndroidRuntime(13963): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13963): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(13963): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(13963): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(13963): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(13963): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(13963): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(13963): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(13963): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(13963): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(13963): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(13963): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(13963): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(13963): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(13963): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(13963): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(13963): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(13963): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(13963): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(13963): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(13963): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(13963): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(13963): 	... 12 more
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (13976): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13976):  
I/Process (13963): Sending signal. PID: 13963 SIG: 9
I/ActivityManager( 2419): Process com.sec.pcw.device (pid 13963) (adj 0) has died.
D/dalvikvm( 1920): GC_EXPLICIT freed 43K, 12% free 9502K/10688K, paused 3ms+3ms, total 41ms
I/SELinux (13976): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13976):  
I/SELinux (13976):  
I/SELinux (13976): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13976): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(13976): >>>>> Normal User
E/dalvikvm(13976): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (13976): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 12% free 9502K/10688K, paused 2ms+4ms, total 29ms
D/TimaKeyStoreProvider(13976): in addTimaSignatureService
D/TimaKeyStoreProvider(13976): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13976): Added TimaKesytore provider
D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 12% free 9502K/10688K, paused 3ms+3ms, total 29ms
D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
D/dalvikvm(13976): GC_CONCURRENT freed 3005K, 31% free 9562K/13708K, paused 3ms+2ms, total 24ms
D/dalvikvm(13976): WAIT_FOR_CONCURRENT_GC blocked 20ms
W/System.err(13976): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(13976): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(13976): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(13976): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(13976): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(13976): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(13976): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(13976): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(13976): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(13976): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(13976): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(13976): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(13976): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(13976): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(13976): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(13976): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(13976): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(13976): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(13976): 	at libcore.io.Posix.open(Native Method)
W/System.err(13976): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(13976): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(13976): 	... 21 more
D/GalaxyFinderApplication(13976): [Slink platform] Version = 29011
D/GalaxyFinderApplication(13976): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (13990): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13990):  
I/ActivityManager( 2419): Killing 7788:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1805s
I/SELinux (13990): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13990):  
I/SELinux (13990):  
I/SELinux (13990): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (13990): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(13990): >>>>> Normal User
E/dalvikvm(13990): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (13990): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(13990): in addTimaSignatureService
D/TimaKeyStoreProvider(13990): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(13990): Added TimaKesytore provider
D/dalvikvm(13990): GC_CONCURRENT freed 2997K, 31% free 9571K/13712K, paused 2ms+2ms, total 23ms
D/dalvikvm(13990): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(13990): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(13990): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(13990): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(13990): ContentProvider is not null
W/ResourceType(13990): No package identifier when getting value for resource number 0x00000000
I/System.out(13990): resource Id::2131361807
E/SQLiteDatabase(13990): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(13990): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(13990): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(13990): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(13990): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(13990): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(13990): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(13990): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(13990): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(13990): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(13990): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(13990): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(13990): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(13990): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(13990): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(13990): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(13990): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(13990): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(13990): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(13990): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase
```
