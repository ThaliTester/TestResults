#### Test 50650278b28a87a_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
--------- beginning of /dev/log/main
D/AndroidRuntime( 7294): 
D/AndroidRuntime( 7294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7294): CheckJNI is OFF
D/AndroidRuntime( 7294): setted country_code = Poland
D/AndroidRuntime( 7294): setted countryiso_code = PL
D/AndroidRuntime( 7294): setted sales_code = PLS
D/AndroidRuntime( 7294): readGMSProperty: start
D/AndroidRuntime( 7294): readGMSProperty: already setted!!
D/AndroidRuntime( 7294): readGMSProperty: end
D/AndroidRuntime( 7294): addProductProperty: start
D/dalvikvm( 7294): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7294): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7294): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7294): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7294): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7294): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7294): failed to load memtrack module: -2
D/dalvikvm( 7294): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7294): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2408): mDVFSHelper.acquire()
I/SELinux ( 7321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7321):  
D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7294): Shutting down VM
D/dalvikvm( 7294): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7321):  
I/SELinux ( 7321):  
I/SELinux ( 7321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7321): >>>>> Normal User
E/dalvikvm( 7321): >>>>> com.test.thalitest [ userId:0 | appId:10521 ]
E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7321): in addTimaSignatureService
D/TimaKeyStoreProvider( 7321): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7321): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4168): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4168): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7321): GC_CONCURRENT freed 2994K, 30% free 9566K/13504K, paused 3ms+2ms, total 19ms
D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 13ms
V/WebViewChromium( 7321): Binding Chromium to the background looper Looper (main, tid 1) {4223f410}
I/chromium( 7321): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7321): Initializing chromium process, renderers=0
W/chromium( 7321): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7321): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7321): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7321): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7321): Mali API Version : 401
,I/Mali    ( 7321): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7321): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7321): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7321): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7321): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2408): tr p:7321,o:f
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7321): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7321): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7321): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7321): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7321): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7321): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7321): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7321): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): semi p:7321,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2408): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2408): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2408): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2408): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2408): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7321): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7321): Enabling debug mode 0
,W/AwContents( 7321): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2408): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2408): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 7321): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7321): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7321): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7321): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422401b8
,D/dalvikvm( 7321): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422401b8
,D/jxcore_app_log( 7321): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030882888
,D/JX-Cordova( 7321): jxcore cordova android initializing
,I/dalvikvm( 7321): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 7321): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0045
,D/dalvikvm( 7321): GC_CONCURRENT freed 1311K, 17% free 11328K/13576K, paused 1ms+2ms, total 24ms
D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 7321): GC_CONCURRENT freed 1899K, 17% free 14920K/17772K, paused 1ms+3ms, total 42ms
D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/CustomFrequencyManagerService( 2408): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2408  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7321): GC_FOR_ALLOC freed 5401K, 29% free 16220K/22748K, paused 49ms, total 49ms
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7321): GC_CONCURRENT freed 6712K, 31% free 17680K/25352K, paused 2ms+13ms, total 85ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 61ms
,D/dalvikvm( 7321): GC_FOR_ALLOC freed 1416K, 32% free 17421K/25352K, paused 49ms, total 50ms
,I/dalvikvm-heap( 7321): Grow heap (frag case) to 21.466MB for 3713210-byte allocation
,D/dalvikvm( 7321): GC_FOR_ALLOC freed 2459K, 36% free 18587K/28980K, paused 50ms, total 50ms
,W/jxcore-log( 7321): Initializing JXcore engine
,W/jxcore-log( 7321): JXcore engine is ready
,W/jxcore-log( 7321): Starting JXcore engine
,W/jxcore-log( 7321): Platform android
W/jxcore-log( 7321): 
,W/jxcore-log( 7321): Process ARCH arm
W/jxcore-log( 7321): 
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 10
,I/jxcore-log( 7321): JXcore Cordova bridge is ready!
I/jxcore-log( 7321): 
,W/jxcore-log( 7321): JXcore engine is started
,I/chromium( 7321): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/jxcore-log( 7321): Toggling radios to true
I/jxcore-log( 7321): 
,D/BluetoothAdapter( 7321): enable(): BT is already enabled..!
,I/WifiManager( 7321): packageName : com.test.thalitest
,I/WifiManager( 7321): setWifiEnabled : true
,I/WifiService( 2408): setWifiEnabled: true pid=7321, uid=10521
,W/ActivityManager( 2408): Permission Denial: getCurrentUser() from pid=7321, uid=10521 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): Failed getting userId using ActivityManagerNative
W/WifiService( 2408): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7321, uid=10521 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2408): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2408): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2408): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2408): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2408): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2408): disconnect: pid=7321, uid=10521
I/wpa_supplicant( 3966): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7321): Radios toggled
I/jxcore-log( 7321): 
,I/jxcore-log( 7321): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7321): 
,I/jxcore-log( 7321): Perf Test app loaded loaded
I/jxcore-log( 7321): 
,I/wpa_supplicant( 3966): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,I/jxcore-log( 7321): check test folder
I/jxcore-log( 7321): 
,I/jxcore-log( 7321): found test : ./testFindPeers.js
I/jxcore-log( 7321): 
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3966): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3966): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3966): First Scan Start
,I/wpa_supplicant( 3966): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2408): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2408): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2408): InactiveState{ what=143375 }
D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
D/ConnectivityService( 2408): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3966): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3966): Skip scan - already scanning
D/ConnectivityService( 2408): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2408): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2408): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2408): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2408): Attempting to switch to mobile
,D/ConnectivityService( 2408): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7369): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7369):  
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,I/jxcore-log( 7321): found test : ./testSendData.js
I/jxcore-log( 7321): 
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-53ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-52ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2408): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,I/SELinux ( 7369): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7369):  
I/SELinux ( 7369):  
,I/SELinux ( 7369): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7369): >>>>> Normal User
,E/dalvikvm( 7369): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2408): route cmd failed: 
W/NetworkManagementService( 2408): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2408): '
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2408): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2408): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2408): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2408): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7369): in addTimaSignatureService
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7369): Cannot add TimaSignature Service, License check Failed
,D/NetUtils( 2408): android_net_utils_resetConnections in env=0x77edea18 clazz=0x62600001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2408): resetConnections(wlan0, 3)
D/ActivityThread( 7369): Added TimaKesytore provider
,V/NativeCrypto( 2848): Read error: ssl=0x7b9d1478: I/O error during system call, Connection timed out
,E/SPPClientService( 5586): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7b9d1478: I/O error during system call, Broken pipe
,D/dalvikvm( 7369): GC_CONCURRENT freed 2990K, 30% free 9580K/13508K, paused 4ms+2ms, total 29ms
D/dalvikvm( 7369): WAIT_FOR_CONCURRENT_GC blocked 18ms
,E/SPPClientService( 5586): [e] exceptionCaught(). NET_TIMEOUT
,I/chromium( 7321): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5586): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5586): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5586): [b] ResponseMap empty
,I/System.out( 7369): Inside WakeupProvider
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,I/System.out( 7369): Inside onCreate() of WakeupTriggerProvide
D/ConnectivityService( 2408): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2408): updateIfacesLocked()
,V/NetworkStats( 2408): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 28ms
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,I/VlingoApplication( 7369): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7369): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7369): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4749): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4749): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4749): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2408): Killing 6217:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7369): initQueue()
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4749): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4749): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4749): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2408): updateDataUsageMap
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2408): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2408): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6629): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6629): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6629): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6629): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6629): noConnectivity : true
,I/DBG_DM  ( 4787): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7398): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7398):  
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7398): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7398):  
I/SELinux ( 7398):  
I/SELinux ( 7398): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/wpa_supplicant( 3966): nl80211: Received scan results (5 BSSes)
I/wpa_supplicant( 3966): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3966): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
E/SELinux ( 7398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7398): >>>>> Normal User
,E/dalvikvm( 7398): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7398): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7398): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7398): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7398): Added TimaKesytore provider
,D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3966): Associated with C0.AA.48
I/wpa_supplicant( 3966): freq(2412) increment count 2
,I/wpa_supplicant( 3966): meet head of list.
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3966): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3966): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3966): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2408): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2408): interfaceStatusChanged wlan0, true
,D/WifiNative( 2408): callSECApiVoid - ID [50]
,D/dalvikvm( 7398): GC_CONCURRENT freed 3001K, 30% free 9568K/13512K, paused 5ms+2ms, total 36ms
,D/dalvikvm( 7398): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2408): Killing 6286:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,I/SELinux ( 7412): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7412):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9503K/10488K, paused 4ms+5ms, total 49ms
,I/SELinux ( 7412): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7412):  
I/SELinux ( 7412):  
,I/SELinux ( 7412): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7412): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7412): >>>>> Normal User
,E/dalvikvm( 7412): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7412): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10488K, paused 3ms+4ms, total 39ms
,D/TimaKeyStoreProvider( 7412): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7412): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7412): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10488K, paused 3ms+5ms, total 40ms
,D/dalvikvm( 7412): GC_CONCURRENT freed 3005K, 30% free 9566K/13512K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7412): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/dhcpcd  ( 7424): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7424): bssid match
,I/ActivityManager( 2408): Killing 6342:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7431):  
,I/SELinux ( 7431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7431):  
I/SELinux ( 7431):  
,I/SELinux ( 7431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7431): >>>>> Normal User
,E/dalvikvm( 7431): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7431): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7431): Added TimaKesytore provider
,D/dalvikvm( 7431): GC_CONCURRENT freed 3014K, 30% free 9559K/13512K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7431): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/KLMS-2.3.201 : ( 7431): KLMSValidator() : checkQATesting()
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7431): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449671446183
,I/KLMS-2.3.201 : ( 7431): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2408): Killing 6360:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7443): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7443):  
,I/SELinux ( 7443): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7443):  
I/SELinux ( 7443):  
,I/SELinux ( 7443): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7443): >>>>> Normal User
,E/dalvikvm( 7443): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7443): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7443): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7443): Added TimaKesytore provider
,D/dalvikvm( 2408): GC_CONCURRENT freed 4276K, 74% free 25592K/95360K, paused 11ms+26ms, total 308ms
,D/dalvikvm( 7443): GC_CONCURRENT freed 2993K, 30% free 9566K/13504K, paused 5ms+2ms, total 36ms
,D/dalvikvm( 7443): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/SO_AGENT( 7443): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7443): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5850): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5850): [BDLM] already registered in spp
,I/SA      ( 5850): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5850): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5850): [OR] == isSIMCardReady false ==
,I/SA      ( 5850): [SCU] == networkStateCheck == false
,I/SA      ( 5850): [OR] onReceive END
I/ActivityManager( 2408): Killing 6369:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SELinux ( 7455): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7455):  
,I/SELinux ( 7455): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7455):  
I/SELinux ( 7455):  
,I/SELinux ( 7455): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7455): >>>>> Normal User
,E/dalvikvm( 7455): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7455): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7455): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7455): Added TimaKesytore provider
,D/dalvikvm( 7455): GC_CONCURRENT freed 2998K, 30% free 9571K/13512K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7455): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/PackageManager( 2408): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/sCloudBackupApp( 7455): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7455): Other Intent
I/ActivityManager( 2408): Killing 5635:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7468): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7468):  
,I/SELinux ( 7468): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7468):  
I/SELinux ( 7468):  
,I/SELinux ( 7468): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7468): >>>>> Normal User
,E/dalvikvm( 7468): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7468): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7468): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7468): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7468): Added TimaKesytore provider
,D/dalvikvm( 7468): GC_CONCURRENT freed 3002K, 30% free 9564K/13508K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7468): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7468): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7468): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7468): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7468): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2408): Killing 6322:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5913): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5913): getCountryCode(): countryCode = PL
,D/Headlines( 5913): Breath.onCreate
,D/Headlines( 5913): Breath timer started. interval : 30000
,I/SELinux ( 7498): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7498):  
,V/AlarmManager( 2408): waitForAlarm result :8
D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5913): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5913): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5913): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7498): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7498):  
I/SELinux ( 7498):  
,I/SELinux ( 7498): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7498): >>>>> Normal User
,E/dalvikvm( 7498): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7498): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7498): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7498): Added TimaKesytore provider
,D/WifiP2pService( 2408): InactiveState{ what=143375 }
,D/WifiP2pService( 2408): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2408): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2408): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2408): CaptivePortalCheckState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2408): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2408): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
D/dalvikvm( 7498): GC_CONCURRENT freed 3005K, 30% free 9565K/13508K, paused 3ms+2ms, total 40ms
,D/dalvikvm( 7498): WAIT_FOR_CONCURRENT_GC blocked 34ms
D/ConnectivityService( 2408): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2408): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2408): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/WebViewChromium( 7498): Binding Chromium to the background looper Looper (main, tid 1) {4223c110}
,I/chromium( 7498): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7498): Initializing chromium process, renderers=0
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2408): updateIfacesLocked()
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,V/NetworkStats( 2408): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
W/chromium( 7498): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/libEGL  ( 7498): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7498): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 28ms
,D/libEGL  ( 7498): loaded /system/lib/egl/libGLESv2_mali.so
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,I/Mali    ( 7498): Mali API Version : 401
,I/Mali    ( 7498): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7498): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7498): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7498): Starting up...
,I/iu.Environment( 5981): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5181): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5181): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,I/SELinux ( 7554): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7554):  
,I/SELinux ( 7554): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7554):  
I/SELinux ( 7554):  
,I/SELinux ( 7554): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7554): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7554): >>>>> Normal User
,E/dalvikvm( 7554): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7554): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7554): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7554): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7554): Added TimaKesytore provider
,D/Tethering( 2408): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2408): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2408): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4787): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7554): GC_CONCURRENT freed 2985K, 30% free 9582K/13504K, paused 4ms+3ms, total 35ms
,D/dalvikvm( 7554): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,I/SELinux ( 7572): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7572):  
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,W/ActivityManager( 2408): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2408): exchangeData() failure , invalid userId
I/SELinux ( 7572): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7572):  
I/SELinux ( 7572):  
I/SELinux ( 7572): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7572): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7572): >>>>> Normal User
E/dalvikvm( 7572): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7572): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2408): Killing 6390:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7572): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7572): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7572): Added TimaKesytore provider
,I/SELinux ( 7586): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7586):  
,I/ActivityManager( 2408): Killing 6029:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7586): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7586):  
I/SELinux ( 7586):  
,I/SELinux ( 7586): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7586): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7586): >>>>> Normal User
,E/dalvikvm( 7586): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7586): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/jxcore-log( 7321): Connected to the server!
I/jxcore-log( 7321): 
,D/TimaKeyStoreProvider( 7586): in addTimaSignatureService
D/dalvikvm( 7572): GC_CONCURRENT freed 2988K, 30% free 9576K/13508K, paused 8ms+2ms, total 39ms
,D/dalvikvm( 7572): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaKeyStoreProvider( 7586): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7586): Added TimaKesytore provider
,D/BadgeProvider( 7572): onCreate
,D/BadgeProvider( 7572): DatabaseHelper
,I/chromium( 7321): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,D/BadgeProvider( 7572): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2772): reloadBadges entered.
,D/BadgeProvider( 7572): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7572): sendNotify, [notify] : null
D/BadgeProvider( 7572): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7572): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7572): update, [UpdateCount] : 1
,D/dalvikvm( 7586): GC_CONCURRENT freed 2993K, 30% free 9576K/13512K, paused 5ms+2ms, total 32ms
,D/dalvikvm( 7586): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/hcjo    ( 6002): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6002): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6002): exit::IDLE
,D/InitializeManagerStateMachine( 6002): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6002): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6002): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6002): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6002): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6002): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6002): entry::SUCCESS
,D/hcjo    ( 6002): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6002): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6002): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6002): exit::SUCCESS
,D/InitializeManagerStateMachine( 6002): entry::IDLE
,I/jxcore-log( 7321): BLE advertisement not supported: Build version is 19
I/jxcore-log( 7321): 
,E/SPPClientService( 5586): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5586): [SystemStateMoniter] Current Time : 276619
,E/SPPClientService( 5586): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5586): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4749): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4749): MountReceiver.onReceive - Keep current state
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5913): Breath 1752 latestRequest time : 1449671447298 current time : 1449671449050
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4749): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2408): Killing 6204:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5586): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4749): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4749): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4749): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5586): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408
,D/NearbySettings( 4749): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4749): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5586): [a] [ConnectionManager] Connection is already disconnected.
,D/libgps  ( 2408): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection...
I/PCWCLIENTTRACE_PushUtil( 6629): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6629): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6629): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6629): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): stay LED for fully charged
,E/SPPClientService( 5586): [g] getNetMCC return empty string
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/KLMS-2.3.201 : ( 7431): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/WifiP2pStateTracker( 2408): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2408): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2408):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2408): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2408): updateSourceRoutes : no source routing conditions
,I/KLMS-2.3.201 : ( 7431): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1449671449614
,I/KLMS-2.3.201 : ( 7431): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7443): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3421): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3421): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3421): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3421): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7443): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3549): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7619): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7619):  
,I/SELinux ( 7623): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7623):  
,I/SELinux ( 7619): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7619):  
I/SELinux ( 7619):  
,I/SELinux ( 7619): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7619): >>>>> Normal User
,E/dalvikvm( 7619): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7619): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7623): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7623):  
I/SELinux ( 7623):  
,I/SELinux ( 7623): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7623): >>>>> Normal User
,E/dalvikvm( 7623): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7623): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7619): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7619): Cannot add TimaSignature Service, License check Failed
,D/TimaKeyStoreProvider( 7623): in addTimaSignatureService
,D/ActivityThread( 7619): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7623): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5850): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,D/ActivityThread( 7623): Added TimaKesytore provider
,I/SA      ( 5850): [BDLM] already registered in spp
,I/SA      ( 5850): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5850): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5850): [OR] == isSIMCardReady false ==
,I/SA      ( 5850): [SCU] == networkStateCheck == true
I/SA      ( 5850): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5850): isChinaCountryCode : false
,I/SA      ( 5850): [OR] == networkStateCheck true ==
,I/SA      ( 5850): [OR] GetMyCountryZoneTask
,I/SA      ( 5850): [OR] onReceive END
,D/dalvikvm( 7619): GC_CONCURRENT freed 2990K, 30% free 9580K/13512K, paused 5ms+2ms, total 31ms
,D/dalvikvm( 7619): WAIT_FOR_CONCURRENT_GC blocked 26ms
,I/SA      ( 5850): [SRS] prepareGetMyCountryZone
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SA      ( 5850): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SCloudBackupReceiver( 7455): Other Intent
,I/SA      ( 5850): [SSP] query invoked
,D/dalvikvm( 7623): GC_CONCURRENT freed 2999K, 30% free 9574K/13512K, paused 4ms+3ms, total 49ms
,D/dalvikvm( 7623): WAIT_FOR_CONCURRENT_GC blocked 45ms
,I/SA      ( 5850): [TPMU] GetMccFromDB : null
,I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [TPM] isNoProxy(default) : true
,I/SA      ( 5850): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7468): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 7623): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7623): getFindoCursor query string : 
,I/System.out( 7412): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/Headlines( 5913): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5913): getCountryCode(): countryCode = PL
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,I/System.out( 7412): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7412): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/KVNProvider( 7623): getTagSearchCursor() tagSearchCursor count : 0
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5913): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5913): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5913): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5913): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5981): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5181): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5181): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/RCPManagerService( 2408): exchangeData() failure , invalid userId
,D/hcjo    ( 6002): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6002): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6002): exit::IDLE
,D/InitializeManagerStateMachine( 6002): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6002): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6002): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6002): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6002): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6002): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6002): entry::SUCCESS
,D/hcjo    ( 6002): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6002): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6002): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6002): exit::SUCCESS
,D/InitializeManagerStateMachine( 6002): entry::IDLE
,E/SPPClientService( 5586): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5586): [SystemStateMoniter] Current Time : 277834
,E/SPPClientService( 5586): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5586): GC_CONCURRENT freed 2013K, 23% free 10453K/13492K, paused 9ms+4ms, total 64ms
,D/dalvikvm( 5586): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/System.out( 7412): AsyncTask #1 calls detatch()
,D/libgps  ( 2408): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2408): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2408): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/System.err( 7412): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7412): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7412): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7412): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7412): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7412): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7412): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7412): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7412): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7412): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7412): Caused by: java.lang.NullPointerException
,W/System.err( 7412): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7412): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7412): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7412): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7412): 	... 8 more
,I/ActivityManager( 2408): Killing 6239:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SA      ( 5850): [RC New] [v2liruge] api execute + 793
,I/SA      ( 5850): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5850): AsyncTask #2 calls detatch()
,I/SA      ( 5850): [TPMU] getNetworkMcc : 
,I/SA      ( 5850): [SCU] saveMccToPreferece Start
,I/SA      ( 5850): [SCU] RegionMCC : 260
,I/SA      ( 5850): [SSP] query invoked
,E/WifiStateMachine( 2408): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
I/SA      ( 5850): [TPMU] GetMccFromDB : null
,I/SA      ( 5850): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5850): [SCU] saveMccToPreferece End
I/SA      ( 5850): [RC New] executeRequest [v2liruge] end. 838
I/SA      ( 5850): [RC New] Execute end
I/SA      ( 5850): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5850): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5586): [b] __InitReply__
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,I/ActivityManager( 2408): Killing 6569:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2408): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2408) eventTime = 280340
D/PowerManagerService( 2408): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2408 (0x0)
D/PowerManagerService( 2408): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2408, ws=WorkSource{1000}) (elapsedTime=3485)
,I/GAV2    ( 7498): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6629): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6629): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6629): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6629): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6629): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6629): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6629): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6629): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6629): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2408): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2408): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2408): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2408): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2408): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2408): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2408): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2408): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6002): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6002): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6002): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6002): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6002): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6002): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6002): entry::IDLE
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PreloadUpdateManagerStateMachine( 6002): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6002): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6002): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6002): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6002): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6002): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6002): entry::IDLE
,E/Watchdog( 2408): !@Sync 9
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{46bd61e8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{45f41770 u0 com.sec.spp.push/.PushClientService}
,I/PowerManagerService( 2408): [PWL] Off : 225s ago
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = -10
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5913): Breath 27240 latestRequest time : 1449671450086 current time : 1449671477326
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2408): initializing...
,I/TLC_TIMA_PKM_initialize( 2408): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2408): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2408): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2408): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2408): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2408): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2408): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2408): device_id = 0x0
,I/TZ: mc_tlc_communication( 2408): tlc_open() was called
,I/TZ: mc_tlc_communication( 2408): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2408): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2408): Opening the session
,I/TZ: mc_tlc_communication( 2408): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2408): Trustlet response is completed
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4370, temperature: 296, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2408): turn off LED
,D/lights  ( 2408): led_pattern : 0 +
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/lights  ( 2408): led_pattern : 0 -
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
,D/lights  ( 2408): button : 1 +
,D/lights  ( 2408): button : 1 -
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 317282
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7aed5ac8, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
I/Sensors ( 2408): HAL: batch Dry Run is complete
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/PowerManagerService( 2408): unblankAllDisplays() is called.
I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable done
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x41789550
D/NotificationService( 2408): cancelNotificationLocked
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/PowerManagerService( 2408): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42f5b660)
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 40ms
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/RampAnimator( 2408): Light Animator Finished currentValue=8
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 5ms
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
,D/KeyguardViewManager( 2581): onScreenTurnedOn()
V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
,D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
V/KeyguardViewManager( 2581): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
,D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2408): !@ElectronBeam exit
I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (10/10)
I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (-2/10)
D/lights  ( 2408): lcd : 8 +
,D/lights  ( 2408): lcd : 8 -
,I/SELinux ( 8064): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8064):  
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9503K/10488K, paused 3ms+7ms, total 54ms
,I/SELinux ( 8064): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8064):  
I/SELinux ( 8064):  
,I/SELinux ( 8064): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8064): >>>>> Normal User
,E/dalvikvm( 8064): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 8064): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 317370886071, previousAccTimestamp = 68514485677, difference = 248856400394 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10488K, paused 6ms+5ms, total 49ms
,D/TimaKeyStoreProvider( 8064): in addTimaSignatureService
,I/chromium( 7321): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,D/TimaKeyStoreProvider( 8064): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8064): Added TimaKesytore provider
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 317437052413, previousAccTimestamp = 68514485677, difference = 248922566736 
D/SensorService( 2408):  [AR] 0.3 -0.0 9.8
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9503K/10488K, paused 3ms+4ms, total 50ms
,D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,I/chromium( 7321): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/SurfaceControl( 2408): Excessive delay in unblankDisplay() while turning screen on: 305ms
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 306ms
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 1
,E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SamsungIME( 2961): showDlgMsgBox : false true true
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,E/libGLESv2( 7321): HWUI Protection: wrong calling from app context F:ES3-glDeleteShader
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2408): semi p:7321,o:f
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2408): Excessive delay in MISC setInteractive(true) while turning screen on: 175ms
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
D/PowerManagerService( 2408): Excessive delay in nativeSetInteractive(true): 177ms
,D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : true
D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/dalvikvm( 8064): GC_CONCURRENT freed 3003K, 30% free 9565K/13508K, paused 6ms+2ms, total 40ms
D/dalvikvm( 8064): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/KIES_RECEIVE( 8064): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 8064): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7619): core_num = 4
,D/dalvikvm( 7619): No JNI_OnLoad found in /system/lib/libsavsff.so 0x4223c6e8, skipping init
,W/linker  ( 7619): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/videowall-Global( 7619): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7619): dsp : 720, swkey : false, Cores : 4, Clock : 0
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,I/SELinux ( 8079): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8079):  
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
I/SELinux ( 8079): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8079):  
I/SELinux ( 8079):  
,I/SELinux ( 8079): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8079): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 8079): >>>>> Normal User
,E/dalvikvm( 8079): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 8079): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 8079): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8079): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8079): Added TimaKesytore provider
,D/dalvikvm( 6471): GC_CONCURRENT freed 2517K, 26% free 10067K/13520K, paused 4ms+4ms, total 55ms
,D/dalvikvm( 8079): GC_CONCURRENT freed 2997K, 30% free 9577K/13512K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 8079): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/Watchdog( 2408): !@Sync 10
,D/dalvikvm( 2408): GC_EXPLICIT freed 3148K, 74% free 25459K/94760K, paused 12ms+20ms, total 240ms
,I/SELinux ( 8096): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8096):  
I/ActivityManager( 2408): Killing 6491:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/SELinux ( 8096): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8096):  
I/SELinux ( 8096):  
,I/SELinux ( 8096): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8096): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8096): >>>>> Normal User
,E/dalvikvm( 8096): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
,E/SELinux ( 8096): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaKeyStoreProvider( 8096): in addTimaSignatureService
D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaKeyStoreProvider( 8096): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8096): Added TimaKesytore provider
,D/dalvikvm( 8096): GC_CONCURRENT freed 3004K, 30% free 9557K/13504K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8096): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
I/iu.Environment( 5981): update battery state; isPlugged? false*
,I/iu.SyncManager( 5981): SYNC; picasa accounts
D/PicasaUploader( 8096):    wifiOnlyPhoto changed to true
D/PicasaUploader( 8096):    wifiOnlyVideo changed to true
,D/PicasaUploader( 8096):    syncOnBattery changed to true
,D/PicasaUploaderSync( 8096): sync account database
I/ActivityManager( 2408): Killing 6601:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/iu.Environment( 3600): update battery state; isPlugged? false*
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
I/iu.UploadsManager( 3600): num queued entries: 0
I/iu.UploadsManager( 3600): num updated entries: 0
I/iu.UploadsManager( 5981): num queued entries: 0
I/iu.SyncManager( 3600): NEXT; no task
I/iu.UploadsManager( 5981): num updated entries: 0
D/PicasaUploaderSync( 8096): accounts in DB=1
D/lights  ( 2408): button : 0 +
D/lights  ( 2408): button : 0 -
I/iu.SyncManager( 5981): NEXT; no task
D/PicasaUploaderSyncManager( 8096): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/PicasaUploaderSyncManager( 8096): background data: true
I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/PicasaUploaderSyncManager( 8096): battery info: false
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1449690300000
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1449671491334
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2736): Unbound from all location providers,
I/GCoreUlr( 2736): Place inference reporting - stopped
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1,
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR,
I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng,
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng,
I/GCoreUlr( 2736): Unbound from all location providers
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2736): Place inference reporting - stopped,
,D/dalvikvm( 5380): GC_CONCURRENT freed 2660K, 27% free 9987K/13584K, paused 14ms+4ms, total 106ms,
,D/dalvikvm( 5380): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR,
D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4360, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
,D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 327224
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/PowerUI ( 2581): playSound : 1
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,I/EntropyMixer( 2408): Writing entropy...
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/VibratorService( 2408): JNI vibratorOn() : 100
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1925): sleepTime is reduced to minimum forcely
D/TranscodeService( 7619): onCreate()
,I/SCloudBackupReceiver( 7455): Other Intent
,D/dalvikvm( 7619): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x4223c6e8, skipping init
,D/PicasaUploaderSyncManager( 8096): battery info: true
,D/dalvikvm( 7619): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x4223c6e8, skipping init
,D/dalvikvm( 7619): No JNI_OnLoad found in /system/lib/libsthmb.so 0x4223c6e8, skipping init
D/TranscodeService( 7619): power? : true / screen off : false
,D/TranscodeService( 7619): releaseTranscodeThread.
,I/iu.Environment( 5981): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.FingerprintManager( 5981): Start processing all media
,D/VibratorService( 2408): JNI vibratorOff()
I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3600): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3600): num queued entries: 0
I/iu.UploadsManager( 3600): num updated entries: 0
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/video/media
,I/iu.SyncManager( 3600): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3600): Start processing all media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5981): Finished generating fingerprints; 0.099 seconds
,I/iu.FingerprintManager( 5981):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/images/media
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,D/dalvikvm( 2724): GC_EXPLICIT freed 357K, 27% free 9973K/13496K, paused 14ms+9ms, total 73ms
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Finished generating fingerprints; 0.134 seconds
,I/iu.FingerprintManager( 3600):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/dalvikvm( 2736): GC_CONCURRENT freed 1791K, 19% free 12012K/14812K, paused 6ms+9ms, total 96ms
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 10
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{431be2e8 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService}
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
,D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2408): NotificationReceiver onReceive()
D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/RCPManagerService( 2408): getPolicy: policy value returned = false
D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = true
,D/RCPManagerService( 2408): Calling User is -1
D/UserManagerService( 2408): User -1does not exists!!
,D/RCPManagerService( 2408): userid of SBN ==-1
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42287448
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/dalvikvm( 2581): GC_CONCURRENT freed 15699K, 33% free 33921K/50556K, paused 14ms+12ms, total 116ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{46afd258 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 11
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/RampAnimator( 2408): Light Animator Finished currentValue=2
D/lights  ( 2408): lcd : 2 +
,D/lights  ( 2408): lcd : 2 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 8125): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8125):  
,I/SELinux ( 8125): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8125):  
I/SELinux ( 8125):  
,I/SELinux ( 8125): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8125): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8125): >>>>> Normal User
,E/dalvikvm( 8125): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8125): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8125): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8125): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8125): Added TimaKesytore provider
,D/dalvikvm( 8125): GC_CONCURRENT freed 2997K, 30% free 9566K/13504K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8125): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5913): Breath 77063 latestRequest time : 1449671450086 current time : 1449671527149
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2408): [PWL] On : 317267 (39953 ms ago)
I/PowerManagerService( 2408): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2408): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=19923)
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2408): unregisterListener ::   
I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2408): !@ElectronBeam entry
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 0
,V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7aed5ac8, enabled=0)
I/Sensors ( 2408): HAL: batch Dry Run is complete
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/PowerManagerService( 2408): blankAllDisplays() is called.
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Display
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SensorManager( 2408): unregisterListener ::   
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
D/PowerManagerService( 2408): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x41789550
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SurfaceControl( 2408): Excessive delay in blankDisplay() while turning screen off: 215ms
I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 217ms
I/PowerManagerService( 2408): [PWL] Off : 0s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2408): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2408): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2408, ws=null) (elapsedTime=214)
I/PowerManagerService( 2408): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : false
,I/SQLiteSecureOpenHelper( 4168): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4168): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 2
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan()
,D/BluetoothAdapter( 5181): stopLeScan()
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7619): power? : true / screen off : true
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
D/TranscodeService( 7619): Music is = false
D/TranscodeService( 7619): runvideoplayer is false
,D/TranscodeService( 7619): Thread start
D/TranscodeService( 7619): WakeLock.acquire()
,D/videowall-FileMgr( 7619): thumbnailDBSync -1
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/SensorManager( 2408): unregisterListener ::   
D/lights  ( 2408): led_pattern : 5 +
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 2148
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 2148
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0x864
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0x864
,D/TranscodeService( 7619): Thread end
,D/TranscodeService( 7619): WakeLock.release()
D/TranscodeService( 7619): onDestroy()
,D/TranscodeService( 7619): releaseTranscodeThread.
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2408): Killing 6615:com.android.musicfx/u0a24 (adj 15): empty #43
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2581): isKioskContainerExistOnDevice
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/PowerManagerService( 2408): [PWL] Off : 5s ago
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5913): Breath 87245 latestRequest time : 1449671450086 current time : 1449671537331
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 8163
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4371, temperature: 298, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,D/lights  ( 2408): led_pattern : 0 +
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/lights  ( 2408): led_pattern : 0 -
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/BatteryService( 2408): turn off LED
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Display
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/lights  ( 2408): button : 1 +
D/lights  ( 2408): button : 1 -
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
I/Sensors ( 2408): HAL: batch Dry Run is complete
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 367525
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 4ms
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_disable done
D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x41789550
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/PowerManagerService( 2408): unblankAllDisplays() is called.
D/PowerManagerService( 2408): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x809e0a60, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 19ms
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/RampAnimator( 2408): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/NotificationService( 2408): cancelNotificationLocked
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@4325cd10)
D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 3
D/KeyguardViewMediator( 2581): notifyScreenOnLocked
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
D/KeyguardViewManager( 2581): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
,D/LockPatternUtils( 2581): isPcwEnable = 10
V/KeyguardViewManager( 2581): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2408): !@ElectronBeam exit
I/SurfaceFlinger( 1921): id=21 Removed FlectronBea (10/10)
I/SurfaceFlinger( 1921): id=21 Removed FlectronBea (-2/10)
D/lights  ( 2408): lcd : 8 +
,D/lights  ( 2408): lcd : 8 -,
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,I/KIES_RECEIVE( 8064): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 8064): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 367625695137, previousAccTimestamp = 357457115473, difference = 10168579664 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 367692357985, previousAccTimestamp = 357457115473, difference = 10235242512 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2408): Excessive delay in unblankDisplay() while turning screen on: 246ms
,D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 247ms
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2408): semi p:7321,o:f
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 1
E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,D/SamsungIME( 2961): showDlgMsgBox : false true true
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/PicasaUploaderSyncManager( 8096): battery info: false
,I/iu.Environment( 5981): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.Environment( 3600): update battery state; isPlugged? false*
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.UploadsManager( 3600): num queued entries: 0
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/iu.UploadsManager( 3600): num updated entries: 0
I/iu.SyncManager( 3600): NEXT; no task
I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/GCoreUlr( 2736): DispatchingService.onCreate()
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2408): Excessive delay in MISC setInteractive(true) while turning screen on: 163ms
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
D/PowerManagerService( 2408): Excessive delay in nativeSetInteractive(true): 164ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : true
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = -10
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1449690300000
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1449671540555
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
I/GCoreUlr( 2736): Unbound from all location providers
I/GCoreUlr( 2736): Place inference reporting - stopped
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4355, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 377507
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
D/PowerUI ( 2581): playSound : 1
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/VibratorService( 2408): JNI vibratorOn() : 100
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
I/EntropyMixer( 2408): Writing entropy...
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_CONNECTED
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/TranscodeService( 7619): onCreate()
,I/SCloudBackupReceiver( 7455): Other Intent
D/TranscodeService( 7619): power? : true / screen off : false
,D/TranscodeService( 7619): releaseTranscodeThread.
,D/PicasaUploaderSyncManager( 8096): battery info: true
,I/iu.Environment( 5981): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.FingerprintManager( 5981): Start processing all media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/images/media
D/VibratorService( 2408): JNI vibratorOff()
,I/iu.Environment( 3600): update battery state; isPlugged? true*
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3600): num queued entries: 0
,I/iu.UploadsManager( 3600): num updated entries: 0
,I/iu.SyncManager( 3600): NEXT; no task
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3600): Start processing all media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/images/media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5981): Finished generating fingerprints; 0.094 seconds
,I/iu.FingerprintManager( 5981):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Finished generating fingerprints; 0.075 seconds
,I/iu.FingerprintManager( 3600):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 10
,E/Watchdog( 2408): !@Sync 12
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4360, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{44458398 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5913): Breath 117224 latestRequest time : 1449671450086 current time : 1449671567310
,D/SensorService( 2408):   0.3 0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4358, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,D/RCPManagerService( 2408): NotificationReceiver onReceive()
,D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
,D/RCPManagerService( 2408): getPolicy: policy value returned = false
D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
,D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = true
,D/UserManagerService( 2408): User -1does not exists!!
D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42287448
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 300, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2408):   0.3 -0.0 9.9
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2408): [PWL] On : 367520 (39985 ms ago)
I/PowerManagerService( 2408): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2408): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=9870)
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2408): GC_FOR_ALLOC freed 3294K, 73% free 26150K/94760K, paused 199ms, total 199ms
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4358, temperature: 300, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
,D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 407958
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/lights  ( 2408): lcd : 8 +
D/RampAnimator( 2408): Light Animator Finished currentValue=8
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
D/NotificationService( 2408): cancelNotificationLocked
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/lights  ( 2408): lcd : 8 -
,D/LightsService( 2408): Excessive delay setting light: 51ms
,I/KIES_RECEIVE( 8064): [APK BnR] Receive KIES_USB_DISCONNECT
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
W/ContextImpl( 8064): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
,D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/TranscodeService( 7619): onDestroy()
,D/TranscodeService( 7619): releaseTranscodeThread.
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/PicasaUploaderSyncManager( 8096): battery info: false
,I/iu.Environment( 5981): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5981): num queued entries: 0,
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.Environment( 3600): update battery state; isPlugged? false*
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/iu.UploadsManager( 3600): num queued entries: 0
,I/iu.UploadsManager( 3600): num updated entries: 0
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/iu.SyncManager( 3600): NEXT; no task
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,E/Watchdog( 2408): !@Sync 13
,D/dalvikvm( 2408): GC_CONCURRENT freed 426K, 73% free 25926K/94760K, paused 9ms+21ms, total 279ms
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4356, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 417779
D/PowerUI ( 2581): playSound : 1
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/VibratorService( 2408): JNI vibratorOn() : 100
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
I/EntropyMixer( 2408): Writing entropy...
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/TranscodeService( 7619): onCreate()
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/TranscodeService( 7619): power? : true / screen off : false
,D/TranscodeService( 7619): releaseTranscodeThread.
,I/SCloudBackupReceiver( 7455): Other Intent
,D/PicasaUploaderSyncManager( 8096): battery info: true
,I/iu.Environment( 5981): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.FingerprintManager( 5981): Start processing all media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/images/media
,D/VibratorService( 2408): JNI vibratorOff()
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/video/media
,I/iu.Environment( 3600): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3600): num queued entries: 0
,I/iu.UploadsManager( 3600): num updated entries: 0
,I/iu.SyncManager( 3600): NEXT; no task
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/images/media
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/iu.FingerprintManager( 3600): Start processing all media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/video/media
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
I/iu.FingerprintManager( 5981): Finished generating fingerprints; 0.060 seconds
,I/iu.FingerprintManager( 5981):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Finished generating fingerprints; 0.072 seconds
,I/iu.FingerprintManager( 3600):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
I/GCoreUlr( 2736): DispatchingService.onDestroy()
I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :8
,D/Headlines( 5913): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5913): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5913): Breath 147224 latestRequest time : 1449671450086 current time : 1449671597311
,D/Headlines( 5913): stop 
,D/Headlines( 5913): Breath.onDestroy : 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4367, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
D/RCPManagerService( 2408): NotificationReceiver onReceive()
,D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = false
D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = true
,D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
D/UserManagerService( 2408): User -1does not exists!!
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42287448
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 301, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{4584a5e8 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4357, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,E/Watchdog( 2408): !@Sync 14
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
,I/PowerManagerService( 2408): [PWL] On : 367520 (80257 ms ago)
I/PowerManagerService( 2408): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2408): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2581, ws=null) (elapsedTime=19966)
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
D/SensorManager( 2408): unregisterListener ::   
I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2408): !@ElectronBeam entry
D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:3, health:9, present:true, voltage: 4357, temperature: 301, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 0
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2408): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2408): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,V/WindowOrientationListener( 2408): WindowOrientationListener disabled
,D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x809e0a60, enabled=0)
,I/Sensors ( 2408): HAL: batch Dry Run is complete
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [s] UserActivityState : 0 -> 1
D/lights  ( 2408): button : 1 +
,D/lights  ( 2408): button : 1 -
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 447954
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SensorManager( 2408): unregisterListener ::   
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LockPatternUtils( 2581): isPcwEnable = 10
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 5ms
I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/lights  ( 2408): lcd : 235 +
,D/LockPatternUtils( 2581): isPcwEnable = 10
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/RampAnimator( 2408): Light Animator Finished currentValue=8
I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 29ms
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/lights  ( 2408): lcd : 235 -
,D/lights  ( 2408): lcd : 8 +
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/NotificationService( 2408): cancelNotificationLocked
D/NotificationService( 2408):  hasClearableItems
D/NotificationService( 2408):  has clearable items no 
D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2408): cancelNotificationLocked: cancel alarm
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(3) - 5
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/UsbDeviceManager( 2408): received ACTION_POWER_DISCONNECTED = -1
,D/lights  ( 2408): lcd : 8 -
,D/LightsService( 2408): Excessive delay setting light: 51ms
,D/lights  ( 2408): lcd : 0 +
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 3
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/KIES_RECEIVE( 8064): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 8064): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,I/SQLiteSecureOpenHelper( 4168): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4168): getDatabaseLocked(b,b,pwd)...
D/VibratorService( 2408): JNI vibratorOff()
,D/lights  ( 2408): lcd : 0 -
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/TranscodeService( 7619): onDestroy()
,D/TranscodeService( 7619): releaseTranscodeThread.
,V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,D/PicasaUploaderSyncManager( 8096): battery info: false
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,I/iu.Environment( 5981): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
,I/iu.SyncManager( 5981): NEXT; no task
D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
I/ActivityManager( 2408): Killing 6641:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,I/iu.Environment( 3600): update battery state; isPlugged? false*
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
I/iu.UploadsManager( 3600): num queued entries: 0
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
I/iu.UploadsManager( 3600): num updated entries: 0
I/iu.SyncManager( 3600): NEXT; no task
I/GCoreUlr( 2736): DispatchingService.onCreate()
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:123, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
,D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - shouldScanBleBg = false
,I/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5181): stopLeScan()
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan() complete
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x88e0ca78, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 448193426842, previousAccTimestamp = 447853096586, difference = 340330256 
D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@43312d18)
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 4
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
D/KeyguardViewManager( 2581): onScreenTurnedOn()
,I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
V/KeyguardViewManager( 2581): send wm null token: host was null
,I/SurfaceFlinger( 1921): id=22 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=22 Removed FlectronBea (-2/10)
I/WindowManager( 2408): No lock screen! windowToken=null
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 2408): !@ElectronBeam exit
D/LockPatternUtils( 2581): isPcwEnable = 10
D/lights  ( 2408): lcd : 8 +
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/lights  ( 2408): lcd : 8 -
D/StatusBarManagerService( 2408): semi p:7321,o:f
D/DisplayPowerController( 2408): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
,D/SamsungIME( 2961): showDlgMsgBox : false true true
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 448428487467, previousAccTimestamp = 447853096586, difference = 575390881 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1449690300000
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1449671621019
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
,D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/lights  ( 2408): button : 0 +
,D/lights  ( 2408): button : 0 -
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4353, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UsbDeviceManager( 2408): handleMessage -> MSG_POWER_STATE = 1
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/PowerManagerService( 2408): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/PowerUI ( 2581): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2408): [api] [s] wakeUp (uid: 10019 pid: 2581) eventTime = 458019
V/Vibrator( 2581): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2581): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
D/PowerUI ( 2581): playSound : 1
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
V/VibratorService( 2408): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/VibratorService( 2408): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2408): JNI vibratorOff()
D/VibratorService( 2408): JNI vibratorOn() : 100
I/EntropyMixer( 2408): Writing entropy...
D/PowerUI ( 2581): RINGER_MODE_VIBRATE
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/UsbDeviceManager( 2408): sending intent : ACTION_USB_CABLE_STATE : connected = true
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/TranscodeService( 7619): onCreate()
D/BatteryMeterView( 2581): onDraw batteryColor : -1
,I/SCloudBackupReceiver( 7455): Other Intent
D/TranscodeService( 7619): power? : true / screen off : false
,D/TranscodeService( 7619): releaseTranscodeThread.
,D/PicasaUploaderSyncManager( 8096): battery info: true
,I/iu.Environment( 5981): update battery state; isPlugged? true*
,I/iu.UploadsManager( 5981): num queued entries: 0
,I/iu.UploadsManager( 5981): num updated entries: 0
,I/iu.SyncManager( 5981): NEXT; no task
,I/iu.FingerprintManager( 5981): Start processing all media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/images/media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/external/video/media
,I/iu.Environment( 3600): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3600): num queued entries: 0
,I/iu.UploadsManager( 3600): num updated entries: 0
,I/iu.SyncManager( 3600): NEXT; no task
D/VibratorService( 2408): JNI vibratorOff()
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2736): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3600): Start processing all media
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/images/media
,I/GCoreUlr( 2736): DispatchingService.onCreate()
,I/iu.FingerprintManager( 5981): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 5981): Finished generating fingerprints; 0.077 seconds
,I/iu.FingerprintManager( 5981):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3600): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3600): Finished generating fingerprints; 0.081 seconds
,I/iu.FingerprintManager( 3600):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,D/dalvikvm( 2736): GC_CONCURRENT freed 2205K, 22% free 11803K/15024K, paused 5ms+6ms, total 80ms
,I/GCoreUlr( 2736): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2736): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,I/GCoreUlr( 2736): DispatchingService.onDestroy()
,I/GCoreUlr( 2736): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2736): Unbound from all location providers
,I/GCoreUlr( 2736): Place inference reporting - stopped
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionTIME_TICK
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4365, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,E/Watchdog( 2408): !@Sync 15
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 302, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,I/ActivityManager( 2408): Waited long enough for: ServiceRecord{4336bc08 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryService( 2408): level:100, scale:100, status:2, health:2, present:true, voltage: 4378, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 303, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2408): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/lights  ( 2408): lcd : 2 +
D/RampAnimator( 2408): Light Animator Finished currentValue=2
,D/lights  ( 2408): lcd : 2 -
,D/SensorService( 2408):   0.3 -0.0 9.9
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2408):   0.3 0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:2
,D/PowerManagerService( 2408): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2408): Nap time...
D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2408): unregisterListener ::   
I/SurfaceFlinger( 1921): id=23 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
D/DisplayPowerController( 2408): !@ElectronBeam entry
,D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/PowerManagerService( 2408): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581
,I/PowerManagerService( 2408): !@[ps] Screen__On(wake lock) :  wl: PowerUI
I/PowerManagerService( 2408): Waking up from sleep...
D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2408): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerNotifier( 2408): mBroadcastInProgress = true , mActualPowerState = 1 , mPendingWakeUpBroadcast = true , mPendingGoToSleepBroadcast = true , mBroadcastedPowerState = 1
,V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x88e0ca78, enabled=0)
I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/lights  ( 2408): button : 1 +
D/PowerManagerService( 2408): [s] WAKEFULNESS_AWAKE
D/lights  ( 2408): button : 1 -
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : registerListener mLightSensor
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
D/STATUSBAR-StatusBarManagerService( 2408): sendNotification(1) - 5
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
,D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 1
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2408): [DAB] no lux value from sensor manager
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 13ms
I/Sensors ( 2408): HAL: batch Dry Run is complete
D/NotificationService( 2408): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/LockPatternUtils( 2581): isPcwEnable = 10
W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
,D/RCPManagerService( 2408): NotificationReceiver onReceive()
,D/RCPManagerService( 2408):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298408
,D/ProgressBar( 2581): setProgressDrawable drawableHeight = 12
D/RCPManagerService( 2408): getPolicy: policy value returned = false
D/RCPManagerService( 2408): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2408): app label == com.android.systemui
,D/RCPManagerService( 2408): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298408
D/RCPManagerService( 2408): getPolicy: policy value returned = true
D/RCPManagerService( 2408): Calling User is -1
,D/RCPManagerService( 2408): userid of SBN ==-1
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/UserManagerService( 2408): User -1does not exists!!
E/PersonaManagerService( 2408): returning null in  getPersonasForUser
,D/PhoneStatusBar( 2581): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@42287448
D/SensorManager( 2408): unregisterListener ::   
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 4
,D/SensorManager( 2408): registerListener :: 2, MPL Accelerometer, 200000, 0,  
D/PowerManagerService( 2408): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 32ms
,I/SQLiteSecureOpenHelper( 4168): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4168): getDatabaseLocked(b,b,pwd)...
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryMeterView( 2581): onDraw batteryColor : -1
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/Sensors ( 2408): LightSensor sending flush event 16
D/DisplayPowerController( 2408): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 5 +
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/DisplayPowerController( 2408): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/lights  ( 2408): led_pattern : 5 -
D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
,D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:124, mClearCover:0
,D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5181): stopLeScan()
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan() complete
,D/Sensors ( 2408): LightSensor sending flush event 16
,D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/TranscodeReceiver( 7619): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7619): power? : true / screen off : true
,D/TranscodeService( 7619): Music is = false
,D/TranscodeService( 7619): runvideoplayer is false
,D/TranscodeService( 7619): Thread start
,D/TranscodeService( 7619): WakeLock.acquire()
,D/videowall-FileMgr( 7619): thumbnailDBSync -1
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 65558
D/SensorService( 2408): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7beb8e48, enabled=1)
D/SensorService( 2408): AutoRotationSensor::AR_init
,I/Sensors ( 2408): HAL: batch Dry Run is complete
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 488608508680, previousAccTimestamp = 488098826485, difference = 509682195 
,D/SensorService( 2408): AutoRotationSensor::reset oldrotation = [100], initState = [1]
D/SensorManager( 2408): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
V/KeyguardServiceDelegate( 2408): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@42f935c8)
,D/InputDispatcher( 2408): setInputDispatchMode: enabled=1, frozen=0
,D/KeyguardViewMediator( 2581): onScreenTurnedOn, seq = 5
,D/KeyguardViewMediator( 2581): notifyScreenOnLocked
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/KeyguardViewMediator( 2581): handleNotifyScreenOn
D/KeyguardViewManager( 2581): onScreenTurnedOn()
I/KeyguardEffectViewMain( 2581): *** KeyguardEffectView getInstance ***
D/VisualEffectParticleEffect( 2581): KeyguardEffectViewParticleSpace : screenTurnedOn
V/KeyguardServiceDelegate( 2408): **** SHOWN CALLED ****
,D/VisualEffectParticleEffect( 2581): screenOnAnimationStart
V/KeyguardViewManager( 2581): send wm null token: host was null
I/WindowManager( 2408): No lock screen! windowToken=null
D/PowerManagerNotifier( 2408): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2408): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 1921): id=23 Removed FlectronBea (10/10)
,I/SurfaceFlinger( 1921): id=23 Removed FlectronBea (-2/10)
,D/DisplayPowerController( 2408): !@ElectronBeam exit
,D/lights  ( 2408): lcd : 2 +
D/StatusBarManagerService( 2408): semi p:7321,o:f
,D/lights  ( 2408): lcd : 2 -
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/DisplayPowerController( 2408): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PalmMotionService( 2408): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2408): SURFACE_PALM_SWIPE: 1
,E/MotionRecognitionService( 2408):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.USER_PRESENT
,D/SamsungIME( 2961): showDlgMsgBox : false true true
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
I/NfcService( 2756): applyRouting return - 2 
E/NfcService( 2756): callback == null
,D/LockPatternUtils( 2581): isPcwEnable = 10
,D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2408): turn off LED
D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
,D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 0 +
,D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2408): led_pattern : 0 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/TranscodeService( 7619): Thread end
,D/TranscodeService( 7619): WakeLock.release()
D/TranscodeService( 7619): onDestroy()
D/TranscodeService( 7619): releaseTranscodeThread.
,D/TranscodeService( 7619): Thread isAlive
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/SensorService( 2408): AutoRotationSensor::process: Acc  eventTimestamp = 488717287028, previousAccTimestamp = 488098826485, difference = 618460543 
D/SensorService( 2408):  [AR] 0.3 0.0 9.9
,D/SensorService( 2408): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/Sensors ( 2408): LightSensor sending flush event 16
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_ON
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2408): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=on)
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_ON called
,I/NfcService( 2756): NFC: Screen On & Cover Open
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-NetworkController( 2581): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - bluetoothActionState = 0
D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5181): BleHelper.startScan - shouldScanBleFg = false
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/dalvikvm( 5380): GC_CONCURRENT freed 2064K, 27% free 9960K/13584K, paused 3ms+5ms, total 58ms
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1449690300000
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1449671661367
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,D/daemonapp( 5380): [MSC_Daemon]>>> WCS:143 [0:0] action:androidintentactionSCREEN_ON
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5380): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:44 [0:0] Act : widgetappapaccuweatherdaemonactionCHANGE_ICON_OF_DAEMON, run:true
D/vwengine( 7619): stopTranscoding
,D/TranscodeService( 7619): transThread.join();
D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5380): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5380): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5380): [MSC_Daemon]>>> ====================================================================================================================
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts,
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:377 [0:0] ====ACTION_SEC_CHANGE_ICON_OF_DAEMON===
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:381 [0:0] checkDay:true, UtilgetIsDay():false
V/ApplicationPolicy( 2408): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
D/daemonapp( 5380): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/daemonapp( 5380): [MSC_Daemon]>>> WDSM:424 [0:0] today==null,
,D/lights  ( 2408): button : 0 +,
,D/lights  ( 2408): button : 0 -
,D/SSRMv2:TSP:AirViewOnOff( 2408): SettingsAirViewInfo:: 000000000
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4,
,D/SensorService( 2408):   0.3 0.0 9.9,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/dalvikvm( 2408): GC_CONCURRENT freed 3824K, 72% free 26107K/93008K, paused 21ms+18ms, total 235ms,
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 4, mDelayedShowingSequence = 5,
V/AlarmManager( 2408): waitForAlarm result :4
V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SensorService( 2408):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SensorService( 2408):   0.3 0.0 9.9
,E/Watchdog( 2408): !@Sync 16,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 304, prevStep = 4, currStep = 4
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SensorService( 2408):   0.3 -0.0 9.9,
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2408):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2408): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2581 (0x0)
I/PowerManagerService( 2408): Nap time...
,D/PowerManagerService( 2408): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2408): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2408): Going to sleep due to screen timeout...
D/PowerManagerService( 2408): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/DisplayPowerController( 2408): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/SurfaceFlinger( 1921): id=24 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2408): HAL:resetDataRates mEnabled=4
,I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
I/DisplayPowerController( 2408): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 2408): !@ElectronBeam entry
D/SensorManager( 2408): unregisterListener ::   
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2408): lcd : 0 +
,D/lights  ( 2408): lcd : 0 -
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2408): blankAllDisplays() is called.
D/PowerManagerService( 2408): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/PowerManagerService( 2408): [PWL] sb acquire: PowerManagerService.Broadcasts
V/WindowOrientationListener( 2408): WindowOrientationListener disabled
D/SensorService( 2408): AutoRotationSensor::activate (ident=0x7beb8e48, enabled=0)
I/Sensors ( 2408): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2581): onScreenTurnedOff(3)
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Display
,D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input1/enabled: 0
D/MISC PowerHAL( 2408): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorManager( 2408): unregisterListener ::   
D/InputDispatcher( 2408): setInputDispatchMode: enabled=0, frozen=0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/input/input0/enabled: 0
,D/MISC PowerHAL( 2408): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2408): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
,D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2408): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2408): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2408): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x41789550
,D/LockPatternUtils( 2581): isPcwEnable = 10
,I/SQLiteSecureOpenHelper( 4168): getWritableDatabase(pwd),
,I/SQLiteSecureOpenHelper( 4168): getDatabaseLocked(b,b,pwd)...,
,D/KeyguardViewMediator( 2581): setting alarm to turn off keyguard, seq = 5,
,D/LightsService( 2408): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2408) ,
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
,D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2408): turn on LED for fully charged
D/VibratorService( 2408): JNI vibratorOff()
,I/WifiTrafficPoller( 2408): evaluateTrafficStatsPolling
,D/STATUSBAR-NotificationService( 2408): ACTION_SCREEN_OFF
D/LightsService( 2408): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2408) 
,D/LightsService( 2408): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1925): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2408): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2408): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2408): Bridge Server is not available
,D/PersonaManagerService( 2408): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2408): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2581): makeExpandedInvisible
D/PhoneStatusBarView( 2581): marqueeStatusBar:125, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2581):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2756): applyRouting return - 2 
,E/NfcService( 2756): callback == null
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/LockPatternUtils( 2581): isPcwEnable = 10
D/SurfaceControl( 2408): Excessive delay in blankDisplay() while turning screen off: 213ms
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2408): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2408): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 213ms
D/PowerManagerService( 2408): SecHardwareInterface.setBatteryADC : false
I/PowerManagerService( 2408): [PWL] Off : 0s ago
I/PowerManagerService( 2408): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2408): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2408): [PWL]       PARTIAL_WAKE_LOCK              'GCoreFlp' (uid=10012, pid=2736, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=23)
I/PowerManagerService( 2408): [PWL]   PowerManagerService.Broadcasts: ref count=1
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5181): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
V/QuickConnect[1.1][2] ( 5181): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5181): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
,V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
V/QuickConnect[1.1][2] ( 5181): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a918
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - force = true
D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5181): stopLeScan()
,D/QuickConnect[1.1][2] ( 5181): BleHelper.stopScan - call stopLeScan() complete
,D/PowerManagerService( 2408): [PWL] sb release: PowerManagerService.Broadcasts
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
,D/lights  ( 2408): led_pattern : 5 +
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2408): led_pattern : 5 -
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2408): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :4,
,D/KeyguardViewMediator( 2581): received DELAYED_KEYGUARD_ACTION with seq = 5, mDelayedShowingSequence = 5,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
,D/KeyguardViewMediator( 2581): in doKeyguardLocked mIsRollUp false null,
,D/PersonaManager( 2581): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2581): isPcwEnable = 10,
D/LockPatternUtils( 2581): isPcwEnable = 10
,D/KeyguardViewMediator( 2581): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2408): [PWL] Off : 5s ago,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2408): [PWL] Off : 15s ago,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 4078): GC_CONCURRENT freed 2883K, 29% free 9690K/13544K, paused 11ms+2ms, total 66ms,
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 53ms
,E/Watchdog( 2408): !@Sync 17,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 305, currTemp = 303, prevStep = 4, currStep = 4,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2408): [PWL] Off : 30s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = -10
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/AmoledAdjustTimer( 2408): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2408): waitForAlarm result :4,
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,E/Watchdog( 2408): !@Sync 18,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,I/PowerManagerService( 2408): [PWL] Off : 50s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2408): [PWL] Off : 75s ago,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2408): !@Sync 19,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1,
,I/PowerManagerService( 2408): [PWL] Off : 105s ago,
I/PowerManagerService( 2408): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2408): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2408): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2408, ws=null) (elapsedTime=1720),
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 8646
,E/Watchdog( 2408): !@Sync 20,
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2408): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2408): !@Sync 21,
,I/PowerManagerService( 2408): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/GAV2    ( 5678): Thread[disconnect check,5,main]: Disconnecting due to inactivity,
,I/GAV2    ( 5678): Thread[disconnect check,5,main]: Disconnected from service,
,E/Watchdog( 2408): !@Sync 22,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2408): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2408): waitForAlarm result :8,
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK,
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___,
V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2408): !@Sync 23,
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2408): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2408): stay LED for fully charged,
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 225s ago
,E/Watchdog( 2408): !@Sync 24
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 25
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/AmoledAdjustTimer( 2408): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2408): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 26
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :4
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3600): Aggregate from 1449670131011 (log), 1449670131011 (data)
,D/dalvikvm( 3600): GC_CONCURRENT freed 1822K, 18% free 12586K/15344K, paused 22ms+8ms, total 121ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2408): GC_CONCURRENT freed 4142K, 72% free 26087K/93008K, paused 20ms+19ms, total 232ms
,E/Watchdog( 2408): !@Sync 27
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2408): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 28
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 29
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2408): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 31
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 32
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 33
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10275
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10277
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10278
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10280
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10282
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10283
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10285
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10287
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10288
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 10289
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 525s ago
,E/Watchdog( 2408): !@Sync 34
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 35
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 36
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
D/Sensors ( 2408): LightSensor setDelay = 200000000
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5586): [b] __PingReply__
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 37
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 38
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4078): GC_CONCURRENT freed 1894K, 29% free 9723K/13540K, paused 2ms+2ms, total 34ms
,E/Watchdog( 2408): !@Sync 39
,I/PowerManagerService( 2408): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2408): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 41
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 4158K, 73% free 25986K/93008K, paused 22ms+19ms, total 272ms
,I/PowerManagerService( 2408): [PWL] Off : 765s ago
,E/Watchdog( 2408): !@Sync 42
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 43
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 44
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 855s ago
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 45
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 46
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 47
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2408): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 48
,I/PowerManagerService( 2408): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 49
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2408): Skipping unknown process pid 11965
,E/Watchdog( 2408): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 51
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 52
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 53
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 54
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2408): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1155s ago
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 55
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 56
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,E/SPPClientService( 5586): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 57
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2408): GC_CONCURRENT freed 4046K, 73% free 25975K/93008K, paused 24ms+19ms, total 284ms
,E/Watchdog( 2408): !@Sync 58
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2772): GC_CONCURRENT freed 8971K, 36% free 18074K/27988K, paused 8ms+7ms, total 78ms
,E/Watchdog( 2408): !@Sync 59
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2408): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2408): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2408): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2408): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2408): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2408): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2408): Prepared write state in 62ms
,I/ProcessStatsService( 2408): Prepared write state in 24ms
,I/ProcessStatsService( 2408): Pruning old procstats: /data/system/procstats/state-2015-12-08-19-46-36.bin
,E/Watchdog( 2408): !@Sync 61
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :4
,I/SensorManagerA( 2408): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2408): LightSensor setDelay = 200000000
,D/LightsService( 2408): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2408): LightSensor setSensorDelay = 200000000
D/Sensors ( 2408): Light sensor flush: not enabled 0
D/Sensors ( 2408): LightSensor enable = 1
D/Sensors ( 2408): LightSensor enableSensor = 1
D/SensorManager( 2408): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked(flags=0x3)
,V/AlarmManager( 2408): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2408): currentTimeMillis() cache hit
V/NetworkStats( 2408): performPollLocked() took 39ms
,I/SELinux (13345): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13345):  
,I/SELinux (13345): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13345):  
I/SELinux (13345):  
,I/SELinux (13345): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13345): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13345): >>>>> Normal User
,E/dalvikvm(13345): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13345): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13345): in addTimaSignatureService
,D/TimaKeyStoreProvider(13345): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13345): Added TimaKesytore provider
,D/Sensors ( 2408): LightSensor enable = 0
,D/Sensors ( 2408): LightSensor enableSensor = 0
,D/LightsService( 2408): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2408): unregisterListener ::   
D/LightsService( 2408): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm(13345): GC_CONCURRENT freed 3012K, 30% free 9556K/13512K, paused 3ms+3ms, total 27ms
,D/dalvikvm(13345): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(13345): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13345): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13345): Widget random data : 4
,D/@ WidgetProvider(13345): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13345): Widget random data : 6
,I/ActivityManager( 2408): Killing 6048:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,E/dalvikvm(13345): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(13345): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13345): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13345): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
,W/dalvikvm(13345): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13345): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13345): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
,W/dalvikvm(13345): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13345): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13345): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
,W/dalvikvm(13345): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13345): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(13345): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(13345): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13345): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13345): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2848): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(13345): Thread-684(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13345): Thread-684(ApacheHTTPLog):isShipBuild true
,I/System.out(13345): Thread-684(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(13345): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13345): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13345): Max ALLOWED memory (MB): 128
,V/ImageManager(13345): Max SHOULD USE memory (MB): 128
,V/ImageManager(13345): Max Image Cache memory (MB): 32
,D/skia    (13345): getTotalSize : Do not get file length
,D/@ WidgetProvider(13345): Building widget : 5
,D/dalvikvm( 2772): GC_FOR_ALLOC freed 318K, 33% free 18838K/27980K, paused 34ms, total 35ms
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 62
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2408): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2408): <AppSync3 Whitelist>
,V/AlarmManager( 2408): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4078): GC_CONCURRENT freed 2047K, 28% free 9723K/13384K, paused 4ms+7ms, total 36ms
,E/Watchdog( 2408): !@Sync 63
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 64
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/ActivityManager( 2408): Killing 6485:com.sec.knox.bridge/1000 (adj 15): empty for 1816s
,I/ActivityManager( 2408): Killing 4905:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1816s
,I/ActivityManager( 2408): Killing 6448:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1826s
,I/ActivityManager( 2408): Killing 6787:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1827s
,I/ActivityManager( 2408): Killing 6773:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1827s
,I/ActivityManager( 2408): Killing 6761:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1827s
,I/ActivityManager( 2408): Killing 6749:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1827s
,I/ActivityManager( 2408): Killing 6736:com.samsung.helphub/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2408): Killing 6723:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1828s
,I/ActivityManager( 2408): Killing 6710:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1828s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2408): Killing 6697:com.sec.android.service.cm/u0a82 (adj 15): empty for 1828s
,I/ActivityManager( 2408): Killing 6404:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1828s
,I/ActivityManager( 2408): Killing 5737:com.android.mms/u0a49 (adj 15): empty for 1828s
,I/ActivityManager( 2408): Killing 6671:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1828s
,D/CountryDetector( 2408): No listener is left
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2408): stay LED for fully charged
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 65
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2408): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2408): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2408): stay LED for fully charged
,D/UiModeManager( 2408): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2408): !@Sync 66
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2408): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 67
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2408): !@Sync 68
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2408): waitForAlarm result :8
,V/AlarmManager( 2408): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
I/ActivityManager( 2408): Killing 7498:com.google.android.apps.magazines/u0a115 (adj 15): empty for 1809s
I/ActivityManager( 2408): Killing 7468:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1809s
I/ActivityManager( 2408): Killing 7623:com.sec.android.app.voicenote/1000 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 5850:com.osp.app.signin/u0a44 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 6655:com.policydm/1000 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 7443:com.sec.android.soagent/u0a38 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 7369:com.vlingo.midas/u0a34 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 7431:com.samsung.klmsagent/u0a18 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 7412:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 5792:com.sec.android.diagmonagent/1000 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 6629:com.sec.pcw.device/1000 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 4749:com.android.settings/1000 (adj 15): empty for 1810s
I/ActivityManager( 2408): Killing 7572:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1811s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2408): !@Sync 69
,D/SSRMv2:SIOP( 2408): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2408): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
