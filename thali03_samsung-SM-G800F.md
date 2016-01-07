#### Test 55311151a2306df_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7157): 
D/AndroidRuntime( 7157): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7157): CheckJNI is OFF
D/AndroidRuntime( 7157): setted country_code = Poland
D/AndroidRuntime( 7157): setted countryiso_code = PL
D/AndroidRuntime( 7157): setted sales_code = PLS
D/AndroidRuntime( 7157): readGMSProperty: start
D/AndroidRuntime( 7157): readGMSProperty: already setted!!
D/AndroidRuntime( 7157): readGMSProperty: end
D/AndroidRuntime( 7157): addProductProperty: start
D/dalvikvm( 7157): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7157): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7157): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7157): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7157): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1629832, pollInterval: 10000
E/memtrack( 7157): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7157): failed to load memtrack module: -2
D/dalvikvm( 7157): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7157): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SELinux ( 7171): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7171):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7157): Shutting down VM
D/dalvikvm( 7157): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7171): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7171):  
I/SELinux ( 7171):  
I/SELinux ( 7171): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7171): >>>>> Normal User
E/dalvikvm( 7171): >>>>> com.test.thalitest [ userId:0 | appId:10590 ]
E/SELinux ( 7171): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7171): in addTimaSignatureService
D/TimaKeyStoreProvider( 7171): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7171): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4188): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4188): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7171): GC_CONCURRENT freed 3005K, 32% free 9558K/13936K, paused 2ms+2ms, total 19ms
D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7171): Binding Chromium to the background looper Looper (main, tid 1) {422a7198}
I/chromium( 7171): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7171): Initializing chromium process, renderers=0
W/chromium( 7171): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7171): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7171): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7171): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7171): Mali API Version : 401
,I/Mali    ( 7171): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7171): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7171): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7171): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7171): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:7171,o:f
,W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7171): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7171): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7171): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7171): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7171): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7171): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7171): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7171): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7171): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:7171,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7171): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7171): Enabling debug mode 0
,W/AwContents( 7171): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/AwContents( 7171): nativeOnDraw failed; clearing to background color.
W/ActivityManager( 2422): mDVFSHelper.release()
,W/IInputConnectionWrapper( 7171): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7171): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7171): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a7f20
,D/dalvikvm( 7171): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a7f20
D/jxcore_app_log( 7171): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027641568
,D/JX-Cordova( 7171): jxcore cordova android initializing
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 7171): GC_CONCURRENT freed 1283K, 19% free 11335K/13984K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7171): GC_CONCURRENT freed 1874K, 18% free 14970K/18228K, paused 3ms+2ms, total 56ms
,D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 5453K, 31% free 16292K/23312K, paused 42ms, total 47ms
,D/dalvikvm( 7171): GC_CONCURRENT freed 6670K, 32% free 17738K/25852K, paused 3ms+12ms, total 79ms
,D/dalvikvm( 7171): WAIT_FOR_CONCURRENT_GC blocked 60ms
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 1474K, 33% free 17464K/25852K, paused 48ms, total 48ms
,I/dalvikvm-heap( 7171): Grow heap (frag case) to 21.928MB for 3713210-byte allocation
,D/dalvikvm( 7171): GC_FOR_ALLOC freed 2458K, 37% free 18631K/29480K, paused 45ms, total 45ms
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
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7171): Toggling radios to true
I/jxcore-log( 7171): 
,D/BluetoothAdapter( 7171): enable(): BT is already enabled..!
,I/WifiManager( 7171): packageName : com.test.thalitest
I/WifiManager( 7171): setWifiEnabled : true
,I/WifiService( 2422): setWifiEnabled: true pid=7171, uid=10590
,W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=7171, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7171, uid=10590 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2422): disconnect: pid=7171, uid=10590
I/jxcore-log( 7171): Radios toggled
I/jxcore-log( 7171): 
I/wpa_supplicant( 3972): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7171): Received device characteristics:
I/jxcore-log( 7171): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7171): Bluetooth name: S5mini-1
I/jxcore-log( 7171): Device name: samsung-SM-G800F
I/jxcore-log( 7171): 
,I/wpa_supplicant( 3972): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7171): Perf Test app loaded loaded
I/jxcore-log( 7171): 
,I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7171): check test folder
I/jxcore-log( 7171): 
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3972): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3972): wlan0: Setting scan request: 0 sec 0 usec,
I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=,
I/wpa_supplicant( 3972): First Scan Start
I/jxcore-log( 7171): found test : ./testFindPeers.js
I/jxcore-log( 7171): 
I/wpa_supplicant( 3972): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true,
D/WifiP2pService( 2422): InactiveState{ what=143375 },
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3972): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 3972): Skip scan - already scanning,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
D/ConnectivityService( 2422): Attempting to switch to mobile
,I/SELinux ( 7218): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7218):  
D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1,
,I/jxcore-log( 7171): found test : ./testSendData.js,
I/jxcore-log( 7171): 
,V/RouteController( 1916): RTNETLINK answers: No such process,
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory,
I/SELinux ( 7218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7218):  
I/SELinux ( 7218):  
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
I/SELinux ( 7218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7218): >>>>> Normal User
,E/dalvikvm( 7218): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2422): route cmd failed: 
W/NetworkManagementService( 2422): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2422): '
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2422): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2422): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2422): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2422): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2422): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2422): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-114ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-113ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7218): in addTimaSignatureService
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7218): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7218): Added TimaKesytore provider
,D/NetUtils( 2422): android_net_utils_resetConnections in env=0x7b89ce88 clazz=0x62000001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
,V/NativeCrypto( 2844): Read error: ssl=0x7bab0420: I/O error during system call, Connection timed out
,V/NativeCrypto( 2844): SSL shutdown failed: ssl=0x7bab0420: I/O error during system call, Broken pipe
,E/SPPClientService( 5536): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5536): [e] exceptionCaught(). NET_TIMEOUT
D/dalvikvm( 7218): GC_CONCURRENT freed 2985K, 32% free 9582K/13940K, paused 10ms+11ms, total 63ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 43ms
,E/SPPClientService( 5536): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5536): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5536): [b] ResponseMap empty
,I/chromium( 7171): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 7218): Inside WakeupProvider
,I/System.out( 7218): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2422): updateIfacesLocked()
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 28ms
,I/VlingoApplication( 7218): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7218): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7218): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2839): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2839): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2422): Killing 6172:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7218): initQueue()
,D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2839): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2839): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2422): updateDataUsageMap
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/DBG_DM  ( 4737): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): noConnectivity : true
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7247): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7247):  
,I/wpa_supplicant( 3972): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 3972): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3972): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/SELinux ( 7247): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7247):  
I/SELinux ( 7247):  
,I/SELinux ( 7247): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7247): >>>>> Normal User
,E/dalvikvm( 7247): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7247): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7247): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7247): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7247): Added TimaKesytore provider
,I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3972): Associated with C0.AA.48
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3972): freq(2412) increment count 2
,I/wpa_supplicant( 3972): meet head of list.
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm( 7247): GC_CONCURRENT freed 2989K, 32% free 9577K/13936K, paused 4ms+3ms, total 32ms
,D/dalvikvm( 7247): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3972): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3972): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3972): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/WifiNative( 2422): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2422): Killing 6242:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,I/SELinux ( 7261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7261):  
,I/SELinux ( 7261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7261):  
I/SELinux ( 7261):  
,I/SELinux ( 7261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7261): >>>>> Normal User
,E/dalvikvm( 7261): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7261): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7261): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7261): Added TimaKesytore provider
,D/dalvikvm( 7261): GC_CONCURRENT freed 2993K, 32% free 9575K/13936K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7261): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/dhcpcd  ( 7273): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7273): bssid match
,I/ActivityManager( 2422): Killing 6304:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7280): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7280):  
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
I/SELinux ( 7280): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7280):  
I/SELinux ( 7280):  
I/SELinux ( 7280): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7280): >>>>> Normal User
,E/dalvikvm( 7280): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
E/SELinux ( 7280): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/TimaKeyStoreProvider( 7280): in addTimaSignatureService
D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaKeyStoreProvider( 7280): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7280): Added TimaKesytore provider
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7280): GC_CONCURRENT freed 2996K, 32% free 9564K/13932K, paused 4ms+2ms, total 34ms
,D/dalvikvm( 7280): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/KLMS-2.3.201 : ( 7280): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7280): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452156114650
,I/KLMS-2.3.201 : ( 7280): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2422): Killing 6340:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7293): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7293):  
,I/SELinux ( 7293): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7293):  
I/SELinux ( 7293):  
,I/SELinux ( 7293): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7293): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7293): >>>>> Normal User
,E/dalvikvm( 7293): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7293): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7293): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7293): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7293): Added TimaKesytore provider
,D/dalvikvm( 7293): GC_CONCURRENT freed 3000K, 32% free 9564K/13932K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7293): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7293): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7293): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5804): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5804): [BDLM] already registered in spp
,I/SA      ( 5804): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5804): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5804): [OR] == isSIMCardReady false ==
I/SA      ( 5804): [SCU] == networkStateCheck == false
,I/SA      ( 5804): [OR] onReceive END
I/ActivityManager( 2422): Killing 5588:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7305): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7305):  
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1619821, pollInterval: 10000,
,I/SELinux ( 7305): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7305):  
,I/SELinux ( 7305):  
,I/SELinux ( 7305): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7305): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7305): >>>>> Normal User
,E/dalvikvm( 7305): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 13% free 9501K/10912K, paused 5ms+5ms, total 57ms
,E/SELinux ( 7305): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7305): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7305): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7305): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10912K, paused 3ms+5ms, total 37ms
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10912K, paused 3ms+4ms, total 37ms
,D/dalvikvm( 7305): GC_CONCURRENT freed 2997K, 32% free 9569K/13936K, paused 5ms+3ms, total 39ms
,D/dalvikvm( 7305): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/sCloudBackupApp( 7305): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7305): Other Intent
I/ActivityManager( 2422): Killing 6299:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7318): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7318):  
,I/SELinux ( 7318): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7318):  
I/SELinux ( 7318):  
,I/SELinux ( 7318): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7318): >>>>> Normal User
,E/dalvikvm( 7318): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7318): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7318): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7318): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7318): Added TimaKesytore provider
,D/dalvikvm( 7318): GC_CONCURRENT freed 2983K, 32% free 9576K/13932K, paused 4ms+3ms, total 43ms
,D/dalvikvm( 7318): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7318): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7318): [KK AccuPhone]>>> RM:136 [0:0]  V init 
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/daemonapp( 5336): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7318): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5336): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7318): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5336): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 2422): Killing 6315:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/Headlines( 5871): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5871): getCountryCode(): countryCode = PL
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2422): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/Headlines( 5871): Breath.onCreate
,D/Headlines( 5871): Breath timer started. interval : 30000
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2422): CaptivePortalCheckState enter
,I/SELinux ( 7351): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7351):  
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling,
,V/AlarmManager( 2422): waitForAlarm result :8,
D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5871): queryCategory.  mRequest is not initialized.,
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5871): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5871): requestUpdateNewsWelcomeCard !!! no welcome card
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,E/Watchdog( 2422): !@Sync 9,
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/SELinux ( 7351): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7351):  
I/SELinux ( 7351):  
,I/SELinux ( 7351): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7351): >>>>> Normal User
,E/dalvikvm( 7351): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,D/TimaKeyStoreProvider( 7351): in addTimaSignatureService
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7351): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7351): Added TimaKesytore provider
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2422): updateIfacesLocked()
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 25ms
,D/dalvikvm( 7351): GC_CONCURRENT freed 2994K, 32% free 9571K/13936K, paused 4ms+2ms, total 43ms
,D/dalvikvm( 7351): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/WebViewChromium( 7351): Binding Chromium to the background looper Looper (main, tid 1) {422a42e0}
,I/chromium( 7351): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7351): Initializing chromium process, renderers=0
,W/chromium( 7351): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7351): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7351): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7351): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7351): Mali API Version : 401
,I/Mali    ( 7351): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/GAV2    ( 7351): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7351): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 10
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
,D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/NSApplication( 7351): Starting up...
,I/DBG_DM  ( 4737): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,D/QuickConnect[1.1][2] ( 5139): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5139): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5139): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6930
,I/SELinux ( 7404): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7404):  
,I/jxcore-log( 7171): Connected to the server!
I/jxcore-log( 7171): 
,I/chromium( 7171): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/SELinux ( 7404): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7404):  
I/SELinux ( 7404):  
,I/SELinux ( 7404): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7404): >>>>> Normal User
,E/dalvikvm( 7404): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7404): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7404): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7404): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7404): Added TimaKesytore provider
,D/dalvikvm( 7404): GC_CONCURRENT freed 2980K, 32% free 9584K/13936K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7404): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/SELinux ( 7423): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7423):  
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2422): Killing 5985:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7423): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7423):  
I/SELinux ( 7423):  
,I/SELinux ( 7423): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7423): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7423): >>>>> Normal User
,E/dalvikvm( 7423): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7423): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7423): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7423): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7423): Added TimaKesytore provider
,I/SELinux ( 7436): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7436):  
,I/ActivityManager( 2422): Killing 6261:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/SELinux ( 7436): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7436):  
I/SELinux ( 7436):  
,I/SELinux ( 7436): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7436): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7436): >>>>> Normal User
,E/dalvikvm( 7436): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7436): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7436): in addTimaSignatureService
D/dalvikvm( 7423): GC_CONCURRENT freed 3012K, 32% free 9554K/13936K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7423): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/TimaKeyStoreProvider( 7436): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7436): Added TimaKesytore provider
,D/BadgeProvider( 7423): onCreate
,D/BadgeProvider( 7423): DatabaseHelper
,D/BadgeProvider( 7423): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2771): reloadBadges entered.
D/BadgeProvider( 7423): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7423): sendNotify, [notify] : null
D/BadgeProvider( 7423): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7423): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7423): update, [UpdateCount] : 1
,D/dalvikvm( 7436): GC_CONCURRENT freed 3006K, 32% free 9558K/13936K, paused 3ms+2ms, total 37ms
,D/dalvikvm( 7436): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/dalvikvm( 7171): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7171): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7171): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7171): Shutting down VM
,W/dalvikvm( 7171): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7171): FATAL EXCEPTION: main
E/AndroidRuntime( 7171): Process: com.test.thalitest, PID: 7171
E/AndroidRuntime( 7171): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7171): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7171): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7171): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7171): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7171): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7171): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 7171): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7171): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7171): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7171): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7171): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7171): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7171): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7171): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7171): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7171): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7171): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7171): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2422):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2422): Killing 6159:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/Process ( 7171): Sending signal. PID: 7171 SIG: 9
,D/CrashAnrDetector( 2422): processName: com.test.thalitest
,D/CrashAnrDetector( 2422): broadcastEvent : com.test.thalitest data_app_crash
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/DBG_DM  ( 4737): [3.19.140541][Line:408][onResume] 
,D/hcjo    ( 5957): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5957): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5957): exit::IDLE
,D/InitializeManagerStateMachine( 5957): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5957): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5957): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5957): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): entry::SUCCESS
,D/hcjo    ( 5957): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
I/WindowState( 2422): WIN DEATH: Window{43028788 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager( 2422): Process com.test.thalitest (pid 7171) (adj 9) has died.
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
I/DBG_DM  ( 4737): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5957): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5957): exit::SUCCESS
D/InitializeManagerStateMachine( 5957): entry::IDLE
,I/DBG_DM  ( 4737): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
,I/DBG_DM  ( 4737): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4737): [3.19.140541][Line:418][onResume] Postpone Count : 28
E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 290244
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : true
,I/DBG_DM  ( 4737): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,E/SPPClientService( 5536): [[SystemStateMonitorService]] No Active Internet,
,D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2839): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2839): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4737): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2839): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4737): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,I/DBG_DM  ( 4737): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
,E/SPPClientService( 5536): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
I/DBG_DM  ( 4737): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2839): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2839): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2839): MountReceiver.onReceive - Keep current state
,I/DBG_DM  ( 4737): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4737): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4737): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4737): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,E/SPPClientService( 5536): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/DBG_DM  ( 4737): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4737): setTransGradationMode to true
,D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:4737,o:t
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/DBG_DM  ( 4737): [3.19.140541][Line:400][onPause] 
D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5871): Breath 1946 latestRequest time : 1452156115821 current time : 1452156117767
,I/SurfaceFlinger( 1922): id=20 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1922): id=21 createSurf (1x1),1 flag=4, Uoast
D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/NearbySettings( 2839): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2839): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 7171 uid 10590
,E/SPPClientService( 5536): [g] getNetMCC return empty string
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/KLMS-2.3.201 : ( 7280): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7280): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452156118039
,I/KLMS-2.3.201 : ( 7280): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,I/dalvikvm( 7261): Total arena pages for JIT: 11
,I/dalvikvm( 7261): Total arena pages for JIT: 12
I/dalvikvm( 7261): Total arena pages for JIT: 13
,I/dalvikvm( 7261): Total arena pages for JIT: 14
,I/dalvikvm( 7261): Total arena pages for JIT: 15
I/dalvikvm( 7261): Total arena pages for JIT: 16
,I/dalvikvm( 7261): Total arena pages for JIT: 17
,I/LocationTagReadyService( 3250): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 7293): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7293): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7461):  
,I/GallerySearchProvider( 3378): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7461):  
I/SELinux ( 7461):  
,I/SELinux ( 7461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7461): >>>>> Normal User
,E/dalvikvm( 7461): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5804): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5804): [BDLM] already registered in spp
,I/SELinux ( 7473): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7473):  
,D/TimaKeyStoreProvider( 7461): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7461): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7461): Added TimaKesytore provider
,I/SA      ( 5804): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5804): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5804): [OR] == isSIMCardReady false ==
,I/SA      ( 5804): [SCU] == networkStateCheck == true
I/SA      ( 5804): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5804): isChinaCountryCode : false
,I/SA      ( 5804): [OR] == networkStateCheck true ==
,I/SA      ( 5804): [OR] GetMyCountryZoneTask
,I/SA      ( 5804): [OR] onReceive END
,I/SA      ( 5804): [SRS] prepareGetMyCountryZone,
I/SELinux ( 7473): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7473):  
I/SELinux ( 7473):  
I/SELinux ( 7473): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 7473): >>>>> Normal User
,E/dalvikvm( 7473): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,E/SELinux ( 7473): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5804): [SSP] query invoked,
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive,
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled,
I/SA      ( 5804): [TPMU] GetMccFromDB : null
I/SA      ( 5804): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5804): [TPM] isNoProxy(default) : true
,I/SA      ( 5804): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 7305): Other Intent
,D/TimaKeyStoreProvider( 7473): in addTimaSignatureService,
D/dalvikvm( 7461): GC_CONCURRENT freed 2985K, 32% free 9583K/13940K, paused 5ms+1ms, total 27ms
,D/dalvikvm( 7461): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/TimaKeyStoreProvider( 7473): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7473): Added TimaKesytore provider,
D/com.samsung.app( 7318): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7318): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5871): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5871): getCountryCode(): countryCode = PL
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5871): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5871): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5871): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 7261): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7261): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7261): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7473): GC_CONCURRENT freed 3002K, 32% free 9569K/13940K, paused 4ms+1ms, total 23ms
,D/dalvikvm( 7473): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2422): GC_EXPLICIT freed 4180K, 74% free 25145K/96576K, paused 12ms+23ms, total 259ms
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/KVNProvider( 7473): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7473): getFindoCursor query string : 
,D/QuickConnect[1.1][2] ( 5139): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5139): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5139): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b6930
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,V/KVNProvider( 7473): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5957): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5957): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5957): exit::IDLE
,D/InitializeManagerStateMachine( 5957): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5957): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5957): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): entry::SUCCESS
,D/hcjo    ( 5957): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5957): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5957): exit::SUCCESS
,D/InitializeManagerStateMachine( 5957): entry::IDLE
,E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 291074
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : false
,I/System.out( 7261): AsyncTask #1 calls detatch()
,W/System.err( 7261): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7261): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7261): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7261): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7261): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7261): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7261): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7261): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7261): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7261): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7261): Caused by: java.lang.NullPointerException
W/System.err( 7261): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7261): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7261): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7261): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7261): 	... 8 more
,I/ActivityManager( 2422): Killing 6195:com.google.android.music:main/u0a125 (adj 15): empty #43,
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,D/dalvikvm( 5536): GC_CONCURRENT freed 1922K, 25% free 10486K/13928K, paused 3ms+5ms, total 35ms,
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8,
,I/SA      ( 5804): [RC New] [v2liruge] api execute + 687,
I/SA      ( 5804): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5804): AsyncTask #2 calls detatch()
,I/SA      ( 5804): [TPMU] getNetworkMcc : 
,I/SA      ( 5804): [SCU] saveMccToPreferece Start
,I/SA      ( 5804): [SCU] RegionMCC : 260
,I/SA      ( 5804): [SSP] query invoked
,I/SA      ( 5804): [TPMU] GetMccFromDB : null
I/SA      ( 5804): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5804): [SCU] saveMccToPreferece End
I/SA      ( 5804): [RC New] executeRequest [v2liruge] end. 720
,I/SA      ( 5804): [RC New] Execute end
I/SA      ( 5804): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5804): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,E/SPPClientService( 5536): [b] __InitReply__
,I/PowerManagerService( 2422): [PWL] Off : 225s ago,
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=21 Removed Uoast (-2/11)
I/ActivityManager( 2422): Killing 6523:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 293908
,D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
,I/GAV2    ( 7351): Thread[GAThread,5,main]: No campaign data found.
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3495)
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6582): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6582): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6582): GetString : secure API is not supported!!,
I/PCWCLIENTTRACE_PushUtil( 6582): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6582): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6582): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6582): [ensureRegistration] - No Samsung account,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609808, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204,
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4,
,D/PreloadUpdateManagerStateMachine( 5957): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5957): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5957): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5957): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5957): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5957): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 5957): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5957): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5957): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5957): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5957): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5957): entry::IDLE,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{43041cc8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{4492ac60 u0 com.sec.spp.push/.PushClientService},
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599795, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4,
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2422): initializing...,
I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): device_id = 0x0
,I/TZ: mc_tlc_communication( 2422): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2422): Opening the session
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589777, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,E/Watchdog( 2422): !@Sync 10
D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5871): Breath 27507 latestRequest time : 1452156118329 current time : 1452156145836
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579764, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569752, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 275s ago,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559739, pollInterval: 10000,
,E/Watchdog( 2422): !@Sync 11
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7834): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7834):  
,I/SELinux ( 7834): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7834):  
I/SELinux ( 7834):  
,I/SELinux ( 7834): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7834): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7834): >>>>> Normal User
,E/dalvikvm( 7834): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7834): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7834): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7834): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7834): Added TimaKesytore provider
,D/dalvikvm( 7834): GC_FOR_ALLOC freed 3017K, 32% free 9550K/13936K, paused 25ms, total 25ms
,D/dalvikvm( 7834): GC_CONCURRENT freed 240K, 17% free 9553K/11420K, paused 2ms+3ms, total 24ms
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5871): Breath 62912 latestRequest time : 1452156118329 current time : 1452156181242
,I/ActivityManager( 2422): Killing 6443:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549724, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539710, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529696, pollInterval: 10000,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
E/Watchdog( 2422): !@Sync 12
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5871): Breath 87521 latestRequest time : 1452156118329 current time : 1452156205850,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519684, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509679, pollInterval: 10000,
,I/PowerManagerService( 2422): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499668, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,E/Watchdog( 2422): !@Sync 13,
D/Headlines( 5871): Breath 117521 latestRequest time : 1452156118329 current time : 1452156235850
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489658, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate,
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3997): Disconnected process message: 10,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479630, pollInterval: 10000,
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469618, pollInterval: 10000,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5871): Breath 147517 latestRequest time : 1452156118329 current time : 1452156265846
,D/Headlines( 5871): stop ,
E/Watchdog( 2422): !@Sync 14
,D/Headlines( 5871): Breath.onDestroy : ,
I/ActivityManager( 2422): Killing 6552:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459603, pollInterval: 10000,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449587, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439575, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 15
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429561, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419547, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409534, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 16
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399520, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389506, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3997): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,I/PowerManagerService( 2422): [PWL] Off : 455s ago
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/dalvikvm( 6423): GC_CONCURRENT freed 2526K, 28% free 10116K/14008K, paused 7ms+4ms, total 72ms
,D/dalvikvm( 6423): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 6423): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379492, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 17
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 280, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,I/SELinux ( 8271): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8271):  
,I/SELinux ( 8271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8271):  
I/SELinux ( 8271):  
,I/SELinux ( 8271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8271): >>>>> Normal User
,E/dalvikvm( 8271): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8271): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/TimaKeyStoreProvider( 8271): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8271): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8271): Added TimaKesytore provider
,D/dalvikvm( 8271): GC_CONCURRENT freed 2996K, 32% free 9568K/13936K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8271): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/UserAnalysis.PlaceProvider( 8271): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,I/ActivityManager( 2422): Killing 6566:com.android.musicfx/u0a24 (adj 15): empty #43
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2582): GC_CONCURRENT freed 15743K, 34% free 33859K/50968K, paused 18ms+13ms, total 121ms
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369482, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77,
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359472, pollInterval: 10000
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349458, pollInterval: 10000
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,E/Watchdog( 2422): !@Sync 18
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [90:e7:c4:f6:69:77]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339450, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 90:e7:c4:f6:69:77
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=90:E7:C4:F6:69:77, alias=null, name=HTC One M8s, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: HTC One M8s
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,E/BluetoothRemoteDevices( 3997): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b4ac rs_disc_pending=0
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329439, pollInterval: 10000
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [08:ec:a9:50:76:27]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 3997): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3924K, 75% free 25071K/96576K, paused 20ms+24ms, total 269ms
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [e0:db:10:14:e2:c0]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319427, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 19
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [08:ec:a9:50:76:27]: 0, 0, 0
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b4ac rs_disc_pending=1
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b668 rs_disc_pending=0
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2422): [PWL] Off : 525s ago
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309413, pollInterval: 10000
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b4ac rs_disc_pending=0
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299402, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [e0:db:10:14:e2:c0]: 7, f, 2205
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b4ac rs_disc_pending=0
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value e0:db:10:14:e2:c0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=E0:DB:10:14:E2:C0, alias=null, name=Note4-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Note4-1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289393, pollInterval: 10000
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2422): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279382, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 0
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 0:0
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/GKI_LINUX( 3997): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 3997): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 08:ec:a9:50:76:27
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/        ( 3997): remote version info [08:ec:a9:50:76:27]: 7, f, 2205
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/UserAnalysis.CarAnalyzer( 8271): Create SecureDbHelper
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,E/bt-btm  ( 3997): tBTM_SEC_DEV:0x77d9b668 rs_disc_pending=0
,E/bt-btm  ( 3997): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 3997): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 3997): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 08:ec:a9:50:76:27
D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_LMP_VER, value 7:8709
,D/IOP_DB_BT( 3997): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 3997): db_query_execute: result 1
,D/KeyguardViewMediator( 2582): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2582): isGear1: device is not B1!
,V/BluetoothEventManager( 2839): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2839): ACTION_ACL_DISCONNECTED
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269341, pollInterval: 10000
,I/BluetoothConnectionReceiver( 6423): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=08:EC:A9:50:76:27, alias=null, name=Thali Test (Galaxy A3), majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6423): Bluetooth Device Name: Thali Test (Galaxy A3)
,D/GKI_LINUX( 3997): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/BluetoothAdapterService(1110064736)( 3997): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/btif_config_util( 3997): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259321, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 21
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249307, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239293, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,I/GAV2    ( 5631): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5631): Thread[disconnect check,5,main]: Disconnected from service
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229277, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 22
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219263, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209250, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1199237, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 23
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1189222, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1179212, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1169196, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 24
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1159183, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1149172, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1139159, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 25
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4058): GC_CONCURRENT freed 2878K, 31% free 9724K/13972K, paused 6ms+3ms, total 66ms
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1129145, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1119131, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1109122, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 26
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1099108, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2422): LightSensor enable = 0
D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 4
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1089094, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1079082, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 27
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1069072, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1059058, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1049045, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1039031, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1029020, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1019005, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 29
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1008992, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 998982, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 988967, pollInterval: 10000
,E/Watchdog( 2422): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 978953, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 968942, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 958928, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 4031K, 75% free 24881K/96576K, paused 17ms+17ms, total 220ms
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 948915, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 938877, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 32
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 928866, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 918853, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 908839, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 898825, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 888813, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 878799, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 34
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 868784, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 858770, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 848756, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 35
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 838743, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 828729, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 818715, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 36
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 808702, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 798692, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SPPClientService( 5536): [b] __PingReply__
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 788682, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 37
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 778669, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 768655, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 758642, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 38
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 748632, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 738622, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 728612, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 39
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 718602, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 708592, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 698582, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2422): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 688572, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 678562, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 668552, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 658542, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2771): GC_CONCURRENT freed 7131K, 40% free 18940K/31220K, paused 11ms+7ms, total 97ms
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 648532, pollInterval: 10000
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 638522, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 42
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 628512, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 618502, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 608488, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 43
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 598475, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 588462, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 578452, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1265s ago
,E/Watchdog( 2422): !@Sync 44
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 568442, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 558431, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 548422, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 45
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 538412, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 528402, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3803K, 75% free 24858K/96576K, paused 21ms+16ms, total 266ms
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 518392, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 46
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 508382, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 498372, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :4
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
,D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
,D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3440): Aggregate from 1452155319569 (log), 1452155319569 (data)
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 2
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 488362, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 47
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 478352, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 468342, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1380s ago
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 458332, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 48
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 448322, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 438312, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 428302, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 49
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 418292, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4058): GC_CONCURRENT freed 2048K, 31% free 9721K/13972K, paused 9ms+2ms, total 50ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 408282, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 398272, pollInterval: 10000
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 388262, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 378248, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 368237, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 51
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 358227, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 348217, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1500s ago
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 338206, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 52
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 328197, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 318187, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 308172, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 53
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 298161, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 288152, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 278141, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 54
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 268132, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 258122, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 248112, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 55
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 238102, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 228092, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 218082, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1625s ago
,E/Watchdog( 2422): !@Sync 56
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 208071, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 198062, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 188052, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 57
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 178041, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 168027, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 158013, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 58
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 148000, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 137985, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 127970, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 59
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 117957, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 107943, pollInterval: 10000
,D/dalvikvm( 2422): GC_CONCURRENT freed 3704K, 75% free 24947K/96576K, paused 13ms+19ms, total 235ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 11662
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 97929, pollInterval: 10000
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 87915, pollInterval: 10000
,I/PowerManagerService( 2422): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 77902, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 67889, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 61
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 57875, pollInterval: 10000
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2422): Prepared write state in 43ms
,I/ProcessStatsService( 2422): Prepared write state in 47ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 47860, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 37846, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 62
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 27833, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 17818, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 7804, pollInterval: 10000
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 63
,D/Finsky  ( 3701): [1] ExperimentsChangeHandler$2.run: Exiting process because of stale process stable experiments
,I/AndroidRuntime( 3701): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager( 2422): Process com.android.vending (pid 3701) (adj 15) has died.
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 64
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 65
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
I/ActivityManager( 2422): Killing 6438:com.sec.knox.bridge/1000 (adj 15): empty for 1817s
,I/ActivityManager( 2422): Killing 4860:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1817s
,I/ActivityManager( 2422): Killing 6400:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1826s
,I/ActivityManager( 2422): Killing 6740:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1827s
,I/ActivityManager( 2422): Killing 6726:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1828s
,I/ActivityManager( 2422): Killing 6714:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1828s
,I/ActivityManager( 2422): Killing 6702:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1828s
I/ActivityManager( 2422): Killing 6689:com.samsung.helphub/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2422): Killing 6676:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1828s
,I/ActivityManager( 2422): Killing 6664:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1828s
,I/ActivityManager( 2422): Killing 6649:com.sec.android.service.cm/u0a82 (adj 15): empty for 1829s
I/ActivityManager( 2422): Killing 6358:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1829s
,I/ActivityManager( 2422): Killing 5695:com.android.mms/u0a49 (adj 15): empty for 1829s
,I/ActivityManager( 2422): Killing 6624:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1829s
,I/ActivityManager( 2422): Killing 6001:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1829s
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2422): Killing 6594:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1830s
,D/CountryDetector( 2422): No listener is left
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 66
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/NetworkStats( 2422): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked() took 44ms
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/SELinux (12205): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12205):  
,I/SELinux (12205): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12205):  
I/SELinux (12205):  
,I/SELinux (12205): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12205): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12205): >>>>> Normal User
,E/dalvikvm(12205): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
E/SELinux (12205): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12205): in addTimaSignatureService
,D/TimaKeyStoreProvider(12205): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12205): Added TimaKesytore provider
,D/dalvikvm(12205): GC_CONCURRENT freed 3011K, 32% free 9554K/13936K, paused 2ms+1ms, total 24ms
,D/dalvikvm(12205): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/@ WidgetProvider(12205): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12205): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12205): Widget random data : 10
,D/@ WidgetProvider(12205): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12205): Widget random data : 7
E/dalvikvm(12205): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12205): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12205): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12205): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12205): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12205): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12205): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12205): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12205): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12205): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12205): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12205): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12205): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12205): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12205): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12205): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
,D/Sensors ( 2422): LightSensor enableSensor = 1
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2844): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2844): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/NativeCrypto( 2844): SSL shutdown failed: ssl=0x745f6f68: I/O error during system call, Connection timed out
,I/System.out(12205): Thread-669(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12205): Thread-669(ApacheHTTPLog):isShipBuild true
,I/System.out(12205): Thread-669(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 3
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12205): AsyncNetworking-1-thread-1 calls detatch()
,D/dalvikvm( 2844): GC_CONCURRENT freed 1921K, 24% free 10891K/14252K, paused 11ms+5ms, total 78ms
,I/System.out(12205): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12205): Max ALLOWED memory (MB): 128
V/ImageManager(12205): Max SHOULD USE memory (MB): 128
,V/ImageManager(12205): Max Image Cache memory (MB): 32
,D/skia    (12205): getTotalSize : Do not get file length
,D/@ WidgetProvider(12205): Building widget : 5
,I/PhenotypeConfigurator( 2736): Scheduling Phenotype for one-off execution 2218 seconds from now (1452157840834)
,D/dalvikvm( 2736): GC_CONCURRENT freed 1762K, 22% free 11779K/14984K, paused 10ms+7ms, total 84ms
,D/dalvikvm( 2736): WAIT_FOR_CONCURRENT_GC blocked 47ms
,D/GetConfigurationSnapshotOperation( 2736): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 2736): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,W/dalvikvm( 2736): VFY: unable to find class referenced in signature (Landroid/net/Network;)
,I/dalvikvm( 2736): Could not find method android.net.Network.openConnection, referenced from method com.google.android.gms.http.g.a
W/dalvikvm( 2736): VFY: unable to resolve virtual method 1007: Landroid/net/Network;.openConnection (Ljava/net/URL;)Ljava/net/URLConnection;
,D/dalvikvm( 2736): VFY: replacing opcode 0x6e at 0x00bb
,I/GoogleURLConnFactory( 2736): Using platform SSLCertificateSocketFactory
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 2736): Thread-124(HTTPLog):isShipBuild true
,I/System.out( 2736): Thread-124(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/dalvikvm( 2736): GC_CONCURRENT freed 1636K, 21% free 12113K/15184K, paused 6ms+10ms, total 66ms
,D/LocationManagerService( 2422): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 67
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 68
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
V/HeadsetService( 3997): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3997): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),E/Watchdog( 2422): !@Sync 69
D/AndroidRuntime(12442): 
D/AndroidRuntime(12442): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12442): CheckJNI is OFF
D/AndroidRuntime(12442): setted country_code = Poland
D/AndroidRuntime(12442): setted countryiso_code = PL
D/AndroidRuntime(12442): setted sales_code = PLS
D/AndroidRuntime(12442): readGMSProperty: start
D/AndroidRuntime(12442): readGMSProperty: already setted!!
D/AndroidRuntime(12442): readGMSProperty: end
D/AndroidRuntime(12442): addProductProperty: start
D/dalvikvm(12442): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12442): Added shared lib libjavacore.so 0x0
D/dalvikvm(12442): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12442): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12442): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12442): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12442): failed to load memtrack module: -2
D/dalvikvm(12442): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
V/AlarmManager( 2422): waitForAlarm result :8
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
I/ActivityManager( 2422): Killing 7305:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1801s
I/ActivityManager( 2422): Killing 7461:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1801s
I/ActivityManager( 2422): Killing 5804:com.osp.app.signin/u0a44 (adj 15): empty for 1801s
I/ActivityManager( 2422): Killing 6608:com.policydm/1000 (adj 15): empty for 1801s
I/ActivityManager( 2422): Killing 7293:com.sec.android.soagent/u0a38 (adj 15): empty for 1801s
I/ActivityManager( 2422): Killing 7280:com.samsung.klmsagent/u0a18 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 7261:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 5746:com.sec.android.diagmonagent/1000 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 7247:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 6582:com.sec.pcw.device/1000 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 2839:com.android.settings/1000 (adj 15): empty for 1802s
I/ActivityManager( 2422): Killing 7423:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1802s
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/AndroidRuntime(12442): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2422): START PACKAGE DELETE: observer{1125155696}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2422): !@killApplicatoin: 10590, uninstall pkg
D/dalvikvm( 2422): GC_CONCURRENT freed 3894K, 75% free 24937K/96576K, paused 8ms+17ms, total 182ms
D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 161ms
W/PackageSettings( 2422): Skipping PackageSetting{42d3c7c8 com.example.hello/10580} due to missing metadata
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10590, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10590, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
E/SamsungIME( 2990): mOCRHelper is null
I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
D/QuickConnect[1.1][2] ( 5139): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
I/SELinux (12471): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12471):  
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 6423): GC_EXPLICIT freed 861K, 29% free 9950K/14000K, paused 6ms+68ms, total 194ms
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9501K/10912K, paused 3ms+4ms, total 44ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12471): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12471):  
I/SELinux (12471):  
I/SELinux (12471): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/dalvikvm( 2973): GC_EXPLICIT freed 1465K, 28% free 10034K/13932K, paused 12ms+49ms, total 206ms
E/SELinux (12471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12471): >>>>> Normal User
E/dalvikvm(12471): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12471): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10912K, paused 3ms+4ms, total 35ms
D/RegisteredServicesCache( 2759): empty dynamic service
D/TimaKeyStoreProvider(12471): in addTimaSignatureService
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12471): Cannot add TimaSignature Service, License check Failed
D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9501K/10912K, paused 3ms+4ms, total 34ms
D/ActivityThread(12471): Added TimaKesytore provider
D/dalvikvm( 3440): GC_EXPLICIT freed 1770K, 21% free 12587K/15776K, paused 11ms+16ms, total 315ms
W/SQLiteConnectionPool( 3440): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2422): PackageReceiver onReceive()
I/HarmonyEASService( 2422): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12471): GC_CONCURRENT freed 2998K, 32% free 9571K/13936K, paused 3ms+2ms, total 34ms
D/dalvikvm(12471): WAIT_FOR_CONCURRENT_GC blocked 24ms
D/elm:14132(12471): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(12471): ELMEngine.ELMEngine( context ).
D/elm:14132(12471): MDMBridge.setEnterpriseBridge()
D/elm:14132(12471): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(12471): ElmAgentService : onCreate()
D/elm:14132(12471): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12471): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12471): MDMBridge.getInstance()
D/elm:14132(12471): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(12471): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12484): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12484):  
D/elm:14132(12471): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(12471): ElmAgentService : onDestroy().
I/ActivityManager( 2422): Killing 7318:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1802s
I/SELinux (12484): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12484):  
I/SELinux (12484):  
I/SELinux (12484): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12484): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12484): >>>>> Normal User
E/dalvikvm(12484): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12484): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12484): in addTimaSignatureService
D/TimaKeyStoreProvider(12484): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12484): Added TimaKesytore provider
D/EnterpriseDeviceManagerService( 2422): Package has changed for user 0
D/dalvikvm( 2422): GC_EXPLICIT freed 1808K, 75% free 24896K/96576K, paused 14ms+27ms, total 591ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2422): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2422): removePackageParticipantsLocked: uid=10590 #1
D/dalvikvm(12484): GC_CONCURRENT freed 2990K, 32% free 9578K/13940K, paused 8ms+2ms, total 56ms
D/dalvikvm(12484): WAIT_FOR_CONCURRENT_GC blocked 42ms
D/PackageManager( 2422): delete sourFile : 
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/PackageManager( 2422): delete native library directory: 
D/PackageManager( 2422): return delete result to caller: 1125155696
D/PackageManager( 2422): returnCode: 1
D/AndroidRuntime(12442): Shutting down VM
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12442): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 5ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12501): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12501):  
I/ActivityManager( 2422): Killing 7473:com.sec.android.app.voicenote/1000 (adj 15): empty for 1803s
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (12501): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12501):  
I/SELinux (12501):  
I/SELinux (12501): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12501): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12501): >>>>> Normal User
E/dalvikvm(12501): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12501): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12501): in addTimaSignatureService
D/TimaKeyStoreProvider(12501): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12501): Added TimaKesytore provider
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12501): GC_CONCURRENT freed 2994K, 32% free 9567K/13932K, paused 13ms+2ms, total 45ms
D/dalvikvm(12501): WAIT_FOR_CONCURRENT_GC blocked 30ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SQLiteDatabase(12501): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase(12501): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12501): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase(12501): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase(12501): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(12501): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(12501): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(12501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12501): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12501): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12501): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12501): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12501): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12501): Shutting down VM
W/dalvikvm(12501): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/AndroidRuntime(12501): FATAL EXCEPTION: main
E/AndroidRuntime(12501): Process: com.sec.android.app.mss, PID: 12501
E/AndroidRuntime(12501): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12501): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime(12501): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime(12501): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime(12501): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12501): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12501): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12501): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12501): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12501): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12501): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12501): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12501): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12501): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12501): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12501): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12501): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime(12501): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime(12501): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime(12501): 	... 10 more
I/SELinux (12515): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12515):  
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2422): Killing 7351:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1803s
I/Process (12501): Sending signal. PID: 12501 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
W/ApplicationsProvider( 2973): Could not fetch usage stats
W/ApplicationsProvider( 2973): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2973): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2973): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2973): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2973): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2973): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2973): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2973): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 2422): Process com.sec.android.app.mss (pid 12501) (adj 9) has died.
I/EsApplication( 5935): Trimming memory (onTrimMemory 40)
V/SamsungIME( 2990): onTrimMeomory Level = 5
D/HeadlinesChannelApplication( 5871): HeadlinesChannelApplication.onTrimMemory(). level : 60
I/SELinux (12515): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12515):  
I/SELinux (12515):  
I/SELinux (12515): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12515): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12515): >>>>> Normal User
E/dalvikvm(12515): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/SELinux (12515): [DEBUG] seapp_context_lookup: seinfoCategory = release
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/GeoLookout( 3086): at (DisasterAlertApplication.java:67) [onTrimMemory()]
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/rsC++   ( 2771): RS Message thread exiting.
D/TimaKeyStoreProvider(12515): in addTimaSignatureService
E/OpenGLRenderer( 2771): SFEffectCache:clear(), mSize = 0
D/Launcher( 2771): onTrimMemory. Level: 80
D/TimaKeyStoreProvider(12515): Cannot add TimaSignature Service, License check Failed
W/ManagedEGLContext( 2771): doTerminate failed: EGL count is 2 but managed count is 1
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ActivityThread(12515): Added TimaKesytore provider
I/CrashAnrDetector( 2422): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2422): clearDefaults: com.test.thalitest
W/AtomicFile( 2422): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2422): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/dalvikvm(12515): GC_CONCURRENT freed 2998K, 32% free 9565K/13936K, paused 3ms+2ms, total 25ms
D/dalvikvm(12515): WAIT_FOR_CONCURRENT_GC blocked 21ms
I/SELinux (12529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12529):  
I/SELinux (12529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12529):  
I/SELinux (12529):  
I/SELinux (12529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12529): >>>>> Normal User
E/dalvikvm(12529): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (12529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12529): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(12529): in addTimaSignatureService
D/TimaKeyStoreProvider(12529): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12529): Added TimaKesytore provider
D/dalvikvm(12529): GC_CONCURRENT freed 3007K, 32% free 9559K/13936K, paused 3ms+2ms, total 25ms
D/dalvikvm(12529): WAIT_FOR_CONCURRENT_GC blocked 21ms
E/SQLiteDatabase(12529): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12529): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12529): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12529): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12529): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12529): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12529): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12529): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12529): Shutting down VM
W/dalvikvm(12529): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12529): FATAL EXCEPTION: main
E/AndroidRuntime(12529): Process: com.sec.pcw.device, PID: 12529
E/AndroidRuntime(12529): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12529): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12529): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12529): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12529): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12529): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12529): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12529): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12529): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12529): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12529): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12529): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12529): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12529): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12529): 	... 12 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
I/SELinux (12543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12543):  
I/Process (12529): Sending signal. PID: 12529 SIG: 9
I/ActivityManager( 2422): Process com.sec.pcw.device (pid 12529) (adj 0) has died.
I/SELinux (12543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12543):  
I/SELinux (12543):  
I/SELinux (12543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12543): >>>>> Normal User
E/dalvikvm(12543): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12543): in addTimaSignatureService
D/TimaKeyStoreProvider(12543): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12543): Added TimaKesytore provider
D/dalvikvm(12543): GC_CONCURRENT freed 2999K, 32% free 9568K/13936K, paused 3ms+2ms, total 26ms
D/dalvikvm(12543): WAIT_FOR_CONCURRENT_GC blocked 13ms
W/System.err(12543): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12543): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12543): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12543): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12543): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12543): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12543): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12543): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12543): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12543): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12543): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12543): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12543): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12543): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12543): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12543): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12543): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12543): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12543): 	at libcore.io.Posix.open(Native Method)
W/System.err(12543): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12543): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12543): 	... 21 more
D/GalaxyFinderApplication(12543): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12543): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12557): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12557):  
I/ActivityManager( 2422): Killing 5935:com.google.android.apps.plus/u0a133 (adj 15): empty for 1804s
I/SELinux (12557): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12557):  
I/SELinux (12557):  
I/SELinux (12557): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12557): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12557): >>>>> Normal User
E/dalvikvm(12557): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12557): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12557): in addTimaSignatureService
D/TimaKeyStoreProvider(12557): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12557): Added TimaKesytore provider
D/dalvikvm(12557): GC_CONCURRENT freed 3010K, 32% free 9560K/13940K, paused 3ms+2ms, total 25ms
D/dalvikvm(12557): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 10
D/AmoledAdjustTimer( 2422): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
W/ContextImpl(12557): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12557): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12557): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12557): ContentProvider is not null
W/ResourceType(12557): No package identifier when getting value for resource number 0x00000000
I/System.out(12557): resource Id::2131361807
E/SQLiteDatabase(12557): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12557): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12557): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12557): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12557): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12557): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12557): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12557): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12557): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12557): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12557): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12557): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12557): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12557): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12557): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12557): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12557): Shutting down VM
W/dalvikvm(12557): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12557): FATAL EXCEPTION: main
E/AndroidRuntime(12557): Process: com.sec.android.app.shealth, PID: 12557
E/AndroidRuntime(12557): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12557): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12557): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12557): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12557): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12557): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12557): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12557): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12557): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12557): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12557): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12557): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12557): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12557): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12557): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12557): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12557): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12557): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12557): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12557): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12557): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12557): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12557): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12557): 	at com.sec.android.app.shealth.framework.app.AppRegistryDb
```
