#### Test 506502785223c58_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2406): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7214): 
D/AndroidRuntime( 7214): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7214): CheckJNI is OFF
D/AndroidRuntime( 7214): setted country_code = Poland
D/AndroidRuntime( 7214): setted countryiso_code = PL
D/AndroidRuntime( 7214): setted sales_code = PLS
D/AndroidRuntime( 7214): readGMSProperty: start
D/AndroidRuntime( 7214): readGMSProperty: already setted!!
D/AndroidRuntime( 7214): readGMSProperty: end
D/AndroidRuntime( 7214): addProductProperty: start
D/dalvikvm( 7214): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7214): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7214): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7214): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7214): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1609633, pollInterval: 10000
E/memtrack( 7214): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7214): failed to load memtrack module: -2
D/dalvikvm( 7214): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7214): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2406): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2406): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2406): mDVFSHelper.acquire()
I/SELinux ( 7242): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7242):  
D/PointerIcon( 2406): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2406): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2406): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2406): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7214): Shutting down VM
D/dalvikvm( 7214): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7242): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7242):  
I/SELinux ( 7242):  
I/SELinux ( 7242): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7242): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7242): >>>>> Normal User
E/dalvikvm( 7242): >>>>> com.test.thalitest [ userId:0 | appId:10560 ]
E/SELinux ( 7242): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7242): in addTimaSignatureService
D/TimaKeyStoreProvider( 7242): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7242): Added TimaKesytore provider
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
I/SQLiteSecureOpenHelper( 4188): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4188): getDatabaseLocked(b,b,pwd)...
D/dalvikvm( 7242): GC_CONCURRENT freed 3006K, 30% free 9565K/13552K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7242): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7242): Binding Chromium to the background looper Looper (main, tid 1) {423be260}
I/chromium( 7242): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7242): Initializing chromium process, renderers=0
W/chromium( 7242): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7242): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7242): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7242): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7242): Mali API Version : 401
I/Mali    ( 7242): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7242): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7242): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7242): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7242): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/StatusBarManagerService( 2406): tr p:7242,o:f
W/dalvikvm( 7242): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7242): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7242): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7242): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7242): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7242): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7242): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7242): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7242): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7242): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7242): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2406): semi p:7242,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2406): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2406): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2406): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2406): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2406): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2406): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7242): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7242): Enabling debug mode 0
,W/AwContents( 7242): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7242): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2406): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2406): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2406): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7242): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7242): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7242): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x423befe8
,D/dalvikvm( 7242): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x423befe8
D/jxcore_app_log( 7242): JniHelper::setJavaVM(0x4196c220), pthread_self() = 2027536392
,D/JX-Cordova( 7242): jxcore cordova android initializing
,D/dalvikvm( 7242): GC_CONCURRENT freed 1287K, 17% free 11350K/13612K, paused 1ms+2ms, total 22ms
,D/dalvikvm( 7242): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0
,D/dalvikvm( 7242): GC_CONCURRENT freed 1919K, 17% free 14901K/17812K, paused 1ms+2ms, total 36ms
,D/dalvikvm( 7242): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/CustomFrequencyManagerService( 2406): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7242): GC_FOR_ALLOC freed 5326K, 29% free 16184K/22728K, paused 49ms, total 50ms
,D/AmoledAdjustTimer( 2406): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/dalvikvm( 7242): GC_CONCURRENT freed 6692K, 31% free 17655K/25352K, paused 1ms+9ms, total 52ms
,D/dalvikvm( 7242): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 7242): GC_FOR_ALLOC freed 1216K, 31% free 17551K/25352K, paused 35ms, total 38ms
,I/dalvikvm-heap( 7242): Grow heap (frag case) to 21.631MB for 3713210-byte allocation
,D/dalvikvm( 7242): GC_FOR_ALLOC freed 2528K, 36% free 18649K/28980K, paused 31ms, total 31ms
,W/jxcore-log( 7242): Initializing JXcore engine
,W/jxcore-log( 7242): JXcore engine is ready
,W/jxcore-log( 7242): Starting JXcore engine
,W/jxcore-log( 7242): Platform android
W/jxcore-log( 7242): 
,W/jxcore-log( 7242): Process ARCH arm
W/jxcore-log( 7242): 
,I/jxcore-log( 7242): JXcore Cordova bridge is ready!
I/jxcore-log( 7242): 
,W/jxcore-log( 7242): JXcore engine is started
,I/chromium( 7242): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7242): Toggling radios to true
I/jxcore-log( 7242): 
,D/BluetoothAdapter( 7242): enable(): BT is already enabled..!
,I/WifiManager( 7242): packageName : com.test.thalitest
I/WifiManager( 7242): setWifiEnabled : true
,I/WifiService( 2406): setWifiEnabled: true pid=7242, uid=10560
,W/ActivityManager( 2406): Permission Denial: getCurrentUser() from pid=7242, uid=10560 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2406): Failed getting userId using ActivityManagerNative
W/WifiService( 2406): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7242, uid=10560 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2406): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2406): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2406): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2406): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2406): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2406): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2406): disconnect: pid=7242, uid=10560
I/jxcore-log( 7242): Radios toggled
I/jxcore-log( 7242): 
I/wpa_supplicant( 3981): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7242): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7242): 
,I/jxcore-log( 7242): Perf Test app loaded loaded
I/jxcore-log( 7242): 
,I/jxcore-log( 7242): check test folder
I/jxcore-log( 7242): 
,I/wpa_supplicant( 3981): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7242): found test : ./testFindPeers.js
I/jxcore-log( 7242): 
I/wpa_supplicant( 3981): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3981): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3981): First Scan Start
,W/Settings( 2406): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3981): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2406): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2406): InactiveState{ what=143375 }
D/WifiP2pService( 2406): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling
I/wpa_supplicant( 3981): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3981): Skip scan - already scanning
D/ConnectivityService( 2406): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2406): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/WifiP2pService( 2406): InactiveState{ what=143375 }
D/WifiP2pService( 2406): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2406): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2406): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2406): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2406): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
D/ConnectivityService( 2406): Attempting to switch to mobile
,D/ConnectivityService( 2406): Attempting to switch to BLUETOOTH_TETHER
,I/SELinux ( 7288): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7288):  
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1,
,I/jxcore-log( 7242): found test : ./testSendData.js,
I/jxcore-log( 7242): 
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling,
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2406): Error! unhandled message{ when=-73ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2406): Error! unhandled message{ when=-74ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 7288): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7288):  
I/SELinux ( 7288):  
,I/SELinux ( 7288): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
V/RouteController( 1916): RTNETLINK answers: No such file or directory
,E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7288): >>>>> Normal User
,E/dalvikvm( 7288): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/WifiStateMachine( 2406): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2406): route cmd failed: 
W/NetworkManagementService( 2406): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2406): '
W/NetworkManagementService( 2406): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2406): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2406): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2406): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2406): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2406): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2406): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2406): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2406): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2406): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2406): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2406): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2406): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
D/TimaKeyStoreProvider( 7288): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7288): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/ActivityThread( 7288): Added TimaKesytore provider
,D/NetUtils( 2406): android_net_utils_resetConnections in env=0x7bc2bd78 clazz=0x62f00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2406): resetConnections(wlan0, 3)
,D/dalvikvm( 7288): GC_CONCURRENT freed 2993K, 30% free 9579K/13552K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 7288): WAIT_FOR_CONCURRENT_GC blocked 20ms
,E/SPPClientService( 5567): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5567): [e] exceptionCaught(). NET_TIMEOUT
,V/NativeCrypto( 2848): Read error: ssl=0x7bab98a8: I/O error during system call, Connection timed out
,E/SPPClientService( 5567): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,V/NativeCrypto( 2848): SSL shutdown failed: ssl=0x7bab98a8: I/O error during system call, Broken pipe
,E/SPPClientService( 5567): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5567): [b] ResponseMap empty
,I/System.out( 7288): Inside WakeupProvider
,I/System.out( 7288): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats( 2406): updateIfacesLocked()
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
V/NetworkStats( 2406): performPollLocked(flags=0x1)
,D/ConnectivityService( 2406): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
V/NetworkStats( 2406): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
V/NetworkStats( 2406): performPollLocked() took 21ms
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
,I/chromium( 7242): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/VlingoApplication( 7288): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7288): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7288): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,D/DialogFlow( 7288): initQueue(),
,I/ActivityManager( 2406): Killing 6200:com.sec.android.app.sns3/u0a37 (adj 15): empty #43,
V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002,
,D/Tethering( 2406): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2406): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2406): updateDataUsageMap
,D/CaptivePortalTracker( 2406): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2406): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6609): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6609): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6609): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6609): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6609): noConnectivity : true
,I/DBG_DM  ( 4768): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2406): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7317): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7317):  
,I/SELinux ( 7317): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7317):  
I/SELinux ( 7317):  
,I/SELinux ( 7317): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7317): >>>>> Normal User
,E/dalvikvm( 7317): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,I/wpa_supplicant( 3981): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3981): wlan0: Setting scan request: 8 sec 0 usec
,I/wpa_supplicant( 3981): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
,E/SELinux ( 7317): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7317): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7317): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7317): Added TimaKesytore provider
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3981): Associated with C0.AA.48
D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3981): freq(2412) increment count 2
,I/wpa_supplicant( 3981): meet head of list.
D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3981): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3981): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3981): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2406): interfaceLinkStateChanged wlan0, true
D/WifiNative( 2406): callSECApiVoid - ID [50]
,D/Tethering( 2406): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7317): GC_CONCURRENT freed 2997K, 30% free 9574K/13552K, paused 5ms+5ms, total 43ms
,D/dalvikvm( 7317): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/ActivityManager( 2406): Killing 6273:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2406): InactiveState{ what=143375 }
,D/WifiP2pService( 2406): P2pEnabledState{ what=143375 }
,I/SELinux ( 7331): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7331):  
,I/SELinux ( 7331): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7331):  
I/SELinux ( 7331):  
,I/SELinux ( 7331): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7331): >>>>> Normal User
,E/dalvikvm( 7331): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7331): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7331): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7331): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7331): Added TimaKesytore provider
,I/dhcpcd  ( 7335): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7335): bssid match
,D/dalvikvm( 7331): GC_CONCURRENT freed 3001K, 30% free 9572K/13548K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7331): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2406): Killing 6347:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7350): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7350):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9509K/10532K, paused 4ms+5ms, total 54ms
I/SELinux ( 7350): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7350):  
I/SELinux ( 7350):  
,I/SELinux ( 7350): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7350): >>>>> Normal User
,E/dalvikvm( 7350): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7350): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7350): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9509K/10532K, paused 4ms+5ms, total 39ms
,D/libgps  ( 2406): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2406): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2406): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2406): agps_ril_update_network_availability: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7350): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7350): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9509K/10532K, paused 4ms+5ms, total 37ms
,D/dalvikvm( 7350): GC_CONCURRENT freed 3015K, 30% free 9561K/13552K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7350): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/KLMS-2.3.201 : ( 7350): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7350): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312969899
,I/KLMS-2.3.201 : ( 7350): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2406): Killing 6367:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7362):  
,I/SELinux ( 7362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7362):  
I/SELinux ( 7362):  
,I/SELinux ( 7362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7362): >>>>> Normal User
,E/dalvikvm( 7362): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7362): Added TimaKesytore provider
,D/dalvikvm( 7362): GC_CONCURRENT freed 3014K, 30% free 9565K/13556K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7362): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/SO_AGENT( 7362): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7362): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5835): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5835): [BDLM] already registered in spp
I/SA      ( 5835): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5835): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5835): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5835): [OR] == isSIMCardReady false ==
,I/SA      ( 5835): [SCU] == networkStateCheck == false
,I/SA      ( 5835): [OR] onReceive END
I/ActivityManager( 2406): Killing 5616:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7374):  
,I/SELinux ( 7374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7374):  
I/SELinux ( 7374):  
,I/SELinux ( 7374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7374): >>>>> Normal User
,E/dalvikvm( 7374): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7374): Added TimaKesytore provider
,D/dalvikvm( 7374): GC_CONCURRENT freed 2994K, 30% free 9577K/13548K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7374): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/sCloudBackupApp( 7374): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7374): Other Intent
I/ActivityManager( 2406): Killing 6329:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7387): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7387):  
,I/SELinux ( 7387): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7387):  
I/SELinux ( 7387):  
,I/SELinux ( 7387): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7387): >>>>> Normal User
,E/dalvikvm( 7387): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7387): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7387): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7387): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7387): Added TimaKesytore provider
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4365, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/dalvikvm( 7387): GC_CONCURRENT freed 2998K, 30% free 9577K/13552K, paused 10ms+3ms, total 59ms
,D/dalvikvm( 7387): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/libgps  ( 2406): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2406): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2406): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager,
,D/com.samsung.app( 7387): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create,
,D/com.samsung.app( 7387): [KK AccuPhone]>>> RM:136 [0:0]  V init ,
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/com.samsung.app( 7387): [KK AccuPhone]>>> RM:128 [0:0] updateCityList,
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/com.samsung.app( 7387): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0,
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
I/ActivityManager( 2406): Killing 6343:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,D/WifiP2pService( 2406): InactiveState{ what=143375 }
,D/WifiP2pService( 2406): P2pEnabledState{ what=143375 }
,D/Headlines( 5902): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5902): getCountryCode(): countryCode = PL
,D/WifiStateMachine( 2406): VerifyingLinkState enter
D/Headlines( 5902): Breath.onCreate
,D/Headlines( 5902): Breath timer started. interval : 30000
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7421): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7421):  
,V/AlarmManager( 2406): waitForAlarm result :8,
D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5902): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5902): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5902): requestUpdateNewsWelcomeCard !!! no welcome card
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2406): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2406): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2406): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2406): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2406): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7421): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7421):  
I/SELinux ( 7421):  
,I/SELinux ( 7421): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7421): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7421): >>>>> Normal User
,E/dalvikvm( 7421): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
E/SELinux ( 7421): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling
D/ConnectivityService( 2406): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2406): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2406): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/TimaKeyStoreProvider( 7421): in addTimaSignatureService
D/ConnectivityService( 2406): handleConnectivityChange: setting default proxy info 
,D/TimaKeyStoreProvider( 7421): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7421): Added TimaKesytore provider
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/dalvikvm( 7421): GC_CONCURRENT freed 3002K, 30% free 9578K/13556K, paused 3ms+2ms, total 31ms,
,D/dalvikvm( 7421): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit,
V/NetworkStats( 2406): updateIfacesLocked()
,V/NetworkStats( 2406): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
D/NtpTrustedTime( 2406): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit,
V/NetworkStats( 2406): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit,
V/NetworkStats( 2406): performPollLocked() took 23ms
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2406): currentTimeMillis() cache hit,
,V/WebViewChromium( 7421): Binding Chromium to the background looper Looper (main, tid 1) {423bb238},
,I/chromium( 7421): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7421): Initializing chromium process, renderers=0,
,W/chromium( 7421): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7421): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7421): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 7421): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7421): Mali API Version : 401,
,I/Mali    ( 7421): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,W/GAV2    ( 7421): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/ContextImpl( 7421): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1599623, pollInterval: 10000,
,I/NSApplication( 7421): Starting up...,
,D/Tethering( 2406): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2406): MasterInitialState.processMessage what=3
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/CaptivePortalTracker( 2406): NoActiveNetworkState{ when=-6ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2406): agps_ril_update_network_state: Waiting for IPC connection...
,I/iu.Environment( 5966): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5168): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5168): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
,I/SELinux ( 7474): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7474):  
D/PackageManager( 2406): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SELinux ( 7474): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7474):  
I/SELinux ( 7474):  
,I/SELinux ( 7474): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7474): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7474): >>>>> Normal User
,E/dalvikvm( 7474): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7474): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7474): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7474): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7474): Added TimaKesytore provider
,D/dalvikvm( 7474): GC_CONCURRENT freed 2981K, 30% free 9588K/13548K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7474): WAIT_FOR_CONCURRENT_GC blocked 23ms
,W/WifiP2pStateTracker( 2406): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2406): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2406):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2406): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2406): updateSourceRoutes : no source routing conditions
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,I/SELinux ( 7492): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7492):  
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,W/ActivityManager( 2406): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,I/ActivityManager( 2406): Killing 6010:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7492): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7492):  
I/SELinux ( 7492):  
,I/SELinux ( 7492): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7492): >>>>> Normal User
,E/dalvikvm( 7492): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7492): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7504):  
,D/TimaKeyStoreProvider( 7492): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7492): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7492): Added TimaKesytore provider
,I/ActivityManager( 2406): Killing 6292:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7504):  
I/SELinux ( 7504):  
,I/SELinux ( 7504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7504): >>>>> Normal User
,E/dalvikvm( 7504): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/TimaKeyStoreProvider( 7504): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7504): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7504): Added TimaKesytore provider,
,D/dalvikvm( 7492): GC_CONCURRENT freed 3002K, 30% free 9572K/13552K, paused 5ms+2ms, total 33ms,
,D/dalvikvm( 7492): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/BadgeProvider( 7492): onCreate,
,D/BadgeProvider( 7492): DatabaseHelper,
,D/BadgeProvider( 7492): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge',
,D/Launcher.Model( 2769): reloadBadges entered.,
D/BadgeProvider( 7492): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7492): sendNotify, [notify] : null
,D/BadgeProvider( 7492): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7492): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7492): update, [UpdateCount] : 1
,D/dalvikvm( 7504): GC_CONCURRENT freed 3013K, 30% free 9565K/13556K, paused 3ms+4ms, total 34ms
,D/dalvikvm( 7504): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/hcjo    ( 5987): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5987): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5987): exit::IDLE
,D/InitializeManagerStateMachine( 5987): entry::NETWORK_CHECK
,I/jxcore-log( 7242): BLE advertisement not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 7242): 
D/InitializeManagerStateMachine( 5987): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5987): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5987): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5987): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5987): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5987): entry::SUCCESS
,D/hcjo    ( 5987): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5987): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5987): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5987): exit::SUCCESS
,D/InitializeManagerStateMachine( 5987): entry::IDLE
,E/SPPClientService( 5567): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5567): [SystemStateMoniter] Current Time : 309137
,E/SPPClientService( 5567): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5567): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5567): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5567): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5902): Breath 1881 latestRequest time : 1450312970972 current time : 1450312972855
,D/libgps  ( 2406): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2406): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2406): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2406): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SPPClientService( 5567): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/dalvikvm( 2406): GC_EXPLICIT freed 4535K, 71% free 25518K/87000K, paused 13ms+25ms, total 339ms
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/SPPClientService( 5567): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2406): Killing 6187:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 10
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5567): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,D/PowerManagerService( 2406): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2406
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5567): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6609): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6609): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6609): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6609): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5567): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7350): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7350): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450312973389
,I/KLMS-2.3.201 : ( 7350): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7362): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3434): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3434): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3434): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3434): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7362): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7529): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7529):  
,I/GallerySearchProvider( 3562): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7533):  
I/SELinux ( 7529): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7529):  
I/SELinux ( 7529):  
I/SELinux ( 7529): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7529): >>>>> Normal User
,E/dalvikvm( 7529): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7529): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7529): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7529): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7529): Added TimaKesytore provider
,I/SELinux ( 7533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7533):  
I/SELinux ( 7533):  
,I/SELinux ( 7533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7533): >>>>> Normal User
,E/dalvikvm( 7533): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5835): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5835): [BDLM] already registered in spp
I/SA      ( 5835): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5835): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5835): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5835): [OR] == isSIMCardReady false ==
,I/SA      ( 5835): [SCU] == networkStateCheck == true
,I/SA      ( 5835): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5835): isChinaCountryCode : false
,I/SA      ( 5835): [OR] == networkStateCheck true ==
,I/SA      ( 5835): [OR] GetMyCountryZoneTask
,I/SA      ( 5835): [OR] onReceive END
,I/SA      ( 5835): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 7533): in addTimaSignatureService
,I/SA      ( 5835): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5835): [SSP] query invoked
,D/TimaKeyStoreProvider( 7533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7533): Added TimaKesytore provider
,I/SA      ( 5835): [TPMU] GetMccFromDB : null,
I/SA      ( 5835): [SCU] getMccFromPreferece mcc = 260,
,I/SA      ( 5835): [TPM] isNoProxy(default) : true,
,I/SA      ( 5835): [RC New] Execute method=[GET] start,
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled,
,I/SCloudBackupReceiver( 7374): Other Intent
,D/dalvikvm( 7529): GC_FOR_ALLOC freed 3010K, 30% free 9562K/13552K, paused 41ms, total 42ms,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,D/com.samsung.app( 7387): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/dalvikvm( 7529): GC_CONCURRENT freed 237K, 30% free 9575K/13552K, paused 7ms+10ms, total 48ms,
,D/Headlines( 5902): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5902): getCountryCode(): countryCode = PL,
,D/dalvikvm( 7533): GC_CONCURRENT freed 3002K, 30% free 9573K/13556K, paused 6ms+2ms, total 38ms,
,D/dalvikvm( 7533): WAIT_FOR_CONCURRENT_GC blocked 33ms,
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0,
D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() category size == 0,
D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5902): queryCategory.  mRequest is not initialized.
,D/HeadlinesCardManager( 5902): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5902): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5902): requestUpdateNewsWelcomeCard !!! no welcome card,
,I/iu.Environment( 5966): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/QuickConnect[1.1][2] ( 5168): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,I/System.out( 7331): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/QuickConnect[1.1][2] ( 5168): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
,V/KVNProvider( 7533): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7533): getFindoCursor query string : 
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,D/RCPManagerService( 2406): exchangeData() failure , invalid userId
,D/libgps  ( 2406): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2406): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2406): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/System.out( 7331): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7331): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/KVNProvider( 7533): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5987): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5987): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5987): exit::IDLE
,D/InitializeManagerStateMachine( 5987): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5987): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5987): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5987): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5987): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5987): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5987): entry::SUCCESS
,D/hcjo    ( 5987): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5987): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5987): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5987): exit::SUCCESS
,D/InitializeManagerStateMachine( 5987): entry::IDLE
,E/SPPClientService( 5567): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5567): [SystemStateMoniter] Current Time : 310382
,E/SPPClientService( 5567): [SystemStateMoniter] No Connect : false
,I/System.out( 7331): AsyncTask #1 calls detatch()
,W/System.err( 7331): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7331): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7331): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7331): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7331): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7331): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7331): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7331): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,D/AmoledAdjustTimer( 2406): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
W/System.err( 7331): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7331): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7331): Caused by: java.lang.NullPointerException
W/System.err( 7331): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7331): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7331): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7331): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 7331): 	... 8 more
,I/ActivityManager( 2406): Killing 6223:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5567): GC_CONCURRENT freed 1929K, 23% free 10487K/13532K, paused 6ms+6ms, total 52ms
,E/WifiStateMachine( 2406): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5835): [RC New] [v2liruge] api execute + 770
,I/SA      ( 5835): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5835): AsyncTask #2 calls detatch()
,I/SA      ( 5835): [TPMU] getNetworkMcc : 
,I/SA      ( 5835): [SCU] saveMccToPreferece Start
,I/SA      ( 5835): [SCU] RegionMCC : 260
,I/SA      ( 5835): [SSP] query invoked
,I/SA      ( 5835): [TPMU] GetMccFromDB : null
I/SA      ( 5835): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5835): [SCU] saveMccToPreferece End
,I/SA      ( 5835): [RC New] executeRequest [v2liruge] end. 797
I/SA      ( 5835): [RC New] Execute end
,I/SA      ( 5835): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5835): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5567): [b] __InitReply__,
,I/jxcore-log( 7242): Connected to the server!
I/jxcore-log( 7242): 
,I/chromium( 7242): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63),
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000,
I/TLC_TIMA_PKM_initialize( 2406): initializing...
I/TLC_TIMA_PKM_initialize( 2406): root = 0, root_strlen = 1,
I/TLC_TIMA_PKM_initialize( 2406): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2406): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2406): input max_recvmsg_size = 262196,
I/TZ: mc_tlc_communication( 2406): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2406): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2406): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2406): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2406): device_id = 0x0
I/TZ: mc_tlc_communication( 2406): tlc_open() was called
I/TZ: mc_tlc_communication( 2406): Opening MobiCore device
I/TZ: mc_tlc_communication( 2406): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2406): Opening the session
,I/TZ: mc_tlc_communication( 2406): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2406): Trustlet response is completed
,I/jxcore-log( 7242): --- start :testFindPeers.js---
I/jxcore-log( 7242): 
,I/jxcore-log( 7242): testFindPeers created [object Object]
I/jxcore-log( 7242): 
,I/jxcore-log( 7242): serverPort is 8876,
I/jxcore-log( 7242): 
I/dalvikvm( 7242): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7242): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x0019,
I/dalvikvm( 7242): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7242): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7242): VFY: replacing opcode 0x6e at 0x0020,
D/AndroidRuntime( 7242): Shutting down VM
,W/dalvikvm( 7242): threadid=1: thread exiting with uncaught exception (group=0x4197fc08),
E/AndroidRuntime( 7242): FATAL EXCEPTION: main
E/AndroidRuntime( 7242): Process: com.test.thalitest, PID: 7242
E/AndroidRuntime( 7242): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7242): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:134)
,E/AndroidRuntime( 7242): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:133)
E/AndroidRuntime( 7242): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:183)
E/AndroidRuntime( 7242): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:95)
E/AndroidRuntime( 7242): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:92)
E/AndroidRuntime( 7242): 	at io.jxcore.node.JXcoreExtension$5.Receiver(JXcoreExtension.java:155)
,E/AndroidRuntime( 7242): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7242): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7242): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7242): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7242): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7242): 	,at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7242): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7242): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7242): 	at java.lang.reflect.Method.invoke(Method.java:515)
,E/AndroidRuntime( 7242): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7242): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7242): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2406):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2406): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2406): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2406): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2406): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2406): Killing 6553:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/CrashAnrDetector( 2406): processName: com.test.thalitest
,D/CrashAnrDetector( 2406): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 7242): Sending signal. PID: 7242 SIG: 9
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2406): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2406): mDVFSHelper.acquire()
,I/DBG_DM  ( 4768): [3.19.140541][Line:408][onResume] 
,I/ActivityManager( 2406): Process com.test.thalitest (pid 7242) (adj 9) has died.
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/11)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/11)
I/WindowState( 2406): WIN DEATH: Window{43120658 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/DBG_DM  ( 4768): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4768): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:418][onResume] Postpone Count : 26
,I/DBG_DM  ( 4768): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4768): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2406): sendNotification(2) - 4
,I/DBG_DM  ( 4768): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,I/DBG_DM  ( 4768): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4768): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4768): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4768): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4768): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4768): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2406): semi p:4768,o:t
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2406): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2406): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2406): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2406): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2406): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2406): setHoveringSpenCustomIcon IconType is same.1
W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2406): Got RemoteException sending setActive(false) notification to pid 7242 uid 10560
,D/CustomFrequencyManagerService( 2406): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2406): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2406): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  pkgName : ACTIVITY_RESUME_BOOSTER@8
,I/GAV2    ( 7421): Thread[GAThread,5,main]: No campaign data found.
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2406): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2406) eventTime = 312909
D/PowerManagerService( 2406): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2406 (0x0)
D/PowerManagerService( 2406): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2406, ws=WorkSource{1000}) (elapsedTime=3458)
,D/CustomFrequencyManagerService( 2406): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2406  tag : ACTIVITY_RESUME_BOOSTER@8
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6609): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6609): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6609): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6609): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6609): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6609): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6609): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6609): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6609): [ensureRegistration] - No Samsung account
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2406): level:100, scale:100, status:3, health:9, present:true, voltage: 4368, temperature: 296, technology: Li-ion, AC powered:false, USB powered:false, Wireless powered:false, icon:17303678, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/lights  ( 2406): led_pattern : 0 +
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 2406): [api] [SvcLED] turnOff:: id = 3 (uid: 0 pid: 0) 
D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 2406): turn off LED
D/LightsService( 2406): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 2406): led_pattern : 0 -
,D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/UsbDeviceManager( 2406): handleMessage -> MSG_POWER_STATE = 0
,D/PowerManagerService( 2406): [api] updateIsPoweredLocked : mIsPowered: false mPlugType: 0
I/PowerManagerService( 2406): !@[ps] Screen__On :  powered change
I/PowerManagerService( 2406): Waking up from sleep...
D/PowerManagerService( 2406): Screen Readiness Inspection requested: mNestCount=1
D/PowerManagerService( 2406): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 2406): [s] WAKEFULNESS_AWAKE
D/PowerManagerService( 2406): [s] UserActivityState : 0 -> 1
D/lights  ( 2406): button : 1 +
,D/lights  ( 2406): button : 1 -
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/PowerManagerService( 2406): [PWL] sb acquire: PowerManagerService.Display
D/DisplayPowerController( 2406): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
I/DisplayPowerController( 2406): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 5
D/DisplayPowerController( 2406): [DAB] setLightSensorEnabled : registerListener mLightSensor
I/DisplayPowerController( 2406): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/DisplayPowerController( 2406): [DAB] setLightSensorEnabled : updateAutoBrightnessSEC(false)
D/DisplayPowerController( 2406): [DAB] no lux value from sensor manager
,D/DisplayPowerController( 2406): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/Sensors ( 2406): LightSensor setDelay = 200000000
D/Sensors ( 2406): LightSensor setSensorDelay = 200000000
D/Sensors ( 2406): Light sensor flush: not enabled 0
D/Sensors ( 2406): LightSensor enable = 1
D/Sensors ( 2406): LightSensor enableSensor = 1
D/SensorManager( 2406): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 65558
,I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 1
D/SensorService( 2406): AutoRotationSensor::changed settle time to [1]
D/SensorService( 2406): AutoRotationSensor::activate (ident=0x7ca6f840, enabled=1)
D/SensorService( 2406): AutoRotationSensor::AR_init
I/Sensors ( 2406): HAL: batch Dry Run is complete
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/PowerManagerService( 2406): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 9ms
W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.removeNotification:712 com.android.server.NotificationManagerService.cancelNotificationLocked:2470 com.android.server.NotificationManagerService.access$5100:162 
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
,I/libsuspend( 2406): !@[s] autosuspend_autosleep_disable
I/libsuspend( 2406): !@[s] autosuspend_autosleep_disable done
,I/Sensors ( 2406): HAL:resetDataRates mEnabled=4
,D/SurfaceFlinger( 1921): Screen acquired, type=0 flinger=0x41105550
D/PowerManagerService( 2406): unblankAllDisplays() is called.
D/PowerManagerService( 2406): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/RampAnimator( 2406): Light Animator Finished currentValue=8
D/PowerManagerService( 2406): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 317355
,D/SensorManager( 2406): registerListener :: 1600221811, Screen Orientation Sensor, 66667, 0,  
,I/Sensors ( 2406): HAL: batch Dry Run is complete
,D/SensorManager( 2406): registerListener :: 2, MPL Accelerometer, 200000, 0,  
,V/KeyguardServiceDelegate( 2406): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$32@456a5240)
D/UsbDeviceManager( 2406): sending intent : ACTION_USB_CABLE_STATE : connected = false
,D/NotificationService( 2406): cancelNotificationLocked
,D/NotificationService( 2406):  hasClearableItems
D/NotificationService( 2406):  has clearable items no 
D/NotificationService( 2406): cancelNotificationLocked: cancel alarm
,D/NotificationService( 2406): cancelNotificationLocked: cancel alarm
D/PowerManagerService( 2406): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 25ms
D/STATUSBAR-StatusBarManagerService( 2406): sendNotification(3) - 5
D/KeyguardViewMediator( 2580): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 2580): notifyScreenOnLocked
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:3 health:9
D/KeyguardViewMediator( 2580): handleNotifyScreenOn
D/KeyguardViewManager( 2580): onScreenTurnedOn()
,V/KeyguardServiceDelegate( 2406): **** SHOWN CALLED ****
D/InputDispatcher( 2406): setInputDispatchMode: enabled=1, frozen=0
,I/KeyguardEffectViewMain( 2580): *** KeyguardEffectView getInstance ***
,D/VisualEffectParticleEffect( 2580): KeyguardEffectViewParticleSpace : screenTurnedOn
V/KeyguardViewManager( 2580): send wm null token: host was null
,I/WindowManager( 2406): No lock screen! windowToken=null
,D/VisualEffectParticleEffect( 2580): screenOnAnimationStart,
D/PowerManagerNotifier( 2406): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/PowerManagerService( 2406): Screen Readiness Inspection completed: mNestCount=0
D/DisplayPowerController( 2406): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (10/10),
,I/SELinux ( 7636): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7636):  
D/DisplayPowerController( 2406): !@ElectronBeam exit
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
I/SurfaceFlinger( 1921): id=14 Removed FlectronBea (-2/10)
D/LockPatternUtils( 2580): isPcwEnable = 10
,D/lights  ( 2406): lcd : 8 +
D/LightsService( 2406): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2406) 
,D/lights  ( 2406): lcd : 8 -
D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/DisplayPowerController( 2406): animation target = 8 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/LightsService( 2406): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/PowerManagerService( 2406): [s] mDisplayPowerControllerCallbacks : onStateChanged()
D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/UsbDeviceManager( 2406): received ACTION_POWER_DISCONNECTED = -1
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
,I/SELinux ( 7636): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7636):  
I/SELinux ( 7636):  
,I/SELinux ( 7636): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7636): >>>>> Normal User
,E/dalvikvm( 7636): >>>>> com.sec.android.Kies [ userId:0 | appId:1000 ]
,E/SELinux ( 7636): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/SensorService( 2406): AutoRotationSensor::process: Acc  eventTimestamp = 317426697321, previousAccTimestamp = 68723084196, difference = 248703613125 
,D/SensorService( 2406): AutoRotationSensor::reset oldrotation = [100], initState = [1]
,D/TimaKeyStoreProvider( 7636): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7636): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7636): Added TimaKesytore provider
,D/DisplayPowerController( 2406): [api] [DAB] onSensorChanged : 1st lux : 0.0
,D/DisplayPowerController( 2406): [DAB] updateAutoBrightnessSEC : 8(8.0)    0.0 < 0.0 < 15.0 (0.0)
,D/SensorService( 2406): AutoRotationSensor::process: Acc  eventTimestamp = 317492872257, previousAccTimestamp = 68723084196, difference = 248769788061 
D/SensorService( 2406):  [AR] 0.3 -0.0 9.9
,D/SensorService( 2406): AutoRotationSensor::process: Ar_SensorChanged oldrotation = [100], rotation = [255]
,D/SurfaceControl( 2406): Excessive delay in unblankDisplay() while turning screen on: 246ms
,D/MISC PowerHAL( 2406): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/input/input1/enabled: 1
D/PowerManagerService( 2406): Excessive delay in mDisplayManagerService.unblankAllDisplaysFromPowerManager(): 247ms
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/input/input1/enabled: 1
D/MISC PowerHAL( 2406): miscpower_set_interactive: /sys/class/input/input0/enabled
,D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/input/input0/enabled: 1
,D/LightsService( 2406): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2406) 
,D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 2406): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/PalmMotionService( 2406): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotionService( 2406): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 2406):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/SSRMv2:TSP:AirViewOnOff( 2406): SettingsAirViewInfo:: 000000000
,D/SamsungIME( 2987): showDlgMsgBox : false true true
,I/NfcService( 2757): applyRouting return - 2 
,E/NfcService( 2757): callback == null
,I/DBG_DM  ( 4768): [3.19.140541][Line:408][onResume] 
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.USER_PRESENT
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling
,I/DBG_DM  ( 4768): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NotificationService( 2406): ACTION_SCREEN_ON
,D/LightsService( 2406): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2406) 
D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 2406): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=on)
,I/DBG_DM  ( 4768): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/input/input0/enabled: 1
D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
D/PowerManagerService-JNI( 2406): Excessive delay in MISC setInteractive(true) while turning screen on: 164ms
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 80 900000:93 1300000:98
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 39000 1300000:79000
,I/SecExternalDisplayIntents_Java( 2406): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
D/PowerManagerService( 2406): Excessive delay in nativeSetInteractive(true): 166ms
D/PowerManagerService( 2406): SecHardwareInterface.setBatteryADC : true
,I/DBG_DM  ( 4768): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:418][onResume] Postpone Count : 26
,D/IpRemoteDisplayController( 2406): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 2406): Bridge Server is not available
,I/DBG_DM  ( 4768): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/PersonaManagerService( 2406): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 2406): MSG_ACTION_SCREEN_ON called
,D/dalvikvm( 7636): GC_CONCURRENT freed 2999K, 30% free 9571K/13552K, paused 8ms+2ms, total 39ms
,D/dalvikvm( 7636): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/NfcService( 2757): NFC: Screen On & Cover Open
,I/NfcService( 2757): applyRouting return - 2 
,E/NfcService( 2757): callback == null
,I/KIES_RECEIVE( 7636): [APK BnR] Receive KIES_USB_DISCONNECT
W/ContextImpl( 7636): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1863 android.content.ContextWrapper.stopService:511 android.content.ContextWrapper.stopService:511 com.sec.android.Kies.kies_receiver.onReceive:170 android.app.ActivityThread.handleReceiver:2698 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/DBG_DM  ( 4768): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
D/STATUSBAR-NetworkController( 2580): onSignalStrengthsChanged signalStrength=SignalStrength: 99 -1 -1 -1 -1 -1 -1 99 2147483647 2147483647 2147483647 2147483647 2147483647 gsm|lte 0x0 level=0
,E/TranscodeReceiver( 7529): onReceive : android.intent.action.ACTION_POWER_DISCONNECTED
,D/videowall-Global( 7529): core_num = 4
,D/dalvikvm( 7529): No JNI_OnLoad found in /system/lib/libsavsff.so 0x423b8b48, skipping init
,I/DBG_DM  ( 4768): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/linker  ( 7529): libvwengine.so has text relocations. This is wasting memory and is a security risk. Please fix.
W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2406): sendNotification(2) - 4
,D/videowall-Global( 7529): density : 2.0 width : 720 height : 1280 Raw width : 720 Raw height : 1280
,D/videowall-Global( 7529): dsp : 720, swkey : false, Cores : 4, Clock : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 26
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1589608, pollInterval: 10000
,I/DBG_DM  ( 4768): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/SELinux ( 7651): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7651):  
,I/DBG_DM  ( 4768): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4768): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(8)
,D/checkbox( 4768): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4768): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,I/DBG_DM  ( 4768): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4768): setTransGradationMode to true
D/StatusBarManagerService( 2406): semi p:4768,o:t
,D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 10% free 9509K/10532K, paused 3ms+4ms, total 47ms
,I/SELinux ( 7651): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7651):  
I/SELinux ( 7651):  
,I/SELinux ( 7651): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
E/dalvikvm( 7651): >>>>> Normal User
,E/dalvikvm( 7651): >>>>> com.android.chrome [ userId:0 | appId:10085 ]
,E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = chrome
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9509K/10532K, paused 3ms+4ms, total 30ms
,D/TimaKeyStoreProvider( 7651): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7651): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7651): Added TimaKesytore provider,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 10% free 9509K/10532K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 6454): GC_CONCURRENT freed 2543K, 26% free 10073K/13584K, paused 4ms+5ms, total 47ms
,D/dalvikvm( 7651): GC_CONCURRENT freed 3004K, 30% free 9572K/13552K, paused 3ms+1ms, total 24ms,
,D/dalvikvm( 7651): WAIT_FOR_CONCURRENT_GC blocked 21ms,
,D/CaptivePortalTracker( 2406): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
,D/CaptivePortalTracker( 2406): Checking http://216.58.209.46/generate_204,
D/ConnectivityService( 2406): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,E/Watchdog( 2406): !@Sync 10
I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(3)
,D/CaptivePortalTracker( 2406): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2406): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2406): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2406): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2406): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0,
,I/SELinux ( 7670): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7670):  
I/ActivityManager( 2406): Killing 6474:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/QuickConnect[1.1][2] ( 5168): PeriphService.mBroadcastReceiver - SCREEN_ON when user = 0,
,V/QuickConnect[1.1][2] ( 5168): BleHelper.shouldScanBleBg - ,
D/QuickConnect[1.1][2] ( 5168): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>,
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
V/QuickConnect[1.1][2] ( 5168): BleHelper.shouldScanBleFg - 
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
D/QuickConnect[1.1][2] ( 5168): BleHelper.startScan - propDisableScan = 0
D/QuickConnect[1.1][2] ( 5168): BleHelper.startScan - bluetoothActionState = 0,
D/QuickConnect[1.1][2] ( 5168): BleHelper.startScan - shouldScanBleBg = false
,D/QuickConnect[1.1][2] ( 5168): BleHelper.startScan - shouldScanBleFg = false,
,I/SELinux ( 7670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7670):  
I/SELinux ( 7670):  
I/SELinux ( 7670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7670): >>>>> Normal User
,E/dalvikvm( 7670): >>>>> com.google.android.apps.uploader [ userId:0 | appId:10117 ]
D/daemonapp( 5368): [MSC_Daemon]>>> WU:1159 [0:0] cDayONight() ::: sunrise is null 
D/daemonapp( 5368): [MSC_Daemon]>>> WU:1175 [0:0] cDayONight() ::: sunset is null 
,E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/PowerManagerService( 2406): [PWL] sb release: PowerManagerService.Broadcasts
,D/TimaKeyStoreProvider( 7670): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7670): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7670): Added TimaKesytore provider
,D/dalvikvm( 7670): GC_CONCURRENT freed 3007K, 30% free 9567K/13552K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7670): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/iu.Environment( 5966): update battery state; isPlugged? false*
,I/iu.SyncManager( 5966): SYNC; picasa accounts
D/PicasaUploader( 7670):    wifiOnlyPhoto changed to true
D/PicasaUploader( 7670):    wifiOnlyVideo changed to true
,D/PicasaUploader( 7670):    syncOnBattery changed to true
,D/PicasaUploaderSync( 7670): sync account database
I/ActivityManager( 2406): Killing 6583:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/iu.Environment( 3279): update battery state; isPlugged? false*
,I/iu.UploadsManager( 5966): num queued entries: 0
,I/iu.UploadsManager( 5966): num updated entries: 0
,I/iu.SyncManager( 5966): NEXT; no task
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_DISCONNECTED}]
,I/iu.UploadsManager( 3279): num queued entries: 0
,I/iu.UploadsManager( 3279): num updated entries: 0
,I/iu.SyncManager( 3279): NEXT; no task
,D/PicasaUploaderSync( 7670): accounts in DB=1
,I/GCoreUlr( 2735): DispatchingService.onCreate()
D/PicasaUploaderSyncManager( 7670): active network: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/PicasaUploaderSyncManager( 7670): background data: true
,D/PicasaUploaderSyncManager( 7670): battery info: false
,D/dalvikvm( 2735): GC_CONCURRENT freed 1581K, 18% free 12145K/14780K, paused 4ms+12ms, total 77ms
,D/LockPatternUtils( 2580): isPcwEnable = 10
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_DISCONNECTED
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:44 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
D/comsamsunglog( 5368): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 5368): [MSC_Daemon]>>> daemonapp [Version : 14052601 ] [ 1 ] 
D/comsamsunglog( 5368): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 5368): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:85 [0:0] c:null, r:3
,D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:362 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:365 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:366 [0:0] [ASO][NUT] = 1450328400000
D/daemonapp( 5368): [MSC_Daemon]>>> WDSM:367 [0:0] [ASO][CT] = 1450312982271
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:1485 [0:0] PakNme size = 1
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:236 [0:0] regintype : EUR
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:292 [0:0] cp type is : cp_eng
,D/daemonapp( 5368): [MSC_Daemon]>>> WU:1488 [0:0] CP Name cp_eng
,D/daemonapp( 5368): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_DISCONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,D/lights  ( 2406): button : 0 +
,D/lights  ( 2406): button : 0 -
,D/SSRMv2:TSP:AirViewOnOff( 2406): SettingsAirViewInfo:: 000000000
,D/PreloadUpdateManagerStateMachine( 5987): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5987): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5987): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5987): AutoUpdateTriggerManager:REQUEST2:requestInterval
,I/Volley  ( 5987): RestApi Request Add : 2307
,D/dalvikvm( 5987): GC_CONCURRENT freed 2549K, 26% free 10063K/13588K, paused 3ms+5ms, total 46ms
,D/dalvikvm( 5987): GC_CONCURRENT freed 2017K, 27% free 10036K/13588K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 5987): GC_CONCURRENT freed 1848K, 25% free 10223K/13588K, paused 2ms+3ms, total 33ms
,D/PreloadUpdateManagerStateMachine( 5987): execute::CHECK_TIMEOUT_FOR_UPDATE:EXECUTE
,I/System.out( 5987): Thread-514(HTTPLog):isShipBuild true
,I/System.out( 5987): Thread-514(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/SensorService( 2406):   0.3 -0.0 9.8
,D/AmoledAdjustTimer( 2406): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/hcjo    ( 5987): AutoUpdateTriggerManager:REQUEST2:setInterval:86400000
,D/hcjo    ( 5987): AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
,D/PreloadUpdateManagerStateMachine( 5987): execute::CHECK_TIMEOUT_FOR_UPDATE:TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5987): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5987): entry::REQ_UPDATE_CHECK
,I/Volley  ( 5987): RestApi Request Add : 2315
,I/qtaguid ( 5987): Failed write_ctrl(u -1) res=-1 errno=9
I/qtaguid ( 5987): Untagging socket -1 failed errno=-9
,W/NetworkManagementSocketTagger( 5987): untagSocket(-1) failed with errno -9
,D/PreloadUpdateManagerStateMachine( 5987): execute::REQ_UPDATE_CHECK:REQUEST_SUCCESS
D/PreloadUpdateManagerStateMachine( 5987): exit::REQ_UPDATE_CHECK
D/PreloadUpdateManagerStateMachine( 5987): entry::NOTIFY_NOTIFICATION
D/PreloadUpdateManagerStateMachine( 5987): exit::NOTIFY_NOTIFICATION
,D/PreloadUpdateManagerStateMachine( 5987): entry::FINISH
D/PreloadUpdateManagerStateMachine( 5987): exit::FINISH
,D/PreloadUpdateManagerStateMachine( 5987): entry::IDLE
,I/ActivityManager( 2406): Waited long enough for: ServiceRecord{444cbd68 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SensorService( 2406):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2406): Waited long enough for: ServiceRecord{44c43ee8 u0 com.sec.spp.push/.PushClientService}
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/SensorService( 2406):   0.3 0.0 9.9
,D/BatteryService( 2406): level:100, scale:100, status:2, health:2, present:true, voltage: 4361, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UsbDeviceManager( 2406): handleMessage -> MSG_POWER_STATE = 1
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/PowerManagerService( 2406): [api] updateIsPoweredLocked : mIsPowered: true mPlugType: 2
D/PowerUI ( 2580): Overvoltage/Undervoltage (recovered) so turn on the screen.
D/PowerManagerService( 2406): [api] [s] wakeUp (uid: 10019 pid: 2580) eventTime = 327314
D/PowerUI ( 2580): playSound : 1
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,V/Vibrator( 2580): Called vibrateImmVibe(int) API - PUID: 10019, PackageName: com.android.keyguard
,V/Vibrator( 2580): vibrateImmVibe - PUID: 10019, PackageName: com.android.keyguard, type: 10, magType: TouchMagnitude
V/VibratorService( 2406): vibrateImmVibeMagnitudeType - magnitudeType: TouchMagnitude
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
V/VibratorService( 2406): vibrate - package: com.android.keyguard, ms: 100, token: null
D/VibratorService( 2406): JNI vibratorOff()
D/VibratorService( 2406): JNI vibratorOn() : 100
D/PowerUI ( 2580): RINGER_MODE_VIBRATE
I/EntropyMixer( 2406): Writing entropy...
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/UsbDeviceManager( 2406): sending intent : ACTION_USB_CABLE_STATE : connected = true
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,E/TranscodeReceiver( 7529): onReceive : android.intent.action.ACTION_POWER_CONNECTED
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/AudioFlinger( 1926): sleepTime is reduced to minimum forcely
,I/SCloudBackupReceiver( 7374): Other Intent
,D/TranscodeService( 7529): onCreate()
,D/PicasaUploaderSyncManager( 7670): battery info: true
,D/dalvikvm( 7529): No JNI_OnLoad found in /system/lib/libsavsvc.so 0x423b8b48, skipping init
,D/dalvikvm( 7529): No JNI_OnLoad found in /system/lib/libsavscmn.so 0x423b8b48, skipping init
I/iu.Environment( 5966): update battery state; isPlugged? true*
,D/dalvikvm( 7529): No JNI_OnLoad found in /system/lib/libsthmb.so 0x423b8b48, skipping init
,I/iu.UploadsManager( 5966): num queued entries: 0
,I/iu.UploadsManager( 5966): num updated entries: 0
D/TranscodeService( 7529): power? : true / screen off : false
,D/TranscodeService( 7529): releaseTranscodeThread.
,I/iu.SyncManager( 5966): NEXT; no task
,D/VibratorService( 2406): JNI vibratorOff()
I/iu.FingerprintManager( 5966): Start processing all media
I/iu.FingerprintManager( 5966): Start processing media store URI: content://media/external/images/media
,I/iu.Environment( 3279): update battery state; isPlugged? true*
,I/iu.UploadsManager( 3279): num queued entries: 0
,I/iu.FingerprintManager( 5966): Start processing media store URI: content://media/external/video/media
,I/iu.UploadsManager( 3279): num updated entries: 0
,I/iu.SyncManager( 3279): NEXT; no task
E/NetworkScheduler.SchedulerReceiver( 2848): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 2848): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/GCoreUlr( 2735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.ACTION_POWER_CONNECTED}]
,I/iu.FingerprintManager( 3279): Start processing all media
,I/iu.FingerprintManager( 5966): Start processing media store URI: content://media/phoneStorage/images/media
,I/iu.FingerprintManager( 3279): Start processing media store URI: content://media/external/images/media
,I/GCoreUlr( 2735): DispatchingService.onCreate()
,I/iu.FingerprintManager( 5966): Start processing media store URI: content://media/phoneStorage/video/media
,I/iu.FingerprintManager( 3279): Start processing media store URI: content://media/external/video/media
,I/iu.FingerprintManager( 5966): Finished generating fingerprints; 0.082 seconds
,I/iu.FingerprintManager( 5966):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/iu.FingerprintManager( 3279): Start processing media store URI: content://media/phoneStorage/images/media
,D/dalvikvm( 5966): GC_CONCURRENT freed 558K, 6% free 26790K/28324K, paused 5ms+16ms, total 70ms
,D/dalvikvm( 5966): WAIT_FOR_CONCURRENT_GC blocked 52ms
,D/dalvikvm( 2721): GC_EXPLICIT freed 352K, 27% free 9968K/13540K, paused 3ms+8ms, total 68ms
,I/iu.FingerprintManager( 3279): Start processing media store URI: content://media/phoneStorage/video/media
I/iu.FingerprintManager( 3279): Finished generating fingerprints; 0.130 seconds
,I/iu.FingerprintManager( 3279):   numSeen=0 numGenerated=0 numDeleted=0 numFailed=0
,I/GCoreUlr( 2735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.ACTION_POWER_CONNECTED
,I/GCoreUlr( 2735): WorldUpdater:android.intent.action.ACTION_POWER_CONNECTED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 2735): Unbound from all location providers
,I/GCoreUlr( 2735): Place inference reporting - stopped
,I/GCoreUlr( 2735): DispatchingService.onDestroy()
,I/GCoreUlr( 2735): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 2735): Unbound from all location providers,
,I/GCoreUlr( 2735): Place inference reporting - stopped,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1579602, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0,
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2,
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2,
,D/SensorService( 2406):   0.3 0.0 9.9,
,D/AmoledAdjustTimer( 2406): prevTemp = 296, currTemp = 297, prevStep = 4, currStep = 4,
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2,
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2,
,I/ActivityManager( 2406): Waited long enough for: ServiceRecord{42ecf530 u0 com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService},
,D/SensorService( 2406):   0.3 -0.0 9.8,
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false),
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2,
,D/SensorService( 2406):   0.3 -0.0 9.9,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/PowerManagerService( 2406): [api] acquire WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.addNotification:676 com.android.server.NotificationManagerService$7.run:2157 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2406): sendNotification(1) - 5
,D/NotificationService( 2406): Sending broadcast with sbn as extra = StatusBarNotification(pkg=com.android.systemui user=UserHandle{-1} id=5 tag=null score=0: Notification(pri=0 icon=7f0200a5 contentView=com.android.systemui/0x1090080 vibrate=null sound=null defaults=0x0 flags=0x2 when=0 ledARGB=0x0 contentIntent=Y deleteIntent=N contentTitle=4 contentText=38 originalPackageName=N tickerText=38 kind=[null]))
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.NotificationManagerService$7.run:2187 android.os.Handler.handleCallback:733 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:146 
D/RCPManagerService( 2406): NotificationReceiver onReceive()
D/RCPManagerService( 2406):  NotificationReceiver sbn.getPackageName() com.android.systemui sbn.getUser().getIdentifier() -1
D/RCPManagerService( 2406): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-sanitize-data ; token = 4294967298406
D/RCPManagerService( 2406): getPolicy: policy value returned = false
D/RCPManagerService( 2406): going to get the app label for pkg == com.android.systemui
D/RCPManagerService( 2406): app label == com.android.systemui
,D/RCPManagerService( 2406): getPolicy: Policy checking block entered for Notifications; for user/persona = -1 ; Policy = knox-export-data ; token = 4294967298406
D/RCPManagerService( 2406): getPolicy: policy value returned = true
D/RCPManagerService( 2406): Calling User is -1
,D/RCPManagerService( 2406): userid of SBN ==-1
D/UserManagerService( 2406): User -1does not exists!!
E/PersonaManagerService( 2406): returning null in  getPersonasForUser
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:2
,D/ProgressBar( 2580): setProgressDrawable drawableHeight = 12
,D/PhoneStatusBar( 2580): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@424073c8
,D/BatteryMeterView( 2580): onDraw batteryColor : -1
,D/dalvikvm( 2580): GC_CONCURRENT freed 15713K, 33% free 33931K/50616K, paused 14ms+10ms, total 98ms
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(44)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1569588, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/SensorService( 2406):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2406): prevTemp = 297, currTemp = 298, prevStep = 4, currStep = 4
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(59)
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(6)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,I/ActivityManager( 2406): Waited long enough for: ServiceRecord{43115810 u0 com.sec.android.app.videoplayer/.videowall.TranscodeService}
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2406):   0.3 -0.0 9.9
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(60)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/display ( 1921): [DYNAMIC_RECOMP] HWC_2_GLES by low FPS(0)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/SensorService( 2406):   0.3 -0.0 9.9
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1559575, pollInterval: 10000
,E/Watchdog( 2406): !@Sync 11
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0
,D/SensorService( 2406):   0.3 -0.0 9.9
,D/AmoledAdjustTimer( 2406): prevTemp = 298, currTemp = 299, prevStep = 4, currStep = 4
,D/PowerManagerService( 2406): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 2406): animation target = 2 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 2406): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/RampAnimator( 2406): Light Animator Finished currentValue=2
D/lights  ( 2406): lcd : 2 +
,D/lights  ( 2406): lcd : 2 -
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2406):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2406): waitForAlarm result :4
,V/AlarmManager( 2406): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/SELinux ( 7708): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7708):  
,I/SELinux ( 7708): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7708):  
I/SELinux ( 7708):  
,I/SELinux ( 7708): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7708): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7708): >>>>> Normal User
,E/dalvikvm( 7708): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7708): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7708): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7708): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7708): Added TimaKesytore provider
,D/dalvikvm( 7708): GC_CONCURRENT freed 3011K, 30% free 9565K/13556K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7708): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5902): Breath 44840 latestRequest time : 1450312973819 current time : 1450313018659
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SensorService( 2406):   0.3 -0.0 9.9
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/PowerManagerService( 2406): [s] UserActivityState : 2 -> 0
I/PowerManagerService( 2406): [PWL] On : 317327 (39984 ms ago)
I/PowerManagerService( 2406): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x0
,I/PowerManagerService( 2406): [PWL]  SCREEN_DIM_WAKE_LOCK           'PowerUI' ACQUIRE_CAUSES_WAKEUP (uid=10019, pid=2580, ws=null) (elapsedTime=19974)
,D/PowerManagerService( 2406): [api] release WakeLock flags=0x10000006 tag=PowerUI uid=10019 pid=2580 (0x0)
I/PowerManagerService( 2406): Nap time...
,D/PowerManagerService( 2406): [s] WAKEFULNESS_NAPPING
I/PowerManagerService( 2406): !@[ps] Screen__Off(2) :  dream finished from Napping
I/PowerManagerService( 2406): Going to sleep due to screen timeout...
,D/PowerManagerService( 2406): [s] WAKEFULNESS_ASLEEP
,D/DisplayPowerController( 2406): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
,I/DisplayPowerController( 2406): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/Sensors ( 2406): LightSensor enable = 0
,D/Sensors ( 2406): LightSensor enableSensor = 0
D/DisplayPowerController( 2406): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/DisplayPowerController( 2406): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/SensorManager( 2406): unregisterListener ::   
I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),-1 flag=20004, FlectronBea
,I/Sensors ( 2406): HAL:resetDataRates mEnabled=4
,D/DisplayPowerController( 2406): !@ElectronBeam entry
D/SensorManager( 2406): unregisterListener ::   
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/lights  ( 2406): lcd : 0 +
,D/lights  ( 2406): lcd : 0 -
D/MISC PowerHAL( 2406): miscpower_set_interactive: /sys/class/input/input1/enabled
,D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/input/input1/enabled: 0
D/PowerManagerService( 2406): blankAllDisplays() is called.
D/PowerManagerService( 2406): [s] mDisplayPowerControllerCallbacks : onStateChanged()
,D/PowerManagerService( 2406): [PWL] sb acquire: PowerManagerService.Broadcasts
D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/input/input1/enabled: 0
V/WindowOrientationListener( 2406): WindowOrientationListener disabled
D/MISC PowerHAL( 2406): miscpower_set_interactive: /sys/class/input/input0/enabled
D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/input/input0/enabled: 0
D/SensorService( 2406): AutoRotationSensor::activate (ident=0x7ca6f840, enabled=0)
I/Sensors ( 2406): HAL: batch Dry Run is complete
,D/KeyguardViewMediator( 2580): onScreenTurnedOff(3)
,D/PowerManagerService( 2406): [PWL] sb release: PowerManagerService.Display
D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/input/input0/enabled: 0
D/MISC PowerHAL( 2406): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 2406): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/timer_rate: 20000
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/hispeed_freq: 900000
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/target_loads: 95
D/SEC PowerHAL( 2406): sysfs_write +: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/SEC PowerHAL( 2406): sysfs_write -: /sys/devices/system/cpu/cpufreq/interactive/above_hispeed_delay: 119000
,D/PowerManagerService( 2406): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/SensorManager( 2406): unregisterListener ::   
D/InputDispatcher( 2406): setInputDispatchMode: enabled=0, frozen=0
D/SurfaceFlinger( 1921): Screen released, type=0 flinger=0x41105550
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SurfaceControl( 2406): Excessive delay in blankDisplay() while turning screen off: 215ms
I/libsuspend( 2406): !@[s] autosuspend_autosleep_enable
,I/libsuspend( 2406): !@[s] autosuspend_autosleep_enable done
D/PowerManagerService( 2406): Excessive delay in mDisplayManagerService.blankAllDisplaysFromPowerManager(): 216ms
I/PowerManagerService( 2406): [PWL] Off : 0s ago
I/PowerManagerService( 2406): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2406): [PWL]     mWakeLockSummary : 0x1
I/PowerManagerService( 2406): [PWL]       PARTIAL_WAKE_LOCK              'ActivityManager-Sleep' (uid=1000, pid=2406, ws=null) (elapsedTime=207)
I/PowerManagerService( 2406): [PWL]   PowerManagerService.Broadcasts: ref count=1
D/PowerManagerService( 2406): SecHardwareInterface.setBatteryADC : false
,I/display ( 1921): [DYNAMIC_RECOMP] GLES_2_HWC by high FPS(29)
,I/DBG_DM  ( 4768): [3.19.140541][Line:400][onPause] 
,I/SQLiteSecureOpenHelper( 4188): getWritableDatabase(pwd)
,I/SQLiteSecureOpenHelper( 4188): getDatabaseLocked(b,b,pwd)...
,D/KeyguardViewMediator( 2580): setting alarm to turn off keyguard, seq = 2
D/LightsService( 2406): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 2406) 
D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 5
D/Sensors ( 2406): LightSensor setDelay = 200000000
D/Sensors ( 2406): LightSensor setSensorDelay = 200000000
,D/Sensors ( 2406): Light sensor flush: not enabled 0
D/Sensors ( 2406): LightSensor enable = 1
,D/Sensors ( 2406): LightSensor enableSensor = 1
,D/SensorManager( 2406): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
D/BatteryService( 2406): turn on LED for fully charged
D/VibratorService( 2406): JNI vibratorOff()
,I/WifiTrafficPoller( 2406): evaluateTrafficStatsPolling
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1549555, pollInterval: 10000
,D/STATUSBAR-NotificationService( 2406): ACTION_SCREEN_OFF
,D/LightsService( 2406): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 2406) 
,D/LightsService( 2406): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
I/AudioHardwareTinyALSA( 1926): setParameters(screen_state=off)
I/SecExternalDisplayIntents_Java( 2406): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 2406): intent received android.intent.action.SCREEN_OFF
,D/IpRemoteDisplayController( 2406): Bridge Server is not available
,D/PersonaManagerService( 2406): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 2406): MSG_ACTION_SCREEN_OFF called
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is received!!!! 
D/STATUSBAR-PhoneStatusBar( 2580): makeExpandedInvisible
D/PhoneStatusBarView( 2580): marqueeStatusBar:122, mClearCover:0
D/STATUSBAR-PhoneStatusBar( 2580):      ACTION_SCREEN_OFF is finished!!!! 
,I/NfcService( 2757): applyRouting return - 2 
,E/NfcService( 2757): callback == null
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/Sensors ( 2406): LightSensor enable = 0
,D/Sensors ( 2406): LightSensor enableSensor = 0
D/SensorManager( 2406): unregisterListener ::   
,D/lights  ( 2406): led_pattern : 5 +
D/LightsService( 2406): [SvcLED]  onSensorChanged::light value = 0
,D/lights  ( 2406): led_pattern : 5 -
D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 2406): GC_CONCURRENT freed 3702K, 71% free 25758K/87000K, paused 14ms+29ms, total 261ms
,D/dalvikvm( 2406): WAIT_FOR_CONCURRENT_GC blocked 152ms
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 2406): GC_EXPLICIT freed 335K, 71% free 25454K/87000K, paused 10ms+18ms, total 238ms
,D/LockPatternUtils( 2580): isPcwEnable = 10
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0
,D/QuickConnect[1.1][2] ( 5168): PeriphService.mBroadcastReceiver - SCREEN_OFF when user = 0
,V/QuickConnect[1.1][2] ( 5168): BleHelper.shouldScanBleBg - 
D/QuickConnect[1.1][2] ( 5168): Utils.getFromDb -  Key[quick_connect_allow_connect], isEnabled [0] /   <0 : Disable, 1 : Enable>
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
V/QuickConnect[1.1][2] ( 5168): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@423cadf8
D/QuickConnect[1.1][2] ( 5168): BleHelper.stopScan - force = true
,D/QuickConnect[1.1][2] ( 5168): BleHelper.stopScan - shouldScanBleBg = false
I/QuickConnect[1.1][2] ( 5168): BleHelper.stopScan - call stopLeScan()
D/BluetoothAdapter( 5168): stopLeScan()
,D/QuickConnect[1.1][2] ( 5168): BleHelper.stopScan - call stopLeScan() complete
,E/TranscodeReceiver( 7529): onReceive : android.intent.action.SCREEN_OFF
,D/TranscodeService( 7529): power? : true / screen off : true
D/PowerManagerService( 2406): [PWL] sb release: PowerManagerService.Broadcasts
,D/TranscodeService( 7529): Music is = false
,D/TranscodeService( 7529): runvideoplayer is false
,D/TranscodeService( 7529): Thread start
,D/TranscodeService( 7529): WakeLock.acquire()
,D/videowall-FileMgr( 7529): thumbnailDBSync -1
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onInitialize : 2858
,D/WVMDrmPlugIn( 1924): WVMDrmPlugin::onSetOnInfoListener : add 2858
I/PrGenericPlugin( 1924): [A] ENTER onInitialize : 0xb2a
,I/PrGenericPlugin( 1924): [A] LEAVE onInitialize : 0xb2a
,D/TranscodeService( 7529): Thread end
,D/TranscodeService( 7529): WakeLock.release()
,D/TranscodeService( 7529): onDestroy()
,D/TranscodeService( 7529): releaseTranscodeThread.
,V/ApplicationPolicy( 2406): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.videoplayer
,I/ActivityManager( 2406): Killing 6596:com.android.musicfx/u0a24 (adj 15): empty #43
,D/AmoledAdjustTimer( 2406): prevTemp = 299, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2406): waitForAlarm result :4,
,D/KeyguardViewMediator( 2580): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2,
,D/LockPatternUtils( 2580): isPcwEnable = 10,
,D/KeyguardViewMediator( 2580): in doKeyguardLocked mIsRollUp false null
,D/PersonaManager( 2580): isKioskContainerExistOnDevice,
,D/LockPatternUtils( 2580): isPcwEnable = 10,
D/LockPatternUtils( 2580): isPcwEnable = 10
,D/KeyguardViewMediator( 2580): doKeyguard: not showing because lockscreen is off,
,V/AlarmManager( 2406): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/PowerManagerService( 2406): [PWL] Off : 5s ago,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1539542, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2406): [PWL] Off : 15s ago,
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/BatteryService( 2406): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1529528, pollInterval: 10000
,E/Watchdog( 2406): !@Sync 12
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2406): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2406): [PWL] Off : 30s ago,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1519517, pollInterval: 10000,
,V/AlarmManager( 2406): waitForAlarm result :4,
,V/AlarmManager( 2406): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5902): Breath 78318 latestRequest time : 1450312973819 current time : 1450313052137,
,D/AmoledAdjustTimer( 2406): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,V/AlarmManager( 2406): waitForAlarm result :8,
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5902): Breath 87182 latestRequest time : 1450312973819 current time : 1450313061001,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2406): stay LED for fully charged
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1509507, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2406): [PWL] Off : 50s ago,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1499497, pollInterval: 10000,
,E/Watchdog( 2406): !@Sync 13,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1489487, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2406): waitForAlarm result :8,
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5902): Breath 117181 latestRequest time : 1450312973819 current time : 1450313091000,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2406): mCoverManager.getCoverState() : true,
,D/BatteryService( 2406): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1479478, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2406): [PWL] Off : 75s ago,
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1469467, pollInterval: 10000,
,E/Watchdog( 2406): !@Sync 14,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1459457, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,V/AlarmManager( 2406): waitForAlarm result :8,
,D/Headlines( 5902): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5902): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5902): Breath 147178 latestRequest time : 1450312973819 current time : 1450313120997
,D/Headlines( 5902): stop ,
,D/Headlines( 5902): Breath.onDestroy : ,
I/ActivityManager( 2406): Killing 6624:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2406): stay LED for fully charged
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1449444, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2406): [PWL] Off : 105s ago,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1439431, pollInterval: 10000,
,E/Watchdog( 2406): !@Sync 15,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1429418, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1419400, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2406): [PWL] Off : 140s ago,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1409388, pollInterval: 10000,
,E/Watchdog( 2406): !@Sync 16,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1399378, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1389364, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2406): !@Sync 17,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1379351, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2406): [PWL] Off : 180s ago,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1369338, pollInterval: 10000,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1359324, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2406): !@Sync 18,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1349309, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1339295, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1329280, pollInterval: 10000,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true,
,D/BatteryService( 2406): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2406): [PWL] Off : 225s ago,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2406): !@Sync 19,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1319267, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1309252, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2406): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1299238, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2406): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1,
,V/AlarmManager( 2406): waitForAlarm result :8,
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2406): !@Sync 20,
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1289224, pollInterval: 10000,
D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 320, Delta = 10,
,D/AmoledAdjustTimer( 2406): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1279211, pollInterval: 10000,
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2406): stay LED for fully charged
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2406): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 275s ago,
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1269196, pollInterval: 10000,
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2406): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2406): !@Sync 21
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1259182, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1249168, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1239157, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/GAV2    ( 5659): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5659): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2406): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2406): <AppSync3 Whitelist>
,V/AlarmManager( 2406): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 22
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1229147, pollInterval: 10000
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 330s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1219137, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1209127, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 23
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1199117, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1189107, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1179097, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2406): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4070): GC_CONCURRENT freed 2892K, 29% free 9732K/13600K, paused 21ms+2ms, total 91ms
,E/Watchdog( 2406): !@Sync 24
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1169083, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 390s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1159069, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1149057, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2406): GC_CONCURRENT freed 3851K, 71% free 25500K/86980K, paused 22ms+19ms, total 280ms
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 25
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1139047, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1129037, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1119022, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 26
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1109009, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1098995, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :4
,V/AlarmManager( 2406): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5567): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,I/EventLogService( 3279): Aggregate from 1450311451087 (log), 1450311451087 (data)
,I/PowerManagerService( 2406): [PWL] Off : 455s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1088981, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 27
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1078965, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1068951, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1058936, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 28
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1048921, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1038903, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1028889, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 525s ago
,E/Watchdog( 2406): !@Sync 29
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1018875, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2406): mCoverManager.getCoverState() : true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2406): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 1008861, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 998846, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 988832, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 978818, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 968803, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 31
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 958792, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 600s ago
,V/AlarmManager( 2406): waitForAlarm result :8
,D/LightsService( 2406): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 5
D/Sensors ( 2406): LightSensor setDelay = 200000000
D/Sensors ( 2406): LightSensor setSensorDelay = 200000000
D/Sensors ( 2406): Light sensor flush: not enabled 0
D/Sensors ( 2406): LightSensor enable = 1
D/Sensors ( 2406): LightSensor enableSensor = 1
D/SensorManager( 2406): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2406): LightSensor enable = 0
D/Sensors ( 2406): LightSensor enableSensor = 0
,D/SensorManager( 2406): unregisterListener ::   
D/LightsService( 2406): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 948782, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 938772, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 32
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 928762, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 918752, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 908742, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 33
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 898732, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 888722, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 878712, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2406): [PWL] Off : 680s ago
,E/Watchdog( 2406): !@Sync 34
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 868702, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 858692, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2406): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 848678, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 35
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 838666, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 828657, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 818647, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 36
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 808637, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 798627, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :4
,V/AlarmManager( 2406): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5567): [b] __PingReply__
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 788617, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 765s ago
,E/Watchdog( 2406): !@Sync 37
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 778607, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 768597, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 758583, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 38
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 748570, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 738557, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 728543, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 39
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 718530, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 708515, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/dalvikvm( 2406): GC_CONCURRENT freed 3895K, 71% free 25511K/86980K, paused 18ms+18ms, total 228ms
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 698502, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1
,I/PowerManagerService( 2406): [PWL] Off : 855s ago
I/PowerManagerService( 2406): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2406): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2406): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2406, ws=null) (elapsedTime=1058)
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 688487, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 678473, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 668460, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 41
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 658446, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 648432, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 638418, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2406): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2406): <AppSync3 Whitelist>
,V/AlarmManager( 2406): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 42
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 628403, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 618389, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 608374, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 950s ago
,E/Watchdog( 2406): !@Sync 43
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 598360, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 588347, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 578336, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 44
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 568322, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 558308, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 548297, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 45
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 538284, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 528272, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 518262, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 46
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 508248, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 1050s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 498233, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 488220, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 47
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 478204, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 468191, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 458177, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4070): GC_CONCURRENT freed 2050K, 29% free 9730K/13600K, paused 15ms+3ms, total 46ms
,D/dalvikvm( 4070): WAIT_FOR_CONCURRENT_GC blocked 18ms
,E/Watchdog( 2406): !@Sync 48
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 448163, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 438148, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 428135, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 49
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 418121, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 408106, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 398092, pollInterval: 10000
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 1155s ago
I/PowerManagerService( 2406): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2406): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2406): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2406, ws=null) (elapsedTime=1079)
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 50
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 388083, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 378070, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 368056, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 51
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 358041, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 348031, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 338017, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 52
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 328007, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 317997, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 307986, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 53
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 297977, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 287967, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 1265s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 277957, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 54
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 267947, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2406): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 257937, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2406): GC_CONCURRENT freed 3926K, 71% free 25493K/86980K, paused 20ms+17ms, total 237ms
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 247923, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2406): !@Sync 55
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 237908, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 227897, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 217887, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 56
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 207877, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 197867, pollInterval: 10000
,V/AlarmManager( 2406): waitForAlarm result :8
,I/SensorManagerA( 2406): getReportingMode :: sensor.mType = 5
,D/LightsService( 2406): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2406): LightSensor setDelay = 200000000
D/Sensors ( 2406): LightSensor setSensorDelay = 200000000
D/Sensors ( 2406): Light sensor flush: not enabled 0
,D/Sensors ( 2406): LightSensor enable = 1
,D/Sensors ( 2406): LightSensor enableSensor = 1
,D/SensorManager( 2406): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5567): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2406): LightSensor enable = 0
D/Sensors ( 2406): LightSensor enableSensor = 0
,D/SensorManager( 2406): unregisterListener ::   
D/LightsService( 2406): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2406): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 187857, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2406): stay LED for fully charged
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 57
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 177847, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2406): stay LED for fully charged
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2406): [PWL] Off : 1380s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 167837, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 157827, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 58
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 147817, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 137807, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 127796, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 59
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 117787, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 107777, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 97767, pollInterval: 10000
,D/TimaService( 2406): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2406): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2406): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2406): Prepared write state in 44ms
,I/ProcessStatsService( 2406): Pruning old procstats: /data/system/procstats/state-2015-12-16-12-15-00.bin
,I/ProcessStatsService( 2406): Prepared write state in 27ms
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2406): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2406): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2406): !@Sync 60
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 87757, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 77747, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 67737, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2406): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2406): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2406): mCoverManager.getCoverState() : true
,D/BatteryService( 2406): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2406): !@Sync 61
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 57727, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 1500s ago
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 47717, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 37706, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2406): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2406): <AppSync3 Whitelist>
,V/AlarmManager( 2406): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 62
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 27697, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 17686, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler.access$100: Executing killAppInBackground with duration: 7676, pollInterval: 10000
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 63
,D/Finsky  ( 3852): [1] ExperimentsChangeHandler$2.run: Exiting process because of stale process stable experiments
,I/AndroidRuntime( 3852): VM exiting with result code 0, cleanup skipped.
,I/ActivityManager( 2406): Process com.android.vending (pid 3852) (adj 15) has died.
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2406): !@Sync 64
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 65
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2406): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
I/ActivityManager( 2406): Killing 6468:com.sec.knox.bridge/1000 (adj 15): empty for 1843s
I/ActivityManager( 2406): Killing 4890:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1843s
I/ActivityManager( 2406): Killing 6430:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1854s
I/ActivityManager( 2406): Killing 6770:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1854s
I/ActivityManager( 2406): Killing 6756:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1855s
I/ActivityManager( 2406): Killing 6744:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1855s
I/ActivityManager( 2406): Killing 6732:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1855s
I/ActivityManager( 2406): Killing 6719:com.samsung.helphub/1000 (adj 15): empty for 1855s
I/ActivityManager( 2406): Killing 6706:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1855s
I/ActivityManager( 2406): Killing 6693:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1856s
I/ActivityManager( 2406): Killing 6679:com.sec.android.service.cm/u0a82 (adj 15): empty for 1856s
I/ActivityManager( 2406): Killing 6388:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1856s
I/ActivityManager( 2406): Killing 5726:com.android.mms/u0a49 (adj 15): empty for 1856s
I/ActivityManager( 2406): Killing 6654:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1856s
I/ActivityManager( 2406): Killing 6031:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1857s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2406): No listener is left
,D/dalvikvm( 2769): GC_CONCURRENT freed 8974K, 36% free 18082K/28036K, paused 7ms+7ms, total 68ms
,E/Watchdog( 2406): !@Sync 66
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 67
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2406): waitForAlarm result :8
,V/AlarmManager( 2406): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2406): GC_CONCURRENT freed 3945K, 71% free 25451K/86980K, paused 10ms+17ms, total 212ms
,E/Watchdog( 2406): !@Sync 68
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2406): !@Sync 69
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2406): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2406): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
