#### Test 506502789b39735_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/BatteryService( 2419): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7208): 
D/AndroidRuntime( 7208): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7208): CheckJNI is OFF
D/AndroidRuntime( 7208): setted country_code = Poland
D/AndroidRuntime( 7208): setted countryiso_code = PL
D/AndroidRuntime( 7208): setted sales_code = PLS
D/AndroidRuntime( 7208): readGMSProperty: start
D/AndroidRuntime( 7208): readGMSProperty: already setted!!
D/AndroidRuntime( 7208): readGMSProperty: end
D/AndroidRuntime( 7208): addProductProperty: start
D/dalvikvm( 7208): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7208): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7208): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7208): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7208): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7208): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7208): failed to load memtrack module: -2
D/dalvikvm( 7208): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7208): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 7231): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7231):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7208): Shutting down VM
D/dalvikvm( 7208): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7231): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7231):  
I/SELinux ( 7231):  
I/SELinux ( 7231): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7231): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7231): >>>>> Normal User
E/dalvikvm( 7231): >>>>> com.test.thalitest [ userId:0 | appId:10553 ]
E/SELinux ( 7231): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7231): in addTimaSignatureService
D/TimaKeyStoreProvider( 7231): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7231): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4155): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4155): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7231): GC_CONCURRENT freed 3006K, 31% free 9559K/13840K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7231): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7231): Binding Chromium to the background looper Looper (main, tid 1) {4228f370}
I/chromium( 7231): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7231): Initializing chromium process, renderers=0
W/chromium( 7231): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7231): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7231): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7231): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7231): Mali API Version : 401
,I/Mali    ( 7231): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7231): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7231): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7231): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7231): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7231): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7231): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:7231,o:f
,W/dalvikvm( 7231): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7231): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7231): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7231): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7231): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7231): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7231): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7231): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7231): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7231): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7231): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7231): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7231): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2419): semi p:7231,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7231): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7231): Enabling debug mode 0
,W/AwContents( 7231): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7231): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/JsMessageQueue( 7231): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7231): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422876f0
,D/dalvikvm( 7231): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422876f0
D/jxcore_app_log( 7231): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027544896
,D/JX-Cordova( 7231): jxcore cordova android initializing
,D/dalvikvm( 7231): GC_CONCURRENT freed 1282K, 19% free 11348K/13900K, paused 1ms+2ms, total 21ms
,D/dalvikvm( 7231): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7231): GC_CONCURRENT freed 1926K, 18% free 14917K/18132K, paused 2ms+2ms, total 39ms
,D/dalvikvm( 7231): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7231): GC_FOR_ALLOC freed 5328K, 30% free 16202K/23052K, paused 52ms, total 52ms
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/dalvikvm( 7231): GC_CONCURRENT freed 6682K, 32% free 17670K/25664K, paused 1ms+15ms, total 74ms
,D/dalvikvm( 7231): WAIT_FOR_CONCURRENT_GC blocked 62ms
,D/dalvikvm( 7231): GC_FOR_ALLOC freed 1285K, 32% free 17508K/25664K, paused 52ms, total 54ms
,I/dalvikvm-heap( 7231): Grow heap (frag case) to 21.875MB for 3713210-byte allocation
,D/dalvikvm( 7231): GC_FOR_ALLOC freed 2528K, 37% free 18605K/29292K, paused 42ms, total 42ms
,W/jxcore-log( 7231): Initializing JXcore engine
,W/jxcore-log( 7231): JXcore engine is ready
,W/jxcore-log( 7231): Starting JXcore engine
,W/jxcore-log( 7231): Platform android
W/jxcore-log( 7231): 
,W/jxcore-log( 7231): Process ARCH arm
W/jxcore-log( 7231): 
,I/jxcore-log( 7231): JXcore Cordova bridge is ready!
I/jxcore-log( 7231): 
,W/jxcore-log( 7231): JXcore engine is started
,I/chromium( 7231): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7231): Toggling radios to true
I/jxcore-log( 7231): 
,D/BluetoothAdapter( 7231): enable(): BT is already enabled..!
,I/WifiManager( 7231): packageName : com.test.thalitest
,I/WifiManager( 7231): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7231, uid=10553
,W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7231, uid=10553 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7231, uid=10553 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2419): disconnect: pid=7231, uid=10553
I/wpa_supplicant( 3967): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7231): Radios toggled
I/jxcore-log( 7231): 
,I/jxcore-log( 7231): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7231): 
,I/jxcore-log( 7231): Perf Test app loaded loaded
I/jxcore-log( 7231): 
,I/wpa_supplicant( 3967): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030,
,I/jxcore-log( 7231): check test folder,
I/jxcore-log( 7231): 
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true,
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7231): found test : ./testFindPeers.js,
I/jxcore-log( 7231): 
,I/wpa_supplicant( 3967): reset timer : RESET_TIMER 0,
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3967): First Scan Start
,I/wpa_supplicant( 3967): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true,
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): Skip scan - already scanning
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2419): Attempting to switch to mobile,
D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7279): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7279):  
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/jxcore-log( 7231): found test : ./testSendData.js,
I/jxcore-log( 7231): 
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling,
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1,
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7279): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7279):  
I/SELinux ( 7279):  
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-91ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 7279): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7279): >>>>> Normal User
E/dalvikvm( 7279): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-96ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/SELinux ( 7279): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-21ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory,
,D/TimaKeyStoreProvider( 7279): in addTimaSignatureService,
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
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7279): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7279): Added TimaKesytore provider
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x7b97b6c8 clazz=0x62f00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,E/SPPClientService( 5520): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5520): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5520): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5520): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5520): [b] ResponseMap empty
,V/NativeCrypto( 2853): Read error: ssl=0x7c298630: I/O error during system call, Connection timed out
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7c298630: I/O error during system call, Broken pipe
,D/dalvikvm( 7279): GC_CONCURRENT freed 2985K, 31% free 9583K/13844K, paused 3ms+12ms, total 81ms
,D/dalvikvm( 7279): WAIT_FOR_CONCURRENT_GC blocked 67ms
,I/System.out( 7279): Inside WakeupProvider
,I/System.out( 7279): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): updateIfacesLocked()
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,I/chromium( 7231): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51),
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): performPollLocked() took 36ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,I/VlingoApplication( 7279): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7279): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7279): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7279): initQueue()
I/ActivityManager( 2419): Killing 6148:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): noConnectivity : true
,I/DBG_DM  ( 4725): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7308): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7308):  
,I/wpa_supplicant( 3967): nl80211: Received scan results (5 BSSes)
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7308): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7308):  
I/SELinux ( 7308):  
,I/SELinux ( 7308): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7308): >>>>> Normal User
,E/dalvikvm( 7308): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7308): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7308): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7308): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7308): Added TimaKesytore provider
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3967): Associated with C0.AA.48
I/wpa_supplicant( 3967): freq(2412) increment count 2
,I/wpa_supplicant( 3967): meet head of list.
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7308): GC_CONCURRENT freed 3014K, 31% free 9560K/13844K, paused 4ms+5ms, total 54ms
,D/dalvikvm( 7308): WAIT_FOR_CONCURRENT_GC blocked 47ms
,I/ActivityManager( 2419): Killing 6218:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/SELinux ( 7322): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7322):  
,D/dalvikvm( 2419): GC_CONCURRENT freed 4304K, 71% free 25545K/86864K, paused 11ms+22ms, total 253ms
,I/SELinux ( 7322): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7322):  
I/SELinux ( 7322):  
,I/SELinux ( 7322): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7322): >>>>> Normal User
,E/dalvikvm( 7322): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7322): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7322): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7322): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7322): Added TimaKesytore provider
,I/dhcpcd  ( 7326): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7326): bssid match
,D/dalvikvm( 7322): GC_CONCURRENT freed 3000K, 31% free 9569K/13840K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 7322): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/ActivityManager( 2419): Killing 6284:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7341): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7341):  
,I/SELinux ( 7341): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7341):  
I/SELinux ( 7341):  
,I/SELinux ( 7341): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7341): >>>>> Normal User
,E/dalvikvm( 7341): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7341): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7341): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7341): Added TimaKesytore provider
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7341): GC_CONCURRENT freed 2996K, 31% free 9565K/13836K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7341): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/KLMS-2.3.201 : ( 7341): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7341): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229861586
,I/KLMS-2.3.201 : ( 7341): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6316:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7353):  
,I/SELinux ( 7353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7353):  
I/SELinux ( 7353):  
,I/SELinux ( 7353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7353): >>>>> Normal User
,E/dalvikvm( 7353): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7353): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7353): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7353): Added TimaKesytore provider
,D/dalvikvm( 7353): GC_CONCURRENT freed 3000K, 31% free 9565K/13836K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7353): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5784): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5784): [BDLM] already registered in spp
I/SA      ( 5784): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5784): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5784): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5784): [OR] == isSIMCardReady false ==
I/SA      ( 5784): [SCU] == networkStateCheck == false
,I/SA      ( 5784): [OR] onReceive END
I/ActivityManager( 2419): Killing 5565:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SELinux ( 7365): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7365):  
,I/SELinux ( 7365): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7365):  
I/SELinux ( 7365):  
,I/SELinux ( 7365): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 13% free 9502K/10820K, paused 4ms+4ms, total 55ms
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7365): >>>>> Normal User
,E/dalvikvm( 7365): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7365): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7365): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10820K, paused 4ms+4ms, total 38ms
,D/ActivityThread( 7365): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9502K/10820K, paused 3ms+4ms, total 37ms
,D/dalvikvm( 7365): GC_CONCURRENT freed 2997K, 31% free 9570K/13840K, paused 4ms+3ms, total 45ms
,D/dalvikvm( 7365): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/sCloudBackupApp( 7365): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7365): Other Intent
I/ActivityManager( 2419): Killing 6273:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7379):  
,I/SELinux ( 7379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7379):  
I/SELinux ( 7379):  
,I/SELinux ( 7379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7379): >>>>> Normal User
,E/dalvikvm( 7379): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7379): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7379): Added TimaKesytore provider
,D/dalvikvm( 7379): GC_CONCURRENT freed 2990K, 31% free 9570K/13836K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7379): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7379): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7379): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5316): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7379): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5316): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7379): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5316): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6290:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/Headlines( 5848): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine( 2419): VerifyingLinkState enter
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/HeadlinesChannelUtil( 5848): getCountryCode(): countryCode = PL
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/Headlines( 5848): Breath.onCreate
,D/Headlines( 5848): Breath timer started. interval : 30000
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/SELinux ( 7412): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7412):  
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling,
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
V/AlarmManager( 2419): waitForAlarm result :8
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5848): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5848): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5848): requestUpdateNewsWelcomeCard !!! no welcome card,
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling,
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults,
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false,
,I/SELinux ( 7412): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7412):  
I/SELinux ( 7412):  
,I/SELinux ( 7412): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7412): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7412): >>>>> Normal User
,E/dalvikvm( 7412): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
,E/SELinux ( 7412): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/TimaKeyStoreProvider( 7412): in addTimaSignatureService
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7412): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7412): Added TimaKesytore provider
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked(),
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152,
D/dalvikvm( 7412): GC_CONCURRENT freed 2994K, 31% free 9572K/13836K, paused 4ms+2ms, total 34ms
D/dalvikvm( 7412): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
V/NetworkStats( 2419): performPollLocked() took 25ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit,
,V/WebViewChromium( 7412): Binding Chromium to the background looper Looper (main, tid 1) {4228c3a8},
,I/chromium( 7412): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7412): Initializing chromium process, renderers=0,
,W/chromium( 7412): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/libEGL  ( 7412): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7412): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7412): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7412): Mali API Version : 401
,I/Mali    ( 7412): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7412): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7412): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7412): Starting up...
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4725): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/iu.Environment( 5915): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5118): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5118): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5118): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229bf70
,I/SELinux ( 7465): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7465):  
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7465): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7465):  
I/SELinux ( 7465):  
,I/SELinux ( 7465): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7465): >>>>> Normal User
,E/dalvikvm( 7465): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7465): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/Watchdog( 2419): !@Sync 9
D/TimaKeyStoreProvider( 7465): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7465): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7465): Added TimaKesytore provider
,I/jxcore-log( 7231): Connected to the server!
I/jxcore-log( 7231): 
,I/chromium( 7231): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 7465): GC_CONCURRENT freed 2991K, 31% free 9581K/13844K, paused 5ms+2ms, total 30ms
,D/dalvikvm( 7465): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/ActivityManager( 2419): Killing 5964:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7492): >>>>> Normal User
,E/dalvikvm( 7492): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,I/SELinux ( 7505): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7505):  
,D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7492): Added TimaKesytore provider
,I/ActivityManager( 2419): Killing 6236:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7505):  
I/SELinux ( 7505):  
,I/SELinux ( 7505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7505): >>>>> Normal User
,E/dalvikvm( 7505): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7505): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7505): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7505): Added TimaKesytore provider
D/dalvikvm( 7492): GC_CONCURRENT freed 3002K, 31% free 9565K/13844K, paused 5ms+5ms, total 36ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/BadgeProvider( 7492): onCreate
,D/BadgeProvider( 7492): DatabaseHelper
,D/BadgeProvider( 7492): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7492): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7492): sendNotify, [notify] : null
D/BadgeProvider( 7492): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2772): reloadBadges entered.
D/BadgeProvider( 7492): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7492): update, [UpdateCount] : 1
,D/dalvikvm( 7505): GC_CONCURRENT freed 2999K, 31% free 9566K/13840K, paused 9ms+2ms, total 44ms
,D/dalvikvm( 7505): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/hcjo    ( 5936): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5936): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5936): exit::IDLE
,D/InitializeManagerStateMachine( 5936): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5936): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5936): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5936): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5936): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5936): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5936): entry::SUCCESS
,D/hcjo    ( 5936): AutoUpdateManager:INITCHECK:onInitializeSuccess,
D/hcjo    ( 5936): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/hcjo    ( 5936): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
,D/InitializeManagerStateMachine( 5936): exit::SUCCESS
,D/InitializeManagerStateMachine( 5936): entry::IDLE,
,E/SPPClientService( 5520): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE,
E/SPPClientService( 5520): [SystemStateMoniter] Current Time : 289216
,E/SPPClientService( 5520): [SystemStateMoniter] No Connect : true
,I/jxcore-log( 7231): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7231): 
,E/SPPClientService( 5520): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2419): Killing 6135:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5520): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5520): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5520): [[PushClientService]] <<--- deInitPushClientService  END  --->>
D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 10
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 1791 latestRequest time : 1450229862696 current time : 1450229864487
,E/SPPClientService( 5520): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5520): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5520): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5520): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7341): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7341): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450229864892
,I/KLMS-2.3.201 : ( 7341): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3237): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3237): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7353): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 3237): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3237): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7529):  
,I/GallerySearchProvider( 3365): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7529):  
I/SELinux ( 7529):  
,I/SELinux ( 7529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7529): >>>>> Normal User
,E/dalvikvm( 7529): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7529): in addTimaSignatureService
I/SA      ( 5784): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5784): [BDLM] already registered in spp
,D/TimaKeyStoreProvider( 7529): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5784): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5784): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/ActivityThread( 7529): Added TimaKesytore provider
,I/SA      ( 5784): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5784): [OR] == isSIMCardReady false ==
,I/SA      ( 5784): [SCU] == networkStateCheck == true
,I/SA      ( 5784): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5784): isChinaCountryCode : false
,I/SA      ( 5784): [OR] == networkStateCheck true ==
,I/SELinux ( 7541): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7541):  
,D/dalvikvm( 2723): GC_EXPLICIT freed 337K, 28% free 10039K/13828K, paused 6ms+14ms, total 98ms
,I/SA      ( 5784): [OR] GetMyCountryZoneTask
,I/SA      ( 5784): [OR] onReceive END
,I/SA      ( 5784): [SRS] prepareGetMyCountryZone
,I/SA      ( 5784): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5784): [SSP] query invoked
D/PhoneNumberLocatorBootCompletedReceiver( 2751): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2751): Phone number locator feature is dsiabled
,I/SA      ( 5784): [TPMU] GetMccFromDB : null
I/SA      ( 5784): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5784): [TPM] isNoProxy(default) : true
,I/SA      ( 5784): [RC New] Execute method=[GET] start
I/SELinux ( 7541): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7541):  
I/SELinux ( 7541):  
,I/SELinux ( 7541): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7541): >>>>> Normal User
,E/dalvikvm( 7541): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SCloudBackupReceiver( 7365): Other Intent
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/TimaKeyStoreProvider( 7541): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7541): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7541): Added TimaKesytore provider
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/dalvikvm( 7529): GC_CONCURRENT freed 2985K, 31% free 9584K/13840K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 7529): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/com.samsung.app( 7379): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5848): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5848): getCountryCode(): countryCode = PL
,I/System.out( 7322): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/dalvikvm( 7541): GC_CONCURRENT freed 3002K, 31% free 9570K/13844K, paused 3ms+9ms, total 43ms
,D/dalvikvm( 7541): WAIT_FOR_CONCURRENT_GC blocked 40ms
,D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5848): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5848): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5848): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5848): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5915): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5118): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5118): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5118): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4229bf70
,V/KVNProvider( 7541): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7541): getFindoCursor query string : 
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/System.out( 7322): Thread-630(ApacheHTTPLog):isShipBuild true
D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/System.out( 7322): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/KVNProvider( 7541): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5936): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5936): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5936): exit::IDLE
,D/InitializeManagerStateMachine( 5936): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5936): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5936): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5936): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5936): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5936): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5936): entry::SUCCESS
,D/hcjo    ( 5936): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5936): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5936): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5936): exit::SUCCESS
,D/InitializeManagerStateMachine( 5936): entry::IDLE
,E/SPPClientService( 5520): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5520): [SystemStateMoniter] Current Time : 290360
,E/SPPClientService( 5520): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5520): GC_CONCURRENT freed 1947K, 25% free 10510K/13832K, paused 3ms+5ms, total 48ms
,D/dalvikvm( 5520): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/System.out( 7322): AsyncTask #1 calls detatch()
,W/System.err( 7322): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7322): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7322): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7322): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7322): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7322): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7322): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7322): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7322): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7322): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7322): Caused by: java.lang.NullPointerException
W/System.err( 7322): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7322): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7322): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7322): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7322): 	... 8 more
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/ActivityManager( 2419): Killing 6171:com.google.android.music:main/u0a125 (adj 15): empty #43
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,I/SA      ( 5784): [RC New] [v2liruge] api execute + 790
,I/SA      ( 5784): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5784): AsyncTask #2 calls detatch()
,I/SA      ( 5784): [TPMU] getNetworkMcc : 
,I/SA      ( 5784): [SCU] saveMccToPreferece Start
I/SA      ( 5784): [SCU] RegionMCC : 260
,I/SA      ( 5784): [SSP] query invoked
,I/SA      ( 5784): [TPMU] GetMccFromDB : null
,I/SA      ( 5784): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5784): [SCU] saveMccToPreferece End
,I/SA      ( 5784): [RC New] executeRequest [v2liruge] end. 903
I/SA      ( 5784): [RC New] Execute end
I/SA      ( 5784): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5784): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5520): [b] __InitReply__
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/ActivityManager( 2419): Killing 6525:com.android.defcontainer/u0a6 (adj 15): empty #43
I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 292931
,D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
,D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3477)
,I/GAV2    ( 7412): Thread[GAThread,5,main]: No campaign data found.
,I/PowerManagerService( 2419): [PWL] Off : 225s ago,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6582): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): [GetString-S]
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6582): [ensureRegistration] - No Samsung account,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5936): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5936): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5936): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5936): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5936): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5936): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5936): entry::IDLE,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 298, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 5936): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5936): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5936): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5936): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5936): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
,D/PreloadUpdateManagerStateMachine( 5936): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 5936): entry::IDLE,
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{46821350 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{43120d40 u0 com.sec.spp.push/.PushClientService},
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2419): stay LED for fully charged
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2419): initializing...,
I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2419): Opening the session,
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 27347 latestRequest time : 1450229865357 current time : 1450229892704
,E/Watchdog( 2419): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3992): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2419): [PWL] Off : 275s ago,
,E/Watchdog( 2419): !@Sync 11,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7940): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7940):  
,I/SELinux ( 7940): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7940):  
I/SELinux ( 7940):  
,I/SELinux ( 7940): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7940): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7940): >>>>> Normal User
,E/dalvikvm( 7940): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7940): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7940): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7940): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7940): Added TimaKesytore provider
,D/dalvikvm( 7940): GC_CONCURRENT freed 3000K, 31% free 9569K/13844K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 7940): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 2419): GC_EXPLICIT freed 2706K, 71% free 25509K/86864K, paused 11ms+21ms, total 237ms
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 63732 latestRequest time : 1450229865357 current time : 1450229929090
,I/ActivityManager( 2419): Killing 6418:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 87337 latestRequest time : 1450229865357 current time : 1450229952694
,E/Watchdog( 2419): !@Sync 12
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 117382 latestRequest time : 1450229865357 current time : 1450229982739
,E/Watchdog( 2419): !@Sync 13
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5848): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5848): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5848): Breath 147359 latestRequest time : 1450229865357 current time : 1450230012717
,D/Headlines( 5848): stop 
,D/Headlines( 5848): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6555:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 15
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 16
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2580): GC_CONCURRENT freed 15727K, 34% free 33862K/50856K, paused 16ms+9ms, total 112ms
,E/Watchdog( 2419): !@Sync 17
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 18
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 19
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2419): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/GAV2    ( 5607): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5607): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3996K, 71% free 25428K/86864K, paused 26ms+18ms, total 272ms
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4065): GC_CONCURRENT freed 2892K, 30% free 9726K/13888K, paused 19ms+2ms, total 110ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5520): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2419): LightSensor enable = 0
D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2419): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
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
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/SPPClientService( 5520): [b] __PingReply__
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3868K, 71% free 25439K/86864K, paused 23ms+18ms, total 268ms
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2419): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
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
,I/EventLogService( 3429): Aggregate from 1450229101292 (log), 1450229101292 (data)
,D/dalvikvm( 3429): GC_CONCURRENT freed 2309K, 23% free 12523K/16104K, paused 23ms+10ms, total 131ms
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4065): GC_CONCURRENT freed 2041K, 30% free 9724K/13888K, paused 2ms+3ms, total 22ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2419): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3881K, 71% free 25451K/86864K, paused 22ms+21ms, total 265ms
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,E/SPPClientService( 5520): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 57ms
,I/ProcessStatsService( 2419): Prepared write state in 33ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2015-12-15-12-22-00.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2419): Killing 6412:com.sec.knox.bridge/1000 (adj 15): empty for 1829s
,I/ActivityManager( 2419): Killing 4836:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1829s
,I/ActivityManager( 2419): Killing 6398:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1829s
,I/ActivityManager( 2419): Killing 6375:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1838s
,I/ActivityManager( 2419): Killing 6743:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1839s
,I/ActivityManager( 2419): Killing 6729:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6717:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6705:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1840s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 6692:com.samsung.helphub/1000 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6679:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6666:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1840s
,I/ActivityManager( 2419): Killing 6653:com.sec.android.service.cm/u0a82 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6334:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 5678:com.android.mms/u0a49 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6627:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 5980:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1841s
,I/ActivityManager( 2419): Killing 6597:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1842s
,I/ActivityManager( 2419): Killing 6569:com.android.musicfx/u0a24 (adj 15): empty for 1842s
,D/CountryDetector( 2419): No listener is left
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2419): waitForAlarm result :4
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x3)
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 62ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12518):  
,I/SELinux (12518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12518):  
I/SELinux (12518):  
,I/SELinux (12518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12518): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12518): >>>>> Normal User
,E/dalvikvm(12518): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12518): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12518): in addTimaSignatureService
,D/TimaKeyStoreProvider(12518): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12518): Added TimaKesytore provider
,D/dalvikvm(12518): GC_CONCURRENT freed 3007K, 31% free 9555K/13836K, paused 3ms+3ms, total 28ms
,D/dalvikvm(12518): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(12518): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12518): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12518): Widget random data : 7
,D/@ WidgetProvider(12518): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12518): Widget random data : 6
,E/dalvikvm(12518): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12518): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12518): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12518): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12518): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12518): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12518): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12518): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12518): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12518): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12518): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12518): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12518): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12518): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12518): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12518): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12518): Thread-666(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12518): Thread-666(ApacheHTTPLog):isShipBuild true
,I/System.out(12518): Thread-666(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12518): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12518): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12518): Max ALLOWED memory (MB): 128
,V/ImageManager(12518): Max SHOULD USE memory (MB): 128
,V/ImageManager(12518): Max Image Cache memory (MB): 32
,D/skia    (12518): getTotalSize : Do not get file length
,D/@ WidgetProvider(12518): Building widget : 5
,D/dalvikvm( 2772): GC_CONCURRENT freed 8856K, 36% free 18313K/28440K, paused 8ms+8ms, total 86ms
,D/dalvikvm( 2772): WAIT_FOR_CONCURRENT_GC blocked 74ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 67
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 4120K, 71% free 25341K/86864K, paused 9ms+17ms, total 215ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 69
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2419): Killing 6611:com.policydm/1000 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7353:com.sec.android.soagent/u0a38 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7279:com.vlingo.midas/u0a34 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7341:com.samsung.klmsagent/u0a18 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7322:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 5726:com.sec.android.diagmonagent/1000 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7308:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 6582:com.sec.pcw.device/1000 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 2831:com.android.settings/1000 (adj 15): empty for 1815s
,I/ActivityManager( 2419): Killing 7492:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1816s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3992): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3992): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
