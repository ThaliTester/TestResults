#### Test 55431344148e3f8_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2392): stay LED for fully charged
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7178): 
D/AndroidRuntime( 7178): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7178): CheckJNI is OFF
D/AndroidRuntime( 7178): setted country_code = Poland
D/AndroidRuntime( 7178): setted countryiso_code = PL
D/AndroidRuntime( 7178): setted sales_code = PLS
D/AndroidRuntime( 7178): readGMSProperty: start
D/AndroidRuntime( 7178): readGMSProperty: already setted!!
D/AndroidRuntime( 7178): readGMSProperty: end
D/AndroidRuntime( 7178): addProductProperty: start
D/dalvikvm( 7178): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7178): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7178): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7178): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7178): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7178): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7178): failed to load memtrack module: -2
D/dalvikvm( 7178): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7178): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2392): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2392): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2392): mDVFSHelper.acquire()
I/SELinux ( 7190): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7190):  
D/PointerIcon( 2392): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2392): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2392): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2392): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7178): Shutting down VM
D/dalvikvm( 7178): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7190): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7190):  
I/SELinux ( 7190):  
I/SELinux ( 7190): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7190): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7190): >>>>> Normal User
E/dalvikvm( 7190): >>>>> com.test.thalitest [ userId:0 | appId:10593 ]
E/SELinux ( 7190): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7190): in addTimaSignatureService
D/TimaKeyStoreProvider( 7190): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7190): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4182): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4182): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7190): GC_CONCURRENT freed 3005K, 30% free 9566K/13524K, paused 1ms+1ms, total 18ms
D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7190): Binding Chromium to the background looper Looper (main, tid 1) {4223f1a0}
I/chromium( 7190): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7190): Initializing chromium process, renderers=0
W/chromium( 7190): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7190): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7190): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7190): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7190): Mali API Version : 401
,I/Mali    ( 7190): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7190): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7190): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7190): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7190): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7190): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7190): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2392): tr p:7190,o:f
,W/dalvikvm( 7190): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7190): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7190): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
,W/dalvikvm( 7190): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7190): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7190): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7190): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7190): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7190): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7190): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7190): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7190): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7190): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2392): semi p:7190,o:f
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2392): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2392): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2392): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2392): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2392): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2392): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7190): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7190): Enabling debug mode 0
,W/AwContents( 7190): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7190): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2392): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2392): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2392): mDVFSHelper.release()
,D/JsMessageQueue( 7190): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7190): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42236fc0
D/dalvikvm( 7190): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42236fc0
D/jxcore_app_log( 7190): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027579664
D/JX-Cordova( 7190): jxcore cordova android initializing
E/Watchdog( 2392): !@Sync 8
D/dalvikvm( 7190): GC_CONCURRENT freed 1290K, 17% free 11349K/13588K, paused 2ms+3ms, total 23ms
D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 11ms
D/dalvikvm( 7190): GC_CONCURRENT freed 1949K, 17% free 14956K/17868K, paused 3ms+3ms, total 45ms
D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 25ms
D/CustomFrequencyManagerService( 2392): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 7190): GC_FOR_ALLOC freed 5363K, 29% free 16244K/22776K, paused 48ms, total 49ms
,D/AmoledAdjustTimer( 2392): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 7190): GC_CONCURRENT freed 6709K, 31% free 17704K/25384K, paused 3ms+11ms, total 78ms
D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 46ms
,D/dalvikvm( 7190): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 7190): GC_FOR_ALLOC freed 1332K, 31% free 17532K/25384K, paused 52ms, total 52ms
,I/dalvikvm-heap( 7190): Grow heap (frag case) to 21.587MB for 3713210-byte allocation
,D/dalvikvm( 7190): GC_FOR_ALLOC freed 2418K, 36% free 18740K/29012K, paused 49ms, total 49ms
,W/jxcore-log( 7190): Initializing JXcore engine
,W/jxcore-log( 7190): JXcore engine is ready
,W/jxcore-log( 7190): Starting JXcore engine
,W/jxcore-log( 7190): Platform android
W/jxcore-log( 7190): 
,W/jxcore-log( 7190): Process ARCH arm
W/jxcore-log( 7190): 
,I/jxcore-log( 7190): JXcore Cordova bridge is ready!
I/jxcore-log( 7190): 
,W/jxcore-log( 7190): JXcore engine is started
,I/chromium( 7190): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7190): Toggling radios to true
I/jxcore-log( 7190): 
,D/BluetoothAdapter( 7190): enable(): BT is already enabled..!
,I/WifiManager( 7190): packageName : com.test.thalitest
,I/WifiManager( 7190): setWifiEnabled : true
,I/WifiService( 2392): setWifiEnabled: true pid=7190, uid=10593
,W/ActivityManager( 2392): Permission Denial: getCurrentUser() from pid=7190, uid=10593 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2392): Failed getting userId using ActivityManagerNative
W/WifiService( 2392): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7190, uid=10593 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2392): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2392): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2392): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2392): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2392): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2392): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2392): disconnect: pid=7190, uid=10593
I/wpa_supplicant( 3980): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7190): Radios toggled
I/jxcore-log( 7190): 
,I/jxcore-log( 7190): Received device characteristics:
I/jxcore-log( 7190): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7190): Bluetooth name: S5mini-1
I/jxcore-log( 7190): Device name: samsung-SM-G800F
I/jxcore-log( 7190): 
,I/wpa_supplicant( 3980): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log( 7190): Perf Test app loaded loaded
I/jxcore-log( 7190): 
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7190): check test folder
I/jxcore-log( 7190): 
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3980): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3980): First Scan Start
I/wpa_supplicant( 3980): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7190): found test : ./testFindPeers.js
I/jxcore-log( 7190): 
,W/Settings( 2392): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2392): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2392): InactiveState{ what=143375 }
D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2392): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2392): net.tcp.usercfg.default not found in system default properties
I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3980): Skip scan - already scanning
E/ConnectivityService( 2392): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2392): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2392): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2392): InactiveState{ what=143375 }
D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/ConnectivityService( 2392): Attempting to switch to mobile
,I/jxcore-log( 7190): found test : ./testSendData.js
I/jxcore-log( 7190): 
,D/ConnectivityService( 2392): Attempting to switch to BLUETOOTH_TETHER
I/SELinux ( 7237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7237):  
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1,
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling,
,V/RouteController( 1915): RTNETLINK answers: No such process,
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1,
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
E/WifiStateMachine( 2392): Error! unhandled message{ when=-67ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2392): Error! unhandled message{ when=-66ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such file or directory,
I/SELinux ( 7237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7237):  
I/SELinux ( 7237):  
,I/SELinux ( 7237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7237): >>>>> Normal User
,E/dalvikvm( 7237): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,W/NetworkManagementService( 2392): route cmd failed: 
W/NetworkManagementService( 2392): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2392): '
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2392): ,	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2392): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088),
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2392): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,E/SELinux ( 7237): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2392): Error! unhandled message{ when=-15ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7237): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7237): Cannot add TimaSignature Service, License check Failed
,D/NetUtils( 2392): android_net_utils_resetConnections in env=0x7466aca8 clazz=0x62700001 iface=wlan0 mask=0x3
,D/ActivityThread( 7237): Added TimaKesytore provider
D/ConnectivityService( 2392): resetConnections(wlan0, 3)
,E/SPPClientService( 5526): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5526): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5526): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5526): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5526): [b] ResponseMap empty
,D/dalvikvm( 7237): GC_CONCURRENT freed 2985K, 30% free 9584K/13520K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7237): WAIT_FOR_CONCURRENT_GC blocked 18ms
,V/NativeCrypto( 2855): Read error: ssl=0x7b9d4568: I/O error during system call, Connection timed out
,V/NativeCrypto( 2855): SSL shutdown failed: ssl=0x7b9d4568: I/O error during system call, Broken pipe
,I/System.out( 7237): Inside WakeupProvider
,I/System.out( 7237): Inside onCreate() of WakeupTriggerProvide
,I/chromium( 7190): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
D/ConnectivityService( 2392): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2392): updateIfacesLocked()
V/NetworkStats( 2392): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7237): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7237): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7237): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked() took 30ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2840): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2840): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2392): Killing 6161:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7237): initQueue()
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2840): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2840): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2392): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2392): updateDataUsageMap
,D/Tethering( 2392): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2392): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2392): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): noConnectivity : true,
,I/DBG_DM  ( 4723): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected,
,I/SELinux ( 7266): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7266):  
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection...,
,I/SELinux ( 7266): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7266):  
I/SELinux ( 7266):  
,I/SELinux ( 7266): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7266): >>>>> Normal User
,E/dalvikvm( 7266): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7266): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7266): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7266): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7266): Added TimaKesytore provider
,I/wpa_supplicant( 3980): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3980): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 3980): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3980): Associated with C0.AA.48
D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7266): GC_CONCURRENT freed 3013K, 30% free 9561K/13524K, paused 2ms+4ms, total 42ms
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7266): WAIT_FOR_CONCURRENT_GC blocked 43ms
I/wpa_supplicant( 3980): freq(2412) increment count 2
,I/wpa_supplicant( 3980): meet head of list.
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3980): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3980): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
D/WifiNative( 2392): callSECApiVoid - ID [50]
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2392): Killing 6231:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2392): InactiveState{ what=143375 }
,D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,I/SELinux ( 7280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7280):  
,I/SELinux ( 7280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7280):  
I/SELinux ( 7280):  
,I/SELinux ( 7280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7280): >>>>> Normal User
,E/dalvikvm( 7280): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7280): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7280): Added TimaKesytore provider
,D/dalvikvm( 7280): GC_CONCURRENT freed 2992K, 30% free 9576K/13524K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7280): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/dhcpcd  ( 7292): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7292): bssid match
,I/ActivityManager( 2392): Killing 6299:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7301):  
,I/SELinux ( 7301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7301):  
I/SELinux ( 7301):  
,I/SELinux ( 7301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7301): >>>>> Normal User
,E/dalvikvm( 7301): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7301): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7301): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7301): Added TimaKesytore provider
,D/dalvikvm( 7301): GC_CONCURRENT freed 3003K, 30% free 9569K/13524K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7301): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection...
,D/KLMS-2.3.201 : ( 7301): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7301): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452246695834
,I/KLMS-2.3.201 : ( 7301): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2392): Killing 6328:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7315): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7315):  
,I/SELinux ( 7315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7315):  
I/SELinux ( 7315):  
,I/SELinux ( 7315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7315): >>>>> Normal User
,E/dalvikvm( 7315): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7315): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7315): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7315): Added TimaKesytore provider
,D/dalvikvm( 7315): GC_CONCURRENT freed 3000K, 30% free 9566K/13520K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7315): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
,I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
,I/SA      ( 5792): [SCU] == networkStateCheck == false
,I/SA      ( 5792): [OR] onReceive END
I/ActivityManager( 2392): Killing 6371:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7346): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7346):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 10% free 9503K/10496K, paused 4ms+5ms, total 47ms
,I/SELinux ( 7346): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7346):  
I/SELinux ( 7346):  
,I/SELinux ( 7346): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7346): >>>>> Normal User
,E/dalvikvm( 7346): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9503K/10496K, paused 3ms+5ms, total 39ms
,D/TimaKeyStoreProvider( 7346): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7346): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7346): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9503K/10496K, paused 3ms+4ms, total 36ms
,D/WifiP2pService( 2392): InactiveState{ what=143375 }
,D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2392): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2392): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 2392): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/ConnectivityService( 2392): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/WifiStateMachine( 2392): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/dalvikvm( 7346): GC_CONCURRENT freed 2997K, 30% free 9577K/13524K, paused 7ms+8ms, total 47ms
D/dalvikvm( 7346): WAIT_FOR_CONCURRENT_GC blocked 33ms
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2392): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2392): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2392): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/PackageManager( 2392): [MSG] WRITE_PACKAGE_RESTRICTIONS
V/RouteController( 1915): RTNETLINK answers: No such file or directory
V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,I/jxcore-log( 7190): Connected to the server!
I/jxcore-log( 7190): 
,I/chromium( 7190): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/dalvikvm( 2392): GC_CONCURRENT freed 4440K, 72% free 25597K/88512K, paused 13ms+26ms, total 318ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 132ms
,D/dalvikvm( 2392): WAIT_FOR_CONCURRENT_GC blocked 212ms
,D/PackageManager( 2392): getApplicationInfo - Execution time: 230 ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): updateIfacesLocked()
,V/NetworkStats( 2392): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked() took 38ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
I/sCloudBackupApp( 7346): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7346): Other Intent
,I/ActivityManager( 2392): Killing 5572:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7375): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7375):  
,I/SELinux ( 7375): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7375):  
I/SELinux ( 7375):  
,I/SELinux ( 7375): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7375): >>>>> Normal User
,E/dalvikvm( 7375): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7375): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7375): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7375): Added TimaKesytore provider
,D/dalvikvm( 7375): GC_CONCURRENT freed 2990K, 30% free 9571K/13516K, paused 5ms+2ms, total 35ms
,D/dalvikvm( 7375): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7375): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7375): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7375): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7375): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5323): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2392): Killing 6287:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5856): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5856): getCountryCode(): countryCode = PL
,D/Headlines( 5856): Breath.onCreate
,D/Headlines( 5856): Breath timer started. interval : 30000
,I/SELinux ( 7387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7387):  
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5856): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5856): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5856): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2392): waitForAlarm result :8
,D/Tethering( 2392): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2392): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2392): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4723): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7387):  
I/SELinux ( 7387):  
,I/SELinux ( 7387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7387): >>>>> Normal User
,E/dalvikvm( 7387): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7387): in addTimaSignatureService
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7387): Added TimaKesytore provider
,D/dalvikvm( 7387): GC_FOR_ALLOC freed 3012K, 30% free 9555K/13520K, paused 24ms, total 24ms
,D/dalvikvm( 7387): GC_CONCURRENT freed 208K, 30% free 9566K/13520K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 7387): WAIT_FOR_CONCURRENT_GC blocked 16ms
,V/WebViewChromium( 7387): Binding Chromium to the background looper Looper (main, tid 1) {4223c4a0}
,I/chromium( 7387): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7387): Initializing chromium process, renderers=0
,W/chromium( 7387): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7387): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7387): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7387): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7387): Mali API Version : 401
,I/Mali    ( 7387): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7387): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7387): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7387): Starting up...,
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a090
,I/SELinux ( 7425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7425):  
,I/SELinux ( 7425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7425):  
I/SELinux ( 7425):  
,I/SELinux ( 7425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7425): >>>>> Normal User
,E/dalvikvm( 7425): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7425): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7425): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7425): Added TimaKesytore provider
,D/dalvikvm( 7425): GC_CONCURRENT freed 2974K, 30% free 9592K/13520K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7425): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection...
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,I/SELinux ( 7444): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7444):  
,W/ActivityManager( 2392): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,I/ActivityManager( 2392): Killing 6307:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7444): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7444):  
I/SELinux ( 7444):  
,I/SELinux ( 7444): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7444): >>>>> Normal User
,E/dalvikvm( 7444): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/SSRMv2:SIOP( 2392): SIOP:: AP = 320, Delta = 10
,I/SELinux ( 7454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7454):  
,D/TimaKeyStoreProvider( 7444): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7444): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7444): Added TimaKesytore provider
,I/ActivityManager( 2392): Killing 5969:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7454):  
I/SELinux ( 7454):  
,I/SELinux ( 7454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7454): >>>>> Normal User
,E/dalvikvm( 7454): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7454): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7454): Added TimaKesytore provider
,D/dalvikvm( 7444): GC_CONCURRENT freed 3002K, 30% free 9566K/13520K, paused 5ms+2ms, total 33ms
,D/dalvikvm( 7444): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/BadgeProvider( 7444): onCreate
,D/BadgeProvider( 7444): DatabaseHelper
,D/BadgeProvider( 7444): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2786): reloadBadges entered.
D/BadgeProvider( 7444): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7444): sendNotify, [notify] : null
D/BadgeProvider( 7444): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7444): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7444): update, [UpdateCount] : 1
,D/dalvikvm( 7454): GC_CONCURRENT freed 3006K, 30% free 9566K/13524K, paused 4ms+2ms, total 41ms
,D/dalvikvm( 7454): WAIT_FOR_CONCURRENT_GC blocked 36ms
,I/dalvikvm( 7190): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7190): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7190): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7190): Shutting down VM
,W/dalvikvm( 7190): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7190): FATAL EXCEPTION: main
E/AndroidRuntime( 7190): Process: com.test.thalitest, PID: 7190
E/AndroidRuntime( 7190): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7190): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7190): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7190): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7190): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7190): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7190): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 7190): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7190): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7190): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7190): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7190): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7190): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7190): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7190): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7190): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7190): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7190): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7190): 	at dalvik.system.NativeStart.main(Native Method)
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE
,W/ActivityManager( 2392):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2392): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2392): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2392): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2392): setHoveringSpenCustomIcon IconType is same.1
,D/CrashAnrDetector( 2392): processName: com.test.thalitest
,D/CrashAnrDetector( 2392): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/ActivityManager( 2392): Killing 6250:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/Process ( 7190): Sending signal. PID: 7190 SIG: 9
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 270188
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : true
D/CustomFrequencyManagerService( 2392): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2392): mDVFSHelper.acquire()
,E/SPPClientService( 5526): [[SystemStateMonitorService]] No Active Internet
,W/InputDispatcher( 2392): channel ~ Consumer closed input channel or an error occurred.  events=0x9
,E/InputDispatcher( 2392): channel ~ Channel is unrecoverably broken and will be disposed!
,W/InputDispatcher( 2392): Attempted to unregister already unregistered input channel
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
I/ActivityManager( 2392): Process com.test.thalitest (pid 7190) (adj 9) has died.
,I/WindowState( 2392): WIN DEATH: Window{444feba8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
I/DBG_DM  ( 4723): [3.19.140541][Line:408][onResume] 
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4723): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,I/DBG_DM  ( 4723): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4723): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4723): [3.19.140541][Line:418][onResume] Postpone Count : 28
,I/DBG_DM  ( 4723): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5526): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/DBG_DM  ( 4723): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,E/SPPClientService( 5526): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/DBG_DM  ( 4723): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2392): sendNotification(2) - 4
,I/DBG_DM  ( 4723): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
,I/DBG_DM  ( 4723): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
D/AmoledAdjustTimer( 2392): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/DBG_DM  ( 4723): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4723): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,D/checkbox( 4723): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4723): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/DBG_DM  ( 4723): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 1807 latestRequest time : 1452246697240 current time : 1452246699047
,D/Activity( 4723): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/StatusBarManagerService( 2392): semi p:4723,o:t
I/DBG_DM  ( 4723): [3.19.140541][Line:400][onPause] 
E/SPPClientService( 5526): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/PowerManagerService( 2392): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2392
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
D/STATUSBAR-StatusBarManagerService( 2392): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2392): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2392): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2392): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2392): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2392): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/SPPClientService( 5526): [g] getNetMCC return empty string
W/InputMethodManagerService( 2392): Got RemoteException sending setActive(false) notification to pid 7190 uid 10593
,D/CustomFrequencyManagerService( 2392): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2392): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2392): mDVFSHelper.release()
,I/KLMS-2.3.201 : ( 7301): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7301): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452246699257
,I/KLMS-2.3.201 : ( 7301): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 7280): Total arena pages for JIT: 11
,I/dalvikvm( 7280): Total arena pages for JIT: 12
I/dalvikvm( 7280): Total arena pages for JIT: 13
,I/dalvikvm( 7280): Total arena pages for JIT: 14
I/dalvikvm( 7280): Total arena pages for JIT: 15
,I/dalvikvm( 7280): Total arena pages for JIT: 16
,I/dalvikvm( 7280): Total arena pages for JIT: 17
,D/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3251): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7482): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7482):  
,I/GallerySearchProvider( 3379): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
I/SELinux ( 7482): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7482):  
I/SELinux ( 7482):  
,I/SELinux ( 7482): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7482): >>>>> Normal User
,E/dalvikvm( 7482): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7482): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,D/TimaKeyStoreProvider( 7482): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7482): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7482): Added TimaKesytore provider
,I/System.out( 7280): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7492): >>>>> Normal User
,E/dalvikvm( 7492): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/System.out( 7280): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7280): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,I/SA      ( 5792): [SCU] == networkStateCheck == true
I/SA      ( 5792): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5792): isChinaCountryCode : false
,I/SA      ( 5792): [OR] == networkStateCheck true ==
,I/SA      ( 5792): [OR] GetMyCountryZoneTask
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5792): [OR] onReceive END
D/ActivityThread( 7492): Added TimaKesytore provider
,I/SA      ( 5792): [SRS] prepareGetMyCountryZone
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [SSP] query invoked
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [TPM] isNoProxy(default) : true
,I/SA      ( 5792): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
D/dalvikvm( 7482): GC_CONCURRENT freed 2992K, 30% free 9577K/13524K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7482): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/SCloudBackupReceiver( 7346): Other Intent
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5856): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5856): getCountryCode(): countryCode = PL
D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5856): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5856): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5856): requestUpdateNewsWelcomeCard !!! no welcome card
D/dalvikvm( 7492): GC_CONCURRENT freed 2995K, 30% free 9567K/13516K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/System.out( 7280): AsyncTask #1 calls detatch()
,D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a090,
,V/KVNProvider( 7492): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7492): getFindoCursor query string : ,
D/RCPManagerService( 2392): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,W/System.err( 7280): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7280): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7280): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7280): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7280): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7280): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7280): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7280): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7280): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7280): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7280): Caused by: java.lang.NullPointerException
,W/System.err( 7280): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7280): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7280): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7280): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7280): 	... 8 more
,V/KVNProvider( 7492): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE
,I/ActivityManager( 2392): Killing 6145:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 271000
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : false
,E/WifiStateMachine( 2392): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 5526): GC_CONCURRENT freed 1996K, 23% free 10450K/13512K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 5526): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/CustomFrequencyManagerService( 2392): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2392  tag : ACTIVITY_RESUME_BOOSTER@8
,I/SA      ( 5792): [RC New] [v2liruge] api execute + 702
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5792): AsyncTask #2 calls detatch()
,I/SA      ( 5792): [TPMU] getNetworkMcc : 
,I/SA      ( 5792): [SCU] saveMccToPreferece Start
,I/SA      ( 5792): [SCU] RegionMCC : 260
,I/SA      ( 5792): [SSP] query invoked
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
,I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [SCU] saveMccToPreferece End
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] end. 735
,I/SA      ( 5792): [RC New] Execute end
I/SA      ( 5792): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5792): [OR] GetMyCountryZoneTask Success
,W/WifiP2pStateTracker( 2392): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2392): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2392):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2392): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2392): updateSourceRoutes : no source routing conditions
,E/SPPClientService( 5526): [b] __InitReply__
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
,I/ActivityManager( 2392): Killing 6184:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2392): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2392) eventTime = 273865
,D/PowerManagerService( 2392): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2392 (0x0)
,D/PowerManagerService( 2392): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2392, ws=WorkSource{1000}) (elapsedTime=3455)
,I/GAV2    ( 7387): Thread[GAThread,5,main]: No campaign data found.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6569): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6569): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6569): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6569): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6569): [ensureRegistration] - No Samsung account
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2392): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2392): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2392): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2392): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2392): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2392): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2392): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2392): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = -10,
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE,
,D/AmoledAdjustTimer( 2392): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE,
,I/ActivityManager( 2392): Waited long enough for: ServiceRecord{44c2bb10 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2392): Waited long enough for: ServiceRecord{431b7578 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 9,
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2392): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4,
,V/AlarmManager( 2392): waitForAlarm result :8,
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2392): [PWL] Off : 225s ago,
,V/AlarmManager( 2392): waitForAlarm result :8,
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5856): Breath 27735 latestRequest time : 1452246699528 current time : 1452246727263,
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2392): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2392): initializing...
,I/TLC_TIMA_PKM_initialize( 2392): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2392): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2392): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2392): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2392): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2392): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2392): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2392): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2392): device_id = 0x0
I/TZ: mc_tlc_communication( 2392): tlc_open() was called
,I/TZ: mc_tlc_communication( 2392): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2392): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2392): Opening the session
,I/TZ: mc_tlc_communication( 2392): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2392): Trustlet response is completed
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2392): !@Sync 10
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 57740 latestRequest time : 1452246699528 current time : 1452246757268
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2392): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2392): [PWL] Off : 275s ago
,E/Watchdog( 2392): !@Sync 11
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2392): waitForAlarm result :4
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7929): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7929):  
,I/SELinux ( 7929): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7929):  
I/SELinux ( 7929):  
,I/SELinux ( 7929): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7929): >>>>> Normal User
,E/dalvikvm( 7929): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7929): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7929): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7929): Added TimaKesytore provider
,D/dalvikvm( 7929): GC_CONCURRENT freed 3000K, 30% free 9569K/13520K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 7929): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2392): Killing 6513:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 87740 latestRequest time : 1452246699528 current time : 1452246787268
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 12
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :4
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5856): Breath 121135 latestRequest time : 1452246699528 current time : 1452246820663
,D/Headlines( 5856): stop 
,I/SELinux ( 8110): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8110):  
,D/Headlines( 5856): Breath.onDestroy : 
I/ActivityManager( 2392): Killing 6432:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 8110): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8110):  
I/SELinux ( 8110):  
,I/SELinux ( 8110): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8110): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8110): >>>>> Normal User
,E/dalvikvm( 8110): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8110): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8110): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8110): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8110): Added TimaKesytore provider
,D/dalvikvm( 8110): GC_CONCURRENT freed 3007K, 30% free 9556K/13520K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8110): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SPPClientService( 8110): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8110): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8110): PushLog.txt file is not deleted.
,D/SPPClientService( 8110): PushLog.txt file is not deleted.
,D/SPPClientService( 8110): ============PushLog. stop!
,I/ActivityManager( 2392): Killing 6543:com.samsung.groupcast/u0a15 (adj 15): empty #43
,E/SPPClientService( 5526): [b] __PingReply__
,I/PowerManagerService( 2392): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2392): !@Sync 13
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 14
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2392): !@Sync 15
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2581): GC_CONCURRENT freed 15713K, 33% free 33866K/50528K, paused 17ms+9ms, total 96ms
,D/dalvikvm( 2392): GC_CONCURRENT freed 4518K, 72% free 25061K/88512K, paused 9ms+18ms, total 222ms
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 16
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/dalvikvm( 6412): GC_CONCURRENT freed 2567K, 26% free 10084K/13600K, paused 4ms+3ms, total 52ms
D/dalvikvm( 6412): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 6412): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 6412): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/SELinux ( 8493): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8493):  
,I/SELinux ( 8493): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8493):  
I/SELinux ( 8493):  
,I/SELinux ( 8493): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8493): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8493): >>>>> Normal User
,E/dalvikvm( 8493): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 8493): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8493): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8493): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8493): Added TimaKesytore provider
,D/dalvikvm( 8493): GC_CONCURRENT freed 3001K, 30% free 9569K/13524K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 8493): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/UserAnalysis.PlaceProvider( 8493): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8493): Create SecureDbHelper
,I/ActivityManager( 2392): Killing 6556:com.android.musicfx/u0a24 (adj 15): empty #43
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2392): [PWL] Off : 455s ago
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4000): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2392): !@Sync 17
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841,
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8493): Create SecureDbHelper
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4000): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8493): Create SecureDbHelper
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4000): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 278, prevStep = 4, currStep = 4
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8493): Create SecureDbHelper
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 18
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4000): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value f8:95:c7:87:3c:51
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [f8:95:c7:87:3c:51]: 7, f, 6109
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/UserAnalysis.CarAnalyzer( 8493): Create SecureDbHelper
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value f8:95:c7:87:3c:51
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=F8:95:C7:87:3C:51, alias=null, name=G4-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: G4-1
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3980): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=0
I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 500000 usec
,I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 100000 usec,
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
D/WifiP2pService( 2392): InactiveState{ what=143375 }
D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2392): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2392): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2392): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2392): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2392): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3980): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService( 2392): Attempting to switch to mobile
D/ConnectivityService( 2392): Attempting to switch to BLUETOOTH_TETHER
,I/wpa_supplicant( 3980): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3980): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3980): Skip scan - already scanning
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,W/Settings( 2392): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2392): ignore requestNetworkTransitionWakelock airplane:true
,D/WifiP2pService( 2392): InactiveState{ what=143375 }
,D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2840): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2840): MountReceiver.mPrefHandler - 7002
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2392): route cmd failed: 
W/NetworkManagementService( 2392): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '57 route del src v6 2' failed with '400 57 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2392): '
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2392): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2392): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2392): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2392): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
E/WifiStateMachine( 2392): Error! unhandled message{ when=-66ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2392): Error! unhandled message{ when=-61ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2392): Error! unhandled message{ when=-11ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/NetUtils( 2392): android_net_utils_resetConnections in env=0x7466aca8 clazz=0x9e000001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2392): resetConnections(wlan0, 3)
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2840): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2840): MountReceiver.mPrefHandler - 7002
,E/SPPClientService( 5526): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5526): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5526): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5526): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5526): [b] ResponseMap empty
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): updateIfacesLocked()
,V/NetworkStats( 2392): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked() took 20ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,I/ApplicationPolicy( 2392): updateDataUsageMap
,D/Tethering( 2392): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2392): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2392): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2392): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4723): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): noConnectivity : true
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7301): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7301): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452247014036
,I/KLMS-2.3.201 : ( 7301): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
,I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
I/SA      ( 5792): [SCU] == networkStateCheck == false
,I/SA      ( 5792): [OR] onReceive END
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7346): Other Intent
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5856): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5856): getCountryCode(): countryCode = PL
,D/Headlines( 5856): Breath.onCreate
,D/Headlines( 5856): Breath timer started. interval : 30000
,V/AlarmManager( 2392): waitForAlarm result :8
D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5856): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5856): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5856): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.SyncManager( 5923): SYNC; picasa accounts
,D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a090
,I/iu.UploadsManager( 5923): num queued entries: 0
,I/iu.UploadsManager( 5923): num updated entries: 0
,I/iu.SyncManager( 5923): NEXT; no task
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,I/Babel   ( 5377): connection state changed from CONNECTED to DISCONNECTED
,I/iu.Environment( 3440): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/iu.UploadsManager( 3440): num queued entries: 0
,I/iu.UploadsManager( 3440): num updated entries: 0
,I/iu.SyncManager( 3440): NEXT; no task
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 585665
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : true
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,E/SPPClientService( 5526): [[SystemStateMonitorService]] No Active Internet
,D/Headlines( 5856): Breath 176 latestRequest time : 1452247014156 current time : 1452247014332
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection...
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/wpa_supplicant( 3980): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 3980): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3980): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3980): Associated with C0.AA.48
,I/wpa_supplicant( 3980): freq(2412) increment count 3
,I/wpa_supplicant( 3980): meet head of list.
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3980): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3980): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,D/Tethering( 2392): interfaceLinkStateChanged wlan0, true
,I/wpa_supplicant( 3980): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2392): interfaceStatusChanged wlan0, true
,D/WifiNative( 2392): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: OBTAINING_IPADDR
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2840): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2840): MountReceiver.mPrefHandler - 7002
,D/WifiP2pService( 2392): InactiveState{ what=143375 }
,D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/dhcpcd  ( 9027): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 9027): bssid match
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 19
,D/WifiP2pService( 2392): InactiveState{ what=143375 }
,D/WifiP2pService( 2392): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2392): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2392): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2392): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2392): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2392): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,I/WifiTrafficPoller( 2392): evaluateTrafficStatsPolling
D/ConnectivityService( 2392): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2392): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2392): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2392): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2840): DMSUtil.isNetworkConnected - flag-null, state-null
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2840): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2840): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/PowerManagerService( 2392): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2392
,D/NearbySettings( 2840): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,I/NearbySettings( 2840): MountReceiver.onReceive - Keep current state
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): updateIfacesLocked()
,V/NetworkStats( 2392): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked() took 32ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/Tethering( 2392): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2392): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2392): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/DBG_DM  ( 4723): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection...
,I/dalvikvm( 7280): Total arena pages for JIT: 18
,I/KLMS-2.3.201 : ( 7301): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/System.err( 7280): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7280): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7280): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7280): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7280): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7280): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7280): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7280): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7280): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7280): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7280): Caused by: java.lang.NullPointerException
,W/System.err( 7280): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7280): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7280): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7280): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7280): 	... 8 more
,D/dalvikvm( 7280): GC_CONCURRENT freed 2698K, 27% free 9957K/13596K, paused 4ms+4ms, total 48ms
,I/KLMS-2.3.201 : ( 7301): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452247019524
,I/KLMS-2.3.201 : ( 7301): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7315): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 3251): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3251): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3379): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,V/KVNProvider( 7492): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7492): getFindoCursor query string : 
,V/KVNProvider( 7492): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
I/SA      ( 5792): [SCU] == networkStateCheck == true
I/SA      ( 5792): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5792): isChinaCountryCode : false
,I/SA      ( 5792): [OR] == networkStateCheck true ==
,I/SA      ( 5792): [OR] GetMyCountryZoneTask
,I/SA      ( 5792): [OR] onReceive END
,I/SA      ( 5792): [SRS] prepareGetMyCountryZone
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [SSP] query invoked
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
,I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [TPM] isNoProxy(default) : true
,I/SA      ( 5792): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7346): Other Intent
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7375): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5856): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5856): getCountryCode(): countryCode = PL
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5856): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5856): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5856): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5856): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 5923): num queued entries: 0
,I/iu.UploadsManager( 5923): num updated entries: 0
,D/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5125): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5125): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a090
,I/iu.SyncManager( 5923): NEXT; no task
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/dalvikvm( 2723): GC_EXPLICIT freed 369K, 27% free 9978K/13508K, paused 13ms+11ms, total 103ms
,D/RCPManagerService( 2392): exchangeData() failure , invalid userId
,D/WaitQueueForNetworkActivate( 5944): notifyNetworkActivated
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE
,I/iu.Environment( 3440): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 3440): num queued entries: 0
,I/iu.UploadsManager( 3440): num updated entries: 0
,I/iu.SyncManager( 3440): NEXT; no task
,E/SPPClientService( 5526): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5526): [SystemStateMoniter] Current Time : 591252
,E/SPPClientService( 5526): [SystemStateMoniter] No Connect : false
,I/Babel   ( 5377): connection state changed from DISCONNECTED to CONNECTED
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/libgps  ( 2392): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SA      ( 5792): [RC New] [v2liruge] api execute + 659
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5792): AsyncTask #3 calls detatch()
,I/SA      ( 5792): [TPMU] getNetworkMcc : 
,I/SA      ( 5792): [SCU] saveMccToPreferece Start
,I/SA      ( 5792): [SCU] RegionMCC : 260
,I/SA      ( 5792): [SSP] query invoked
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
,I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [SCU] saveMccToPreferece End
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] end. 689
I/SA      ( 5792): [RC New] Execute end
I/SA      ( 5792): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5792): [OR] GetMyCountryZoneTask Success
,D/ConnectivityService( 2392): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/libgps  ( 2392): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2392): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2392): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2392): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11)
,D/PowerManagerService( 2392): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2392) eventTime = 593568
,D/PowerManagerService( 2392): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2392 (0x0)
,D/PowerManagerService( 2392): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2392, ws=WorkSource{1000}) (elapsedTime=3491)
,W/WifiP2pStateTracker( 2392): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2392): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2392):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2392): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2392): updateSourceRoutes : no source routing conditions
,E/SPPClientService( 5526): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/AlarmManager( 2392):  next == MAX_VALUE
,E/SPPClientService( 5526): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5526): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5526): [g] getNetMCC return empty string
,I/PowerManagerService( 2392): [PWL] Off : 525s ago
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6569): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6569): [hasSamungAccount] - No Samsung Account
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6569): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6569): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6569): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6569): sales region : global
,I/PCWCLIENTTRACE_PushUtil( 6569): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6569): [ensureRegistration] - No Samsung account
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5526): [b] __InitReply__
,I/ActivityManager( 2392): Waited long enough for: ServiceRecord{42c520b8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/CaptivePortalTracker( 2392): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2392): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/CaptivePortalTracker( 2392): Checking http://216.58.209.46/generate_204
D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/CaptivePortalTracker( 2392): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2392): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2392): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2392): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2392): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/GKI_LINUX( 4000): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4000): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/        ( 4000): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4000): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.NAME_CHANGED
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/ActivityManager( 2392): Waited long enough for: ServiceRecord{43346790 u0 com.sec.spp.push/.PushClientService}
,E/bt-btm  ( 4000): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4000): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4000): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4000): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4000): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2840): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2840): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6412): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6412): Bluetooth Device Name: HTC One M8s
,D/GKI_LINUX( 4000): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/BluetoothAdapterService(1109687288)( 4000): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/btif_config_util( 4000): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 24483 latestRequest time : 1452247019748 current time : 1452247044231
,D/dalvikvm( 2392): GC_CONCURRENT freed 3731K, 72% free 25120K/88512K, paused 12ms+21ms, total 269ms
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,W/ContextImpl( 2392): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 54431 latestRequest time : 1452247019748 current time : 1452247074180
,E/Watchdog( 2392): !@Sync 21
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/GAV2    ( 5614): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5614): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2392): waitForAlarm result :8
,D/LightsService( 2392): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2392): getReportingMode :: sensor.mType = 5
D/Sensors ( 2392): LightSensor setDelay = 200000000
D/Sensors ( 2392): LightSensor setSensorDelay = 200000000
D/Sensors ( 2392): Light sensor flush: not enabled 0
D/Sensors ( 2392): LightSensor enable = 1
D/Sensors ( 2392): LightSensor enableSensor = 1
D/SensorManager( 2392): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 84451 latestRequest time : 1452247019748 current time : 1452247104199
,D/LightsService( 2392): [SvcLED]  onSensorChanged::light value = 5
D/Sensors ( 2392): LightSensor enable = 0
D/Sensors ( 2392): LightSensor enableSensor = 0
,D/SensorManager( 2392): unregisterListener ::   
D/LightsService( 2392): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2392): !@Sync 22
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 114434 latestRequest time : 1452247019748 current time : 1452247134182
,E/Watchdog( 2392): !@Sync 23
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2392): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2392): <AppSync3 Whitelist>
,V/AlarmManager( 2392): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,D/Headlines( 5856): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5856): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5856): Breath 144440 latestRequest time : 1452247019748 current time : 1452247164188
,D/Headlines( 5856): stop 
,D/Headlines( 5856): Breath.onDestroy : 
,E/Watchdog( 2392): !@Sync 24
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 25
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2880K, 29% free 9726K/13556K, paused 8ms+2ms, total 51ms
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 26
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 27
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2392): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 28
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 29
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2392): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 855s ago
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 31
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 32
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 33
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/dalvikvm( 2392): GC_CONCURRENT freed 4055K, 72% free 24942K/88488K, paused 9ms+16ms, total 206ms
,I/PowerManagerService( 2392): [PWL] Off : 950s ago
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 34
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 35
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 36
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1050s ago
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 37
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2392): stay LED for fully charged
V/AlarmManager( 2392): waitForAlarm result :8
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 38
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 39
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :4
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5526): [b] __PingReply__
,D/dalvikvm( 5526): GC_CONCURRENT freed 1884K, 23% free 10502K/13512K, paused 5ms+6ms, total 47ms
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2392): !@Sync 40
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 41
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :8
,I/SensorManagerA( 2392): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2392): LightSensor setDelay = 200000000
,D/Sensors ( 2392): LightSensor setSensorDelay = 200000000
,D/LightsService( 2392): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2392): Light sensor flush: not enabled 0
D/Sensors ( 2392): LightSensor enable = 1
D/Sensors ( 2392): LightSensor enableSensor = 1
D/SensorManager( 2392): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2392): LightSensor enable = 0
,D/Sensors ( 2392): LightSensor enableSensor = 0
,D/SensorManager( 2392): unregisterListener ::   
D/LightsService( 2392): [SvcLED]  onSensorChanged::light value = 5
D/LightsService( 2392): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/Watchdog( 2392): !@Sync 42
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 272, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 43
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2392): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2392): <AppSync3 Whitelist>
,V/AlarmManager( 2392): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 272, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1265s ago
,E/Watchdog( 2392): !@Sync 44
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 45
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 46
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2392): !@Sync 47
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2392): GC_CONCURRENT freed 3806K, 72% free 24956K/88488K, paused 20ms+18ms, total 274ms
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 48
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2392): stay LED for fully charged
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 49
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2048K, 29% free 9723K/13556K, paused 3ms+12ms, total 67ms
,V/AlarmManager( 2392): waitForAlarm result :4
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3440): Aggregate from 1452246063857 (log), 1452246063857 (data)
,D/ConnectivityService( 2392): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :12
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5526): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,E/SPPClientService( 5526): [b] __PingReply__
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2392): !@Sync 50
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 51
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 271, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 271, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2392): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 52
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 53
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 54
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 55
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1625s ago
,E/Watchdog( 2392): !@Sync 56
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 57
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2392): !@Sync 58
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2392): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 59
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,D/TimaService( 2392): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2392): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2392): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/dalvikvm( 2392): GC_CONCURRENT freed 3737K, 72% free 25015K/88488K, paused 8ms+18ms, total 254ms
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2392): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2392): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2392): !@Sync 60
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,I/PowerManagerService( 2392): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 61
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2392): Prepared write state in 49ms
,I/ProcessStatsService( 2392): Prepared write state in 34ms
,I/ProcessStatsService( 2392): Pruning old procstats: /data/system/procstats/state-2016-01-07-10-43-12.bin
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,V/AlarmManager( 2392): waitForAlarm result :4
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked(flags=0x3)
,V/AlarmManager( 2392): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
V/NetworkStats( 2392): performPollLocked() took 44ms
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2392): currentTimeMillis() cache hit
,I/SELinux (12562): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12562):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9503K/10496K, paused 4ms+5ms, total 44ms
,I/SELinux (12562): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12562):  
I/SELinux (12562):  
,I/SELinux (12562): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12562): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12562): >>>>> Normal User
,E/dalvikvm(12562): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12562): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12562): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9503K/10496K, paused 3ms+4ms, total 38ms
,D/TimaKeyStoreProvider(12562): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12562): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9503K/10496K, paused 4ms+4ms, total 37ms
,D/dalvikvm(12562): GC_CONCURRENT freed 3015K, 30% free 9556K/13524K, paused 3ms+2ms, total 31ms
,D/dalvikvm(12562): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/@ WidgetProvider(12562): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12562): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12562): Widget random data : 10
,D/@ WidgetProvider(12562): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12562): Widget random data : 5
I/ActivityManager( 2392): Killing 6584:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,E/dalvikvm(12562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(12562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12562): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12562): VFY: replacing opcode 0x22 at 0x0038
,I/SensorManagerA( 2392): getReportingMode :: sensor.mType = 5
,D/LightsService( 2392): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2392): LightSensor setDelay = 200000000
D/Sensors ( 2392): LightSensor setSensorDelay = 200000000
E/dalvikvm(12562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12562): VFY: replacing opcode 0x22 at 0x0038
D/Sensors ( 2392): Light sensor flush: not enabled 0
E/dalvikvm(12562): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12562): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12562): VFY: replacing opcode 0x22 at 0x0038
D/Sensors ( 2392): LightSensor enable = 1
D/Sensors ( 2392): LightSensor enableSensor = 1
D/SensorManager( 2392): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/dalvikvm(12562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12562): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2855): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12562): Thread-672(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12562): Thread-672(ApacheHTTPLog):isShipBuild true
,I/System.out(12562): Thread-672(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2392): LightSensor enable = 0
,D/Sensors ( 2392): LightSensor enableSensor = 0
D/LightsService( 2392): [SvcLED]  onSensorChanged::light value = 6
,D/SensorManager( 2392): unregisterListener ::   
D/LightsService( 2392): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12562): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12562): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12562): Max ALLOWED memory (MB): 128
V/ImageManager(12562): Max SHOULD USE memory (MB): 128
,V/ImageManager(12562): Max Image Cache memory (MB): 32
,D/skia    (12562): getTotalSize : Do not get file length
,D/@ WidgetProvider(12562): Building widget : 5
,D/dalvikvm( 2786): GC_FOR_ALLOC freed 8510K, 34% free 18489K/27952K, paused 71ms, total 71ms
,E/Watchdog( 2392): !@Sync 62
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 270, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 270, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 63
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2392): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2392): <AppSync3 Whitelist>
,V/AlarmManager( 2392): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12694
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12696
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12697
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12699
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12701
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12702
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12704
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12706
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12707
,W/ProcessCpuTracker( 2392): Skipping unknown process pid 12708
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 64
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/BatteryService( 2392): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/BatteryService( 2392): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2392): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2392): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2392): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2392): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 65
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/ActivityManager( 2392): Killing 6426:com.sec.knox.bridge/1000 (adj 15): empty for 1820s
,I/ActivityManager( 2392): Killing 4847:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1820s
,I/ActivityManager( 2392): Killing 6388:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1829s
,I/ActivityManager( 2392): Killing 6732:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1830s
,I/ActivityManager( 2392): Killing 6717:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1831s
,I/ActivityManager( 2392): Killing 6705:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1831s
I/ActivityManager( 2392): Killing 6692:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1831s
,I/ActivityManager( 2392): Killing 6678:com.samsung.helphub/1000 (adj 15): empty for 1831s
,I/ActivityManager( 2392): Killing 6666:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1831s
,I/ActivityManager( 2392): Killing 6653:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1831s
,I/ActivityManager( 2392): Killing 6641:com.sec.android.service.cm/u0a82 (adj 15): empty for 1832s
,I/ActivityManager( 2392): Killing 6347:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1832s
,I/ActivityManager( 2392): Killing 5677:com.android.mms/u0a49 (adj 15): empty for 1832s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2392): Killing 6614:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1832s
,I/ActivityManager( 2392): Killing 5989:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1832s
,D/CountryDetector( 2392): No listener is left
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 66
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 67
,V/AlarmManager( 2392): waitForAlarm result :8
,V/AlarmManager( 2392): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 290, Delta = -10
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,E/Watchdog( 2392): !@Sync 68
,D/SSRMv2:SIOP( 2392): SIOP:: AP = 290, Delta = 0
,D/AmoledAdjustTimer( 2392): prevTemp = 269, currTemp = 269, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
