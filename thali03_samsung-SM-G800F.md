#### Test 54312298af2c956_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7447): 
D/AndroidRuntime( 7447): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7447): CheckJNI is OFF
D/AndroidRuntime( 7447): setted country_code = Poland
D/AndroidRuntime( 7447): setted countryiso_code = PL
D/AndroidRuntime( 7447): setted sales_code = PLS
D/AndroidRuntime( 7447): readGMSProperty: start
D/AndroidRuntime( 7447): readGMSProperty: already setted!!
D/AndroidRuntime( 7447): readGMSProperty: end
D/AndroidRuntime( 7447): addProductProperty: start
D/dalvikvm( 7447): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7447): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7447): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7447): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7447): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7447): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7447): failed to load memtrack module: -2
D/dalvikvm( 7447): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7447): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2407): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2407): mDVFSHelper.acquire()
I/SELinux ( 7477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7477):  
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7447): Shutting down VM
D/dalvikvm( 7447): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 8% free 9508K/10236K, paused 3ms+2ms, total 29ms
I/SELinux ( 7477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7477):  
I/SELinux ( 7477):  
I/SELinux ( 7477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7477): >>>>> Normal User
E/dalvikvm( 7477): >>>>> com.test.thalitest [ userId:0 | appId:10578 ]
E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9508K/10236K, paused 2ms+3ms, total 26ms
D/TimaKeyStoreProvider( 7477): in addTimaSignatureService
D/TimaKeyStoreProvider( 7477): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7477): Added TimaKesytore provider
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9508K/10236K, paused 2ms+2ms, total 24ms
I/SQLiteSecureOpenHelper( 4184): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4184): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7477): GC_CONCURRENT freed 2998K, 28% free 9578K/13256K, paused 3ms+1ms, total 19ms
D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 14ms
V/WebViewChromium( 7477): Binding Chromium to the background looper Looper (main, tid 1) {423310a8}
I/chromium( 7477): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7477): Initializing chromium process, renderers=0
W/chromium( 7477): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7477): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7477): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7477): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7477): Mali API Version : 401
I/Mali    ( 7477): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7477): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7477): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7477): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7477): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0008
D/StatusBarManagerService( 2407): tr p:7477,o:f
D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7477): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7477): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7477): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7477): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7477): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7477): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7477): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7477): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7477): CordovaWebView is running on device made by: samsung
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2407): semi p:7477,o:f
I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7477): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7477): Enabling debug mode 0
W/AwContents( 7477): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2407): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/AwContents( 7477): nativeOnDraw failed; clearing to background color.
W/IInputConnectionWrapper( 7477): showStatusIcon on inactive InputConnection
D/JsMessageQueue( 7477): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7477): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4232d850
D/dalvikvm( 7477): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4232d850
D/jxcore_app_log( 7477): JniHelper::setJavaVM(0x41925220), pthread_self() = 2027575272
D/JX-Cordova( 7477): jxcore cordova android initializing
,D/dalvikvm( 7477): GC_CONCURRENT freed 1313K, 15% free 11339K/13332K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7477): GC_CONCURRENT freed 1922K, 15% free 14926K/17544K, paused 1ms+3ms, total 54ms
D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 39ms
,D/dalvikvm( 7477): GC_FOR_ALLOC freed 5382K, 28% free 16218K/22500K, paused 53ms, total 54ms
,D/dalvikvm( 7477): GC_CONCURRENT freed 6671K, 30% free 17680K/25092K, paused 2ms+9ms, total 61ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 48ms
,I/PowerManagerService( 2407): [PWL] Off : 140s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4386, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/dalvikvm( 7477): GC_FOR_ALLOC freed 1498K, 31% free 17376K/25092K, paused 69ms, total 70ms
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
I/dalvikvm-heap( 7477): Grow heap (frag case) to 21.172MB for 3713210-byte allocation
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7477): GC_FOR_ALLOC freed 2421K, 36% free 18581K/28720K, paused 54ms, total 54ms
,W/jxcore-log( 7477): Initializing JXcore engine
,W/jxcore-log( 7477): JXcore engine is ready
,W/jxcore-log( 7477): Starting JXcore engine
,W/jxcore-log( 7477): Platform android
W/jxcore-log( 7477): 
,W/jxcore-log( 7477): Process ARCH arm
W/jxcore-log( 7477): 
,E/Watchdog( 2407): !@Sync 11
,I/jxcore-log( 7477): JXcore Cordova bridge is ready!
I/jxcore-log( 7477): 
,W/jxcore-log( 7477): JXcore engine is started
,I/chromium( 7477): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/AmoledAdjustTimer( 2407): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4,
,I/jxcore-log( 7477): Toggling radios to true
I/jxcore-log( 7477): 
,D/BluetoothAdapter( 7477): enable(): BT is already enabled..!,
I/WifiManager( 7477): packageName : com.test.thalitest
I/WifiManager( 7477): setWifiEnabled : true
,I/WifiService( 2407): setWifiEnabled: true pid=7477, uid=10578
,W/ActivityManager( 2407): Permission Denial: getCurrentUser() from pid=7477, uid=10578 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2407): Failed getting userId using ActivityManagerNative
W/WifiService( 2407): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7477, uid=10578 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2407): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2407): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2407): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2407): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2407): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2407): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2407): disconnect: pid=7477, uid=10578
I/wpa_supplicant( 3964): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7477): Radios toggled
I/jxcore-log( 7477): 
I/jxcore-log( 7477): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7477): 
I/jxcore-log( 7477): Perf Test app loaded loaded
I/jxcore-log( 7477): 
I/wpa_supplicant( 3964): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/jxcore-log( 7477): check test folder
I/jxcore-log( 7477): 
,D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3964): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3964): First Scan Start
,I/wpa_supplicant( 3964): Scan requested (ret=0) - scan timeout 30 seconds
,W/Settings( 2407): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2407): ignore requestNetworkTransitionWakelock airplane:true
,I/jxcore-log( 7477): found test : ./testFindPeers.js
I/jxcore-log( 7477): 
D/WifiP2pService( 2407): InactiveState{ what=143375 }
D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
D/ConnectivityService( 2407): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2407): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2407): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2407): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2407): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2407): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3964): Skip scan - already scanning
D/WifiP2pService( 2407): InactiveState{ what=143375 }
D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2407): Attempting to switch to mobile
D/ConnectivityService( 2407): Attempting to switch to BLUETOOTH_TETHER
,I/jxcore-log( 7477): found test : ./testSendData.js
I/jxcore-log( 7477): 
,I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7523):  
D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7523):  
I/SELinux ( 7523):  
,I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,W/NetworkManagementService( 2407): route cmd failed: 
W/NetworkManagementService( 2407): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2407): '
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2407): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2407): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2407): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2407): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2407): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2407): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-92ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-101ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/jxcore-log( 7477): found test : ./testSendData2.js
I/jxcore-log( 7477): 
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7523): Added TimaKesytore provider
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,E/WifiStateMachine( 2407): Error! unhandled message{ when=-40ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetUtils( 2407): android_net_utils_resetConnections in env=0x792b1468 clazz=0x61900001 iface=wlan0 mask=0x3
D/ConnectivityService( 2407): resetConnections(wlan0, 3)
,V/NativeCrypto( 2853): Read error: ssl=0x7c19fc70: I/O error during system call, Connection timed out
D/dalvikvm( 7523): GC_CONCURRENT freed 2990K, 28% free 9578K/13256K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 9ms
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7c19fc70: I/O error during system call, Broken pipe
,E/SPPClientService( 5511): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5511): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5511): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
E/SPPClientService( 5511): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5511): [b] ResponseMap empty
,I/chromium( 7477): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/System.out( 7523): Inside WakeupProvider
,I/System.out( 7523): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2407): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): updateIfacesLocked()
,V/NetworkStats( 2407): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7523): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7523): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7523): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): performPollLocked() took 25ms
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/DialogFlow( 7523): initQueue()
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2407): Killing 5715:com.sec.android.diagmonagent/1000 (adj 15): empty #43
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7552): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7552):  
,I/SELinux ( 7552): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7552):  
I/SELinux ( 7552):  
,I/SELinux ( 7552): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7552): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7552): >>>>> Normal User
,E/dalvikvm( 7552): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7552): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7552): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7552): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7552): Added TimaKesytore provider
,I/ApplicationPolicy( 2407): updateDataUsageMap
,D/Tethering( 2407): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2407): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2407): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2407): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,D/dalvikvm( 7552): GC_CONCURRENT freed 2987K, 28% free 9589K/13260K, paused 4ms+4ms, total 46ms
I/DBG_DM  ( 4724): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection...
,I/dalvikvm( 7552): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7552): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7552): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7552): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0037
,I/wpa_supplicant( 3964): nl80211: Received scan results (2 BSSes)
,I/wpa_supplicant( 3964): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3964): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=,
,W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762),
W/dalvikvm( 7552): Link of class 'Ldqp;' failed
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7552): Link of class 'Ldqp;' failed
I/dalvikvm( 7552): Could not find method dqp.q, referenced from method g.a
,W/dalvikvm( 7552): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0000
,E/dalvikvm( 7552): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
,W/dalvikvm( 7552): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0000
,D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true,
W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7552): Link of class 'Ldqp;' failed
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7552): Link of class 'Ldqp;' failed
I/dalvikvm( 7552): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7552): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x1c at 0x0026
,W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762)
,W/dalvikvm( 7552): Link of class 'Ldqp;' failed
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
,W/dalvikvm( 7552): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7552): Link of class 'Ldqp;' failed
I/dalvikvm( 7552): Could not find method dqp.d, referenced from method g.a
,W/dalvikvm( 7552): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0003
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,W/dalvikvm( 7552): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7552): Link of class 'Lax;' failed
E/dalvikvm( 7552): Could not find class 'ax', referenced from method g.a
,W/dalvikvm( 7552): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0006
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3964): Associated with C0.AA.48
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2407): interfaceStatusChanged wlan0, true
W/dalvikvm( 7552): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7552): Link of class 'Laz;' failed
E/dalvikvm( 7552): Could not find class 'az', referenced from method g.a
I/wpa_supplicant( 3964): freq(2412) increment count 2
I/wpa_supplicant( 3964): meet head of list.
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
D/Tethering( 2407): interfaceStatusChanged wlan0, true
,W/dalvikvm( 7552): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x002c
,I/dalvikvm( 7552): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0008
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/dalvikvm( 7552): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a,
W/dalvikvm( 7552): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7552): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0006
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/dalvikvm( 7552): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
I/wpa_supplicant( 3964): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3964): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
W/dalvikvm( 7552): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x000a
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,I/dalvikvm( 7552): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
D/Tethering( 2407): interfaceLinkStateChanged wlan0, true
D/Tethering( 2407): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7552): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7552): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
,D/dalvikvm( 7552): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7552): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7552): VFY: replacing opcode 0x72 at 0x0000
,D/WifiNative( 2407): callSECApiVoid - ID [50]
,W/dalvikvm( 7552): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7552): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7552): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x23 at 0x0005
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/dalvikvm( 7552): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7552): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7552): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
W/dalvikvm( 7552): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7552): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7552): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x1c at 0x0002
E/dalvikvm( 7552): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7552): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
,D/dalvikvm( 7552): VFY: replacing opcode 0x1f at 0x000c
,D/dalvikvm( 7552): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7552): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7552): VFY: replacing opcode 0x62 at 0x0006
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7552): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7552): Link of class 'Lax;' failed
D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7552): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7552): Link of class 'Laz;' failed
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,D/WifiP2pService( 2407): InactiveState{ what=143375 }
,D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7552): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42320c68
,D/dalvikvm( 7552): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42320c68
,I/dalvikvm( 7552): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
,W/dalvikvm( 7552): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0076
,I/Babel_SMS( 7552): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7552): MmsConfig.loadMmsSettings
I/Babel_SMS( 7552): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7552): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7552): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7552): MmsConfig.loadFromResources
,E/Babel_SMS( 7552): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7552): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
W/dalvikvm( 7552): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7552): Link of class 'Lfzc;' failed
E/dalvikvm( 7552): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7552): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0033
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7552): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7552): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7552): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7552): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7552): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7552): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7552): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7552): Link of class 'Lfzc;' failed
,D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2407): Permission Denial : SEC Private Sensor 
,E/SensorService( 2407): Permission Denial : SEC Private Sensor 
V/AlarmManager( 2407): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:3
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
D/ExynosCameraInterface( 1925): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
D/dalvikvm( 7552): GC_CONCURRENT freed 1767K, 19% free 10893K/13340K, paused 5ms+4ms, total 76ms
D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 38ms
D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 40ms
I/dhcpcd  ( 7573): if(wlan0) info get Success. (MAC : C0.AA.48)
I/dhcpcd  ( 7573): bssid match
D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 49ms
W/Settings( 7552): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7552): startup - clean
I/Babel   ( 7552): deleted: false for 0
I/dalvikvm( 7552): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x000d
V/AlarmManager( 2407): waitForAlarm result :4
V/AlarmManager( 2407): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
I/dalvikvm( 7552): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7552): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7552): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7552): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
D/dalvikvm( 7552): VFY: replacing opcode 0x22 at 0x0071
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7552): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7552): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
D/dalvikvm( 7552): VFY: replacing opcode 0x1f at 0x0021
W/dalvikvm( 7552): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/dalvikvm( 7552): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): noConnectivity : true
I/dalvikvm( 7552): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7552): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
D/dalvikvm( 7552): VFY: replacing opcode 0x6e at 0x0074
I/ActivityManager( 2407): Killing 6295:com.sec.phone/1001 (adj 15): empty #43
I/vclib   ( 7552): onServiceConnected
W/Babel   ( 7552): Attempted to change video mute state without an active call.
I/SELinux ( 7584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7584):  
D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection...
I/SELinux ( 7584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7584):  
I/SELinux ( 7584):  
I/SELinux ( 7584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7584): >>>>> Normal User
E/dalvikvm( 7584): >>>>> com.sec.android.diagmonagent [ userId:0 | appId:1000 ]
E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7584): in addTimaSignatureService
D/TimaKeyStoreProvider( 7584): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7584): Added TimaKesytore provider
D/dalvikvm( 7584): GC_CONCURRENT freed 2997K, 28% free 9580K/13260K, paused 3ms+2ms, total 37ms
D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 33ms
D/dalvikvm( 7552): GC_CONCURRENT freed 998K, 13% free 11909K/13600K, paused 3ms+4ms, total 47ms
D/dalvikvm( 7552): WAIT_FOR_CONCURRENT_GC blocked 36ms
I/DBG_DIAGMONDM( 7584): [1.140541.0531][Line:472][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/DBG_DIAGMONDM( 7584): [1.140541.0531][Line:48][onCreate] myUserId : 0
D/dalvikvm( 7552): GC_FOR_ALLOC freed 488K, 14% free 12402K/14368K, paused 36ms, total 36ms
I/DBG_DIAGMONDM( 7584): [1.140541.0531][Line:376][xdbDMffs_Init] 
D/dalvikvm( 7552): GC_FOR_ALLOC freed 1759K, 20% free 12773K/15952K, paused 33ms, total 33ms
I/DBG_DIAGMONDM( 7584): [1.140541.0531][Line:70][onCreate] nStatus : 0
I/SELinux ( 7598): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7598):  
I/SELinux ( 7598): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7598):  
I/SELinux ( 7598):  
I/SELinux ( 7598): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7598): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7598): >>>>> Normal User
E/dalvikvm( 7598): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
E/SELinux ( 7598): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7598): in addTimaSignatureService
D/TimaKeyStoreProvider( 7598): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7598): Added TimaKesytore provider
,D/dalvikvm( 7598): GC_CONCURRENT freed 3002K, 28% free 9571K/13260K, paused 4ms+1ms, total 42ms
,D/dalvikvm( 7598): WAIT_FOR_CONCURRENT_GC blocked 36ms
,I/ActivityManager( 2407): Killing 6313:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/ActivityManager( 2407): Killing 5954:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7610): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7610):  
,I/SELinux ( 7610): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7610):  
I/SELinux ( 7610):  
,I/SELinux ( 7610): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7610): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7610): >>>>> Normal User
,E/dalvikvm( 7610): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7610): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7610): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7610): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7610): Added TimaKesytore provider
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 2407): GC_CONCURRENT freed 4450K, 57% free 25377K/57740K, paused 14ms+22ms, total 274ms
,D/dalvikvm( 7610): GC_CONCURRENT freed 2999K, 28% free 9571K/13256K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7610): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/KLMS-2.3.201 : ( 7610): KLMSValidator() : checkQATesting()
,D/PackageManager( 2407): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/KLMS-2.3.201 : ( 7610): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450836721535
,I/KLMS-2.3.201 : ( 7610): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2407): Killing 6263:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7643): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7643):  
,I/SELinux ( 7643): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7643):  
I/SELinux ( 7643):  
,I/SELinux ( 7643): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7643): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7643): >>>>> Normal User
,E/dalvikvm( 7643): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7643): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7643): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7643): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7643): Added TimaKesytore provider
,D/dalvikvm( 7643): GC_CONCURRENT freed 3009K, 28% free 9564K/13260K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7643): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7643): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7643): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
D/WifiP2pService( 2407): InactiveState{ what=143375 }
D/WifiP2pService( 2407): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2407): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SA      ( 5776): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5776): [BDLM] already registered in spp
,I/SA      ( 5776): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5776): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5776): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5776): [OR] == isSIMCardReady false ==
,I/SA      ( 5776): [SCU] == networkStateCheck == false
,I/SA      ( 5776): [OR] onReceive END
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2407): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2407): CaptivePortalCheckState enter
I/ActivityManager( 2407): Killing 6135:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2407): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2407): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2407): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/WifiTrafficPoller( 2407): evaluateTrafficStatsPolling
D/ConnectivityService( 2407): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2407): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2407): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
,I/SCloudBackupReceiver( 5811): Other Intent
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2407): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/SELinux ( 7657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7657):  
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
I/SELinux ( 7657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7657):  
I/SELinux ( 7657):  
,I/SELinux ( 7657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7657): >>>>> Normal User
,E/dalvikvm( 7657): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7657): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7657): in addTimaSignatureService
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): updateIfacesLocked()
,V/NetworkStats( 2407): performPollLocked(flags=0x1)
D/TimaKeyStoreProvider( 7657): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7657): Added TimaKesytore provider
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,V/NetworkStats( 2407): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
V/NetworkStats( 2407): performPollLocked() took 24ms
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,D/dalvikvm( 7657): GC_CONCURRENT freed 2996K, 28% free 9579K/13260K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 7657): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7657): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7657): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7657): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7657): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5308): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7657): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2407): Killing 6172:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/Headlines( 5844): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5844): getCountryCode(): countryCode = PL
,D/Headlines( 5844): Breath.onCreate
,D/Headlines( 5844): Breath timer started. interval : 30000
,I/SELinux ( 7683): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7683):  
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5844): queryCategory.  mRequest is not initialized.
,V/AlarmManager( 2407): waitForAlarm result :8
D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5844): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5844): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7683): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7683):  
I/SELinux ( 7683):  
,I/SELinux ( 7683): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7683): >>>>> Normal User
,E/dalvikvm( 7683): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7683): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7683): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7683): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7683): Added TimaKesytore provider
,D/dalvikvm( 7683): GC_CONCURRENT freed 2993K, 28% free 9577K/13256K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7683): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/Tethering( 2407): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2407): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2407): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4724): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection...
,V/WebViewChromium( 7683): Binding Chromium to the background looper Looper (main, tid 1) {4232e318}
,I/chromium( 7683): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7683): Initializing chromium process, renderers=0
,W/chromium( 7683): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7683): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7683): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7683): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7683): Mali API Version : 401
,I/Mali    ( 7683): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7683): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7683): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7683): Starting up...
,I/iu.Environment( 5908): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42337b30
,I/SELinux ( 7729): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7729):  
,I/jxcore-log( 7477): Connected to the server!
I/jxcore-log( 7477): 
,I/chromium( 7477): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
I/SELinux ( 7729): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7729):  
I/SELinux ( 7729):  
,I/SELinux ( 7729): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7729): >>>>> Normal User
,E/dalvikvm( 7729): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7729): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7729): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7729): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7729): Added TimaKesytore provider
,D/dalvikvm( 7729): GC_CONCURRENT freed 2990K, 28% free 9587K/13260K, paused 5ms+1ms, total 31ms
,D/dalvikvm( 7729): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/dalvikvm( 7477): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7477): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7477): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7477): Shutting down VM
,W/dalvikvm( 7477): threadid=1: thread exiting with uncaught exception (group=0x41938c08)
E/AndroidRuntime( 7477): FATAL EXCEPTION: main
E/AndroidRuntime( 7477): Process: com.test.thalitest, PID: 7477
E/AndroidRuntime( 7477): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7477): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7477): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7477): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7477): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7477): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7477): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7477): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7477): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7477): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7477): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7477): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7477): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7477): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7477): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7477): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7477): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7477): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7477): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2407):   Force finishing activity com.test.thalitest/.MainActivity
D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2407): Killing 6224:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/CrashAnrDetector( 2407): processName: com.test.thalitest
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/CrashAnrDetector( 2407): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 7477): Sending signal. PID: 7477 SIG: 9
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2407): mDVFSHelper.acquire()
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,I/DBG_DM  ( 4724): [3.19.140541][Line:408][onResume] 
,I/ActivityManager( 2407): Process com.test.thalitest (pid 7477) (adj 9) has died.
,I/SurfaceFlinger( 1921): id=21 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/10)
,I/WindowState( 2407): WIN DEATH: Window{4319c930 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/DBG_DM  ( 4724): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
I/SurfaceFlinger( 1921): id=21 Removed NainActivit (-2/10)
,I/DBG_DM  ( 4724): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4724): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4724): [3.19.140541][Line:418][onResume] Postpone Count : 27
,I/DBG_DM  ( 4724): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/SELinux ( 7748): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7748):  
,I/DBG_DM  ( 4724): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
W/ActivityManager( 2407): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
I/SELinux ( 7748): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7748):  
I/SELinux ( 7748):  
,I/SELinux ( 7748): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7748): >>>>> Normal User
,E/dalvikvm( 7748): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/DBG_DM  ( 4724): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,E/SELinux ( 7748): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2407): sendNotification(2) - 4
,D/TimaKeyStoreProvider( 7748): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7748): Cannot add TimaSignature Service, License check Failed
,I/DBG_DM  ( 4724): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 27
,D/ActivityThread( 7748): Added TimaKesytore provider
,I/SELinux ( 7761): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7761):  
,I/DBG_DM  ( 4724): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/libgps  ( 2407): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
,I/ActivityManager( 2407): Killing 6452:com.google.android.partnersetup/u0a14 (adj 15): empty #43
E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection...
I/DBG_DM  ( 4724): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4724): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4724): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4724): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4724): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2583): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4724): setTransGradationMode to true
D/StatusBarManagerService( 2407): semi p:4724,o:t
,I/SELinux ( 7761): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7761):  
I/SELinux ( 7761):  
,I/SELinux ( 7761): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7761): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7761): >>>>> Normal User
,E/dalvikvm( 7761): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7761): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 8% free 9508K/10236K, paused 2ms+5ms, total 36ms,
,I/DBG_DM  ( 4724): [3.19.140541][Line:400][onPause] ,
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),2 flag=404, YUIInstallC,
,D/TimaKeyStoreProvider( 7761): in addTimaSignatureService,
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2407): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2407): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
D/PointerIcon( 2407): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2407): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2407): setHoveringSpenCustomIcon IconType is same.1,
D/TimaKeyStoreProvider( 7761): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9508K/10236K, paused 2ms+3ms, total 27ms,
,D/ActivityThread( 7761): Added TimaKesytore provider,
,W/InputMethodManagerService( 2407): Got RemoteException sending setActive(false) notification to pid 7477 uid 10578,
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 8% free 9508K/10236K, paused 3ms+3ms, total 25ms,
,D/dalvikvm( 7748): GC_CONCURRENT freed 3001K, 28% free 9571K/13256K, paused 3ms+1ms, total 23ms,
,D/dalvikvm( 7748): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/BadgeProvider( 7748): onCreate
,D/BadgeProvider( 7748): DatabaseHelper
,D/dalvikvm( 7761): GC_CONCURRENT freed 3005K, 28% free 9571K/13260K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7761): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2407): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2407): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/BadgeProvider( 7748): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7748): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7748): sendNotify, [notify] : null
D/BadgeProvider( 7748): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7748): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7748): update, [UpdateCount] : 1
,D/Launcher.Model( 2776): reloadBadges entered.
,D/WaitQueueForNetworkActivate( 6796): notifyNetworkActivated
,W/ContextImpl( 6796): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2407): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7552): Thread-656(HTTPLog):isShipBuild true
,I/System.out( 7552): Thread-656(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 6796): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6796): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
,W/dalvikvm( 6796): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6796): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6796): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6796): exit::IDLE
,D/InitializeManagerStateMachine( 6796): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6796): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6796): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6796): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6796): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6796): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6796): entry::SUCCESS
,D/hcjo    ( 6796): AutoUpdateManager:INITCHECK:onInitializeSuccess
,E/SPPClientService( 5511): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5511): [SystemStateMoniter] Current Time : 356800
D/hcjo    ( 6796): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6796): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5511): [SystemStateMoniter] No Connect : true
,D/InitializeManagerStateMachine( 6796): exit::SUCCESS
,D/InitializeManagerStateMachine( 6796): entry::IDLE
,E/SPPClientService( 5511): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,I/SELinux ( 7781): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7781):  
,E/SPPClientService( 5511): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5511): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5511): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5511): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SELinux ( 7781): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7781):  
I/SELinux ( 7781):  
,I/SELinux ( 7781): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7781): >>>>> Normal User
,E/dalvikvm( 7781): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 7781): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 7781): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7781): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7781): Added TimaKesytore provider
,E/SPPClientService( 5511): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5511): [a] [ConnectionManager] Connection is already disconnected.
,I/Babel   ( 7552): connection state changed from UNKNOWN to CONNECTED
,E/SPPClientService( 5511): [g] getNetMCC return empty string
I/ActivityManager( 2407): Killing 6577:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/dalvikvm( 7781): GC_CONCURRENT freed 3007K, 28% free 9571K/13260K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7781): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2407): Killing 6590:com.android.musicfx/u0a24 (adj 15): empty #43
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5844): Breath 1980 latestRequest time : 1450836722370 current time : 1450836724350
,I/SurfaceFlinger( 1921): id=23 createSurf (1x1),1 flag=4, Uoast
I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/PowerManagerService( 2407): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2407
,I/KLMS-2.3.201 : ( 7610): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7610): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450836724533
,I/KLMS-2.3.201 : ( 7610): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7643): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3240): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3240): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3240): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3240): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7643): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3369): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
D/SSRMv2:SIOP( 2407): SIOP:: AP = 330, Delta = 10
,I/SELinux ( 7801): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7801):  
,D/libgps  ( 2407): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2407): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2407): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SELinux ( 7801): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7801):  
I/SELinux ( 7801):  
I/SELinux ( 7801): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SA      ( 5776): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5776): [BDLM] already registered in spp
E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7801): >>>>> Normal User
,E/dalvikvm( 7801): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/SA      ( 5776): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5776): [OR] == ACTION_CONNECTIVITY_CHANGE ==
E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5776): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5776): [OR] == isSIMCardReady false ==
,I/SA      ( 5776): [SCU] == networkStateCheck == true
I/SA      ( 5776): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5776): isChinaCountryCode : false
,I/SA      ( 5776): [OR] == networkStateCheck true ==
,I/System.out( 7598): Thread-651(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 5776): [OR] GetMyCountryZoneTask
,I/SA      ( 5776): [OR] onReceive END
,I/SA      ( 5776): [SRS] prepareGetMyCountryZone
,D/TimaKeyStoreProvider( 7801): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7801): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7801): Added TimaKesytore provider
,I/SA      ( 5776): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5776): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/System.out( 7598): Thread-651(ApacheHTTPLog):isShipBuild true
,I/System.out( 7598): Thread-651(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 5776): [TPMU] GetMccFromDB : null
I/SA      ( 5776): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5776): [TPM] isNoProxy(default) : true
,I/SA      ( 5776): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 5811): Other Intent
D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4353, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/com.samsung.app( 7657): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7657): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/Headlines( 5844): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadlinesChannelUtil( 5844): getCountryCode(): countryCode = PL
D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5844): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5844): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5844): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5844): requestUpdateNewsWelcomeCard !!! no welcome card
D/CustomFrequencyManagerService( 2407): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2407  tag : ACTIVITY_RESUME_BOOSTER@8
,I/iu.Environment( 5908): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
W/WifiP2pStateTracker( 2407): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
D/dalvikvm( 7801): GC_CONCURRENT freed 3000K, 28% free 9572K/13252K, paused 4ms+4ms, total 33ms
,D/dalvikvm( 7801): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService( 2407): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2407):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2407): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2407): updateSourceRoutes : no source routing conditions
I/QuickConnect[1.1][2] ( 5110): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5110): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42337b30
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,D/RCPManagerService( 2407): exchangeData() failure , invalid userId
,V/KVNProvider( 7801): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7801): getFindoCursor query string : 
,I/System.out( 7598): AsyncTask #1 calls detatch()
,W/System.err( 7598): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7598): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,D/hcjo    ( 6796): AutoUpdateManager:IDLE:execute
W/System.err( 7598): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7598): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7598): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7598): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7598): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7598): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
D/InitializeManagerStateMachine( 6796): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6796): exit::IDLE
,D/InitializeManagerStateMachine( 6796): entry::NETWORK_CHECK
,W/System.err( 7598): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7598): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7598): Caused by: java.lang.NullPointerException
W/System.err( 7598): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
D/InitializeManagerStateMachine( 6796): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6796): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6796): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6796): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6796): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6796): entry::SUCCESS
,D/hcjo    ( 6796): AutoUpdateManager:INITCHECK:onInitializeSuccess
,W/System.err( 7598): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7598): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7598): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7598): 	... 8 more
D/hcjo    ( 6796): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6796): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6796): exit::SUCCESS
,D/InitializeManagerStateMachine( 6796): entry::IDLE
,V/KVNProvider( 7801): getTagSearchCursor() tagSearchCursor count : 0
,E/SPPClientService( 5511): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5511): [SystemStateMoniter] Current Time : 357719
,E/SPPClientService( 5511): [SystemStateMoniter] No Connect : false
,E/WifiStateMachine( 2407): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 5511): GC_CONCURRENT freed 1926K, 22% free 10465K/13248K, paused 9ms+7ms, total 58ms
,I/SA      ( 5776): [RC New] [v2liruge] api execute + 726
,I/SA      ( 5776): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5776): AsyncTask #2 calls detatch()
,I/SA      ( 5776): [TPMU] getNetworkMcc : 
,I/SA      ( 5776): [SCU] saveMccToPreferece Start
,I/SA      ( 5776): [SCU] RegionMCC : 260
,I/SA      ( 5776): [SSP] query invoked
,I/SA      ( 5776): [TPMU] GetMccFromDB : null
,I/SA      ( 5776): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5776): [SCU] saveMccToPreferece End
I/SA      ( 5776): [RC New] executeRequest [v2liruge] end. 771
I/SA      ( 5776): [RC New] Execute end
,I/SA      ( 5776): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5776): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5511): [b] __InitReply__
,D/AmoledAdjustTimer( 2407): prevTemp = 294, currTemp = 296, prevStep = 4, currStep = 4
,I/ActivityManager( 2407): Killing 6618:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43,
,I/SurfaceFlinger( 1921): id=23 Removed Uoast (10/11),
,D/PowerManagerService( 2407): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2407) eventTime = 360610,
,D/PowerManagerService( 2407): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2407 (0x0)
,D/PowerManagerService( 2407): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2407, ws=WorkSource{1000}) (elapsedTime=3514),
,I/GAV2    ( 7683): Thread[GAThread,5,main]: No campaign data found.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6604): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6604): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6604): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6604): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6604): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6604): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6604): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/CaptivePortalTracker( 2407): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2407): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2407): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2407): Don't send network conditions - lacking user consent.,
,D/CaptivePortalTracker( 2407): isCaptivePortal: ret=false rspCode=204,
D/CaptivePortalTracker( 2407): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
,D/CaptivePortalTracker( 2407): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2407): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6796): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 6796): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 6796): entry::CHECK_TIMEOUT_FOR_UPDATE,
,D/hcjo    ( 6796): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 6796): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6796): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6796): entry::IDLE,
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/PreloadUpdateManagerStateMachine( 6796): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6796): exit::IDLE
D/PreloadUpdateManagerStateMachine( 6796): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6796): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6796): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 6796): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6796): entry::IDLE
,D/AmoledAdjustTimer( 2407): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4,
,I/ActivityManager( 2407): Waited long enough for: ServiceRecord{4493b9d0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2407): Waited long enough for: ServiceRecord{4302eaa8 u0 com.sec.spp.push/.PushClientService},
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = -10,
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 12,
,D/AmoledAdjustTimer( 2407): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4,
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2407): waitForAlarm result :8,
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5844): Breath 27620 latestRequest time : 1450836724782 current time : 1450836752402,
,I/PowerManagerService( 2407): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2407): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2407): !@Sync 13
,D/AmoledAdjustTimer( 2407): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2407): waitForAlarm result :8
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5844): Breath 57610 latestRequest time : 1450836724782 current time : 1450836782392
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 225s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 14
,D/AmoledAdjustTimer( 2407): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2407): waitForAlarm result :8
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5844): Breath 87610 latestRequest time : 1450836724782 current time : 1450836812392
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2407): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = -10
,E/Watchdog( 2407): !@Sync 15
,D/AmoledAdjustTimer( 2407): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2407): waitForAlarm result :8
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5844): Breath 117612 latestRequest time : 1450836724782 current time : 1450836842394
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 275s ago
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 16
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2407): waitForAlarm result :8
,D/Headlines( 5844): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5844): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5844): Breath 147617 latestRequest time : 1450836724782 current time : 1450836872400
,D/Headlines( 5844): stop 
,D/Headlines( 5844): Breath.onDestroy : 
I/ActivityManager( 2407): Killing 5980:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 17
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2407): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2407): GC_CONCURRENT freed 4216K, 57% free 25037K/57740K, paused 22ms+19ms, total 251ms
,D/AmoledAdjustTimer( 2407): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 18
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 19
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2407): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2407): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2407): !@Sync 21
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2882K, 27% free 9731K/13296K, paused 26ms+3ms, total 96ms
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/GAV2    ( 5600): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5600): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2407): !@Sync 22
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2407): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 23
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2407): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2407): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,V/AlarmManager( 2407): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): stay LED for fully charged
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2407): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 525s ago
,E/Watchdog( 2407): !@Sync 24
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 25
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 26
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,D/LightsService( 2407): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2407): getReportingMode :: sensor.mType = 5
D/Sensors ( 2407): LightSensor setDelay = 200000000
D/Sensors ( 2407): LightSensor setSensorDelay = 200000000
D/Sensors ( 2407): Light sensor flush: not enabled 0
D/Sensors ( 2407): LightSensor enable = 1
D/Sensors ( 2407): LightSensor enableSensor = 1
D/SensorManager( 2407): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5511): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2407): LightSensor enable = 0
,D/Sensors ( 2407): LightSensor enableSensor = 0
,D/SensorManager( 2407): unregisterListener ::   
D/LightsService( 2407): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2407): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 27
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2407): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 28
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 680s ago
,E/Watchdog( 2407): !@Sync 29
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2407): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2407): stay LED for fully charged
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 31
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 2407): GC_CONCURRENT freed 3897K, 57% free 24933K/57732K, paused 18ms+16ms, total 237ms
,D/AmoledAdjustTimer( 2407): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 765s ago
,E/Watchdog( 2407): !@Sync 32
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 33
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 34
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 855s ago
,E/Watchdog( 2407): !@Sync 35
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 36
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2407): waitForAlarm result :4
,V/AlarmManager( 2407): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5511): [b] __PingReply__
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 37
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 950s ago
,E/Watchdog( 2407): !@Sync 38
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 39
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2407): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 41
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2407): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 42
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 43
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2407): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2407): <AppSync3 Whitelist>
,V/AlarmManager( 2407): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 44
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 1155s ago
,E/Watchdog( 2407): !@Sync 45
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2050K, 27% free 9729K/13296K, paused 11ms+2ms, total 49ms
D/dalvikvm( 4091): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 46
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/dalvikvm( 2407): GC_CONCURRENT freed 3752K, 57% free 24944K/57732K, paused 23ms+17ms, total 237ms
,V/AlarmManager( 2407): waitForAlarm result :8
,I/SensorManagerA( 2407): getReportingMode :: sensor.mType = 5
D/Sensors ( 2407): LightSensor setDelay = 200000000
,D/Sensors ( 2407): LightSensor setSensorDelay = 200000000
,D/LightsService( 2407): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2407): Light sensor flush: not enabled 0
D/Sensors ( 2407): LightSensor enable = 1
D/Sensors ( 2407): LightSensor enableSensor = 1
D/SensorManager( 2407): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2407): LightSensor enable = 0
,D/Sensors ( 2407): LightSensor enableSensor = 0
,D/SensorManager( 2407): unregisterListener ::   
D/LightsService( 2407): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2407): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 47
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 48
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 49
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2407): !@Sync 50
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 51
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2407): stay LED for fully charged
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 52
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 53
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2776): GC_CONCURRENT freed 7395K, 35% free 18959K/28764K, paused 14ms+7ms, total 83ms
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 54
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 55
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 56
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2407): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,E/SPPClientService( 5511): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 57
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :4
,V/AlarmManager( 2407): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 58
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 59
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 60
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2407): GC_CONCURRENT freed 3779K, 57% free 24966K/57732K, paused 19ms+17ms, total 229ms
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11346
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11351
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11356
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11361
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11364
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 11367
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 61
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2407): Prepared write state in 41ms
,I/ProcessStatsService( 2407): Prepared write state in 49ms
,I/ProcessStatsService( 2407): Pruning old procstats: /data/system/procstats/state-2015-12-22-02-25-22.bin
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 62
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 63
,V/AlarmManager( 2407): waitForAlarm result :8
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2407): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2407): <AppSync3 Whitelist>
,V/AlarmManager( 2407): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 64
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2407): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2407): stay LED for fully charged
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2407): !@Sync 65
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
I/ActivityManager( 2407): Killing 6505:com.google.android.apps.uploader/u0a117 (adj 15): empty for 1806s
,I/ActivityManager( 2407): Killing 6489:com.android.chrome/u0a85 (adj 15): empty for 1806s
,I/ActivityManager( 2407): Killing 6974:com.google.android.gms.unstable/u0a12 (adj 15): empty for 1808s
,I/ActivityManager( 2407): Killing 6476:com.sec.android.Kies/1000 (adj 15): empty for 1816s
,I/ActivityManager( 2407): Killing 6439:com.sec.knox.bridge/1000 (adj 15): empty for 1840s
,I/ActivityManager( 2407): Killing 4832:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1840s
,I/ActivityManager( 2407): Killing 6401:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1849s
,I/ActivityManager( 2407): Killing 6764:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1850s
,I/ActivityManager( 2407): Killing 6750:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1851s
,I/ActivityManager( 2407): Killing 6738:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1851s
,I/ActivityManager( 2407): Killing 6726:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1851s
,I/ActivityManager( 2407): Killing 6713:com.samsung.helphub/1000 (adj 15): empty for 1851s
,I/ActivityManager( 2407): Killing 6700:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1851s
,I/ActivityManager( 2407): Killing 6687:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1852s
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2407): Killing 6673:com.sec.android.service.cm/u0a82 (adj 15): empty for 1852s
,I/ActivityManager( 2407): Killing 6351:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1852s
,I/ActivityManager( 2407): Killing 5666:com.android.mms/u0a49 (adj 15): empty for 1852s
,I/ActivityManager( 2407): Killing 6648:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1852s
,D/CountryDetector( 2407): No listener is left
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 279, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 66
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2407): waitForAlarm result :4
,V/NetworkStats( 2407): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,V/AlarmManager( 2407): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2407): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,V/NetworkStats( 2407): performPollLocked() took 57ms
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
D/NtpTrustedTime( 2407): currentTimeMillis() cache hit
,I/SELinux (11779): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11779):  
,I/SELinux (11779): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11779):  
I/SELinux (11779):  
,I/SELinux (11779): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11779): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11779): >>>>> Normal User
,E/dalvikvm(11779): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (11779): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11779): in addTimaSignatureService
,D/TimaKeyStoreProvider(11779): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11779): Added TimaKesytore provider
,D/dalvikvm(11779): GC_CONCURRENT freed 2991K, 28% free 9578K/13256K, paused 3ms+2ms, total 26ms
,D/dalvikvm(11779): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(11779): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11779): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11779): Widget random data : 9
,D/@ WidgetProvider(11779): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11779): Widget random data : 6
,E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(11779): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11779): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11779): VFY: replacing opcode 0x22 at 0x0038
D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11779): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2407): getReportingMode :: sensor.mType = 5
,D/LightsService( 2407): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2407): LightSensor setDelay = 200000000
D/Sensors ( 2407): LightSensor setSensorDelay = 200000000
D/Sensors ( 2407): Light sensor flush: not enabled 0
D/Sensors ( 2407): LightSensor enable = 1
D/Sensors ( 2407): LightSensor enableSensor = 1
D/SensorManager( 2407): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/EventLogService( 3431): Aggregate from 1450836543971 (log), 1450836543971 (data)
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm( 3431): GC_CONCURRENT freed 1736K, 16% free 12702K/15120K, paused 8ms+13ms, total 85ms
,I/System.out(11779): Thread-681(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11779): Thread-681(ApacheHTTPLog):isShipBuild true
,I/System.out(11779): Thread-681(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/LightsService( 2407): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2407): LightSensor enable = 0
D/Sensors ( 2407): LightSensor enableSensor = 0
,D/SensorManager( 2407): unregisterListener ::   
D/LightsService( 2407): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(11779): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11779): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11779): Max ALLOWED memory (MB): 128
V/ImageManager(11779): Max SHOULD USE memory (MB): 128
,V/ImageManager(11779): Max Image Cache memory (MB): 32
,D/skia    (11779): getTotalSize : Do not get file length
,D/@ WidgetProvider(11779): Building widget : 5
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 67
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 68
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 69
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4091): GC_CONCURRENT freed 2047K, 27% free 9729K/13256K, paused 14ms+3ms, total 46ms
,D/dalvikvm( 4091): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2407): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2407): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2407): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2407): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 70
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2407): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2407): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2407): !@Sync 71
,V/AlarmManager( 2407): waitForAlarm result :8
,V/AlarmManager( 2407): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2407): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2407): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 12178
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 12180
,W/ProcessCpuTracker( 2407): Skipping unknown process pid 12181
,D/SSRMv2:SIOP( 2407): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2407): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms),D/AndroidRuntime(12192): 
D/AndroidRuntime(12192): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(12192): CheckJNI is OFF
D/AndroidRuntime(12192): setted country_code = Poland
D/AndroidRuntime(12192): setted countryiso_code = PL
D/AndroidRuntime(12192): setted sales_code = PLS
D/AndroidRuntime(12192): readGMSProperty: start
D/AndroidRuntime(12192): readGMSProperty: already setted!!
D/AndroidRuntime(12192): readGMSProperty: end
D/AndroidRuntime(12192): addProductProperty: start
D/dalvikvm(12192): Trying to load lib libjavacore.so 0x0
D/dalvikvm(12192): Added shared lib libjavacore.so 0x0
D/dalvikvm(12192): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(12192): Added shared lib libnativehelper.so 0x0
D/dalvikvm(12192): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(12192): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(12192): failed to load memtrack module: -2
D/dalvikvm(12192): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(12192): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2407): START PACKAGE DELETE: observer{1122634072}
D/PackageManager( 2407): pkg{<packageName>}
D/PackageManager( 2407): user{0}
D/PackageManager( 2407): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2407): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2407): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2407): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2407): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2407): !@killApplicatoin: 10578, uninstall pkg
I/ActivityManager( 2407): Killing 7643:com.sec.android.soagent/u0a38 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7523:com.vlingo.midas/u0a34 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7610:com.samsung.klmsagent/u0a18 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7598:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7584:com.sec.android.diagmonagent/1000 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 5701:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 6604:com.sec.pcw.device/1000 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 2835:com.android.settings/1000 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7781:com.blurb.checkout/u0a79 (adj 15): empty for 1807s
I/ActivityManager( 2407): Killing 7748:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1808s
D/dalvikvm( 2407): GC_CONCURRENT freed 3844K, 57% free 25012K/57732K, paused 13ms+18ms, total 218ms
D/dalvikvm( 2407): WAIT_FOR_CONCURRENT_GC blocked 167ms
D/dalvikvm( 2407): WAIT_FOR_CONCURRENT_GC blocked 169ms
D/dalvikvm( 2407): WAIT_FOR_CONCURRENT_GC blocked 164ms
W/PackageSettings( 2407): Skipping PackageSetting{42c2ce28 com.example.hello/10551} due to missing metadata
D/PackageManager( 2407): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10578, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/PackageManager( 2407): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10578, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 6424): GC_EXPLICIT freed 575K, 25% free 9987K/13252K, paused 10ms+7ms, total 81ms
W/GeofencerStateMachine( 2737): Ignoring removeGeofence because network location is disabled.
E/SamsungIME( 3035): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5110): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Scheme: "sms"
I/SELinux (12224): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12224):  
D/dalvikvm( 2952): GC_EXPLICIT freed 1472K, 25% free 10041K/13256K, paused 11ms+18ms, total 136ms
I/SELinux (12224): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12224):  
I/SELinux (12224):  
I/SELinux (12224): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12224): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12224): >>>>> Normal User
D/dalvikvm( 3431): GC_EXPLICIT freed 395K, 18% free 12400K/15120K, paused 7ms+42ms, total 208ms
E/dalvikvm(12224): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (12224): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "smsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(12224): in addTimaSignatureService
D/TimaKeyStoreProvider(12224): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12224): Added TimaKesytore provider
D/RegisteredServicesCache( 2759): empty dynamic service
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2407): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mmsto"
D/RCPManagerService( 2407): PackageReceiver onReceive()
I/HarmonyEASService( 2407): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "sms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService( 2407): Package has changed for user 0
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "smsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12224): GC_CONCURRENT freed 3002K, 28% free 9571K/13256K, paused 5ms+5ms, total 30ms
D/dalvikvm(12224): WAIT_FOR_CONCURRENT_GC blocked 25ms
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mmsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(12224): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(12224): ELMEngine.ELMEngine( context ).
D/elm:14132(12224): MDMBridge.setEnterpriseBridge()
D/dalvikvm( 2759): GC_CONCURRENT freed 2339K, 23% free 10262K/13280K, paused 7ms+5ms, total 85ms
D/elm:14132(12224): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(12224): ElmAgentService : onCreate()
D/elm:14132(12224): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(12224): MainReceiver.listeningToPackageRemoved()
D/elm:14132(12224): MDMBridge.getInstance()
D/elm:14132(12224): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(12224): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (12237): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12237):  
D/elm:14132(12224): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/elm:14132(12224): ElmAgentService : onDestroy().
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2407): Killing 6632:com.policydm/1000 (adj 15): empty for 1808s
I/SELinux (12237): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12237):  
I/SELinux (12237):  
I/SELinux (12237): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12237): >>>>> Normal User
E/dalvikvm(12237): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (12237): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 2407): GC_EXPLICIT freed 1638K, 57% free 25077K/57732K, paused 13ms+26ms, total 543ms
D/TimaKeyStoreProvider(12237): in addTimaSignatureService
D/PackageManager( 2407): delete sourFile : 
D/TimaKeyStoreProvider(12237): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12237): Added TimaKesytore provider
D/PackageManager( 2407): delete native library directory: 
D/PackageManager( 2407): return delete result to caller: 1122634072
D/PackageManager( 2407): returnCode: 1
D/AndroidRuntime(12192): Shutting down VM
D/dalvikvm(12192): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 4ms
D/BackupManagerService( 2407): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2407): removePackageParticipantsLocked: uid=10578 #1
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "sms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(12237): GC_CONCURRENT freed 2999K, 28% free 9574K/13256K, paused 3ms+4ms, total 41ms
D/dalvikvm(12237): WAIT_FOR_CONCURRENT_GC blocked 34ms
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "smsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mms"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2407):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2407):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2407):   Scheme: "mmsto"
I/PackageManager( 2407): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (12252): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12252):  
I/ActivityManager( 2407): Killing 6326:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1808s
I/SELinux (12252): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12252):  
I/SELinux (12252):  
I/SELinux (12252): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12252): >>>>> Normal User
E/dalvikvm(12252): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (12252): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12252): in addTimaSignatureService
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider(12252): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12252): Added TimaKesytore provider
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ApplicationsProvider( 2952): Could not fetch usage stats
W/ApplicationsProvider( 2952): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2952): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2952): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2952): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2952): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2952): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2952): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2952): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2952): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(12252): GC_CONCURRENT freed 3009K, 28% free 9566K/13256K, paused 3ms+2ms, total 43ms
D/dalvikvm(12252): WAIT_FOR_CONCURRENT_GC blocked 40ms
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2407): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2407): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2407): clearDefaults: com.test.thalitest
E/SQLiteDatabase(12252): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase(12252): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12252): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase(12252): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase(12252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(12252): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(12252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(12252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12252): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12252): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12252): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12252): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12252): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12252): Shutting down VM
W/dalvikvm(12252): threadid=1: thread exiting with uncaught exception (group=0x41938c08)
W/AtomicFile( 2407): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2407): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
E/AndroidRuntime(12252): FATAL EXCEPTION: main
E/AndroidRuntime(12252): Process: com.sec.android.app.mss, PID: 12252
E/AndroidRuntime(12252): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime(12252): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime(12252): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime(12252): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12252): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12252): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12252): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12252): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12252): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12252): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12252): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12252): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12252): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12252): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12252): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12252): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime(12252): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime(12252): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime(12252): 	... 10 more
I/SELinux (12268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12268):  
I/ActivityManager( 2407): Killing 5776:com.osp.app.signin/u0a44 (adj 15): empty for 1808s
I/Process (12252): Sending signal. PID: 12252 SIG: 9
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop239.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
I/ActivityManager( 2407): Process com.sec.android.app.mss (pid 12252) (adj 9) has died.
I/EsApplication( 5908): Trimming memory (onTrimMemory 40)
V/SamsungIME( 3035): onTrimMeomory Level = 5
D/HeadlinesChannelApplication( 5844): HeadlinesChannelApplication.onTrimMemory(). level : 60
I/SELinux (12268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12268):  
I/SELinux (12268):  
I/SELinux (12268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12268): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12268): >>>>> Normal User
E/dalvikvm(12268): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (12268): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/rsC++   ( 2776): RS Message thread exiting.
E/OpenGLRenderer( 2776): SFEffectCache:clear(), mSize = 0
D/Launcher( 2776): onTrimMemory. Level: 80
W/ManagedEGLContext( 2776): doTerminate failed: EGL count is 2 but managed count is 1
W/GeoLookout( 3089): at (DisasterAlertApplication.java:67) [onTrimMemory()]
D/TimaKeyStoreProvider(12268): in addTimaSignatureService
D/TimaKeyStoreProvider(12268): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12268): Added TimaKesytore provider
D/dalvikvm(12268): GC_CONCURRENT freed 2996K, 28% free 9575K/13256K, paused 2ms+2ms, total 25ms
D/dalvikvm(12268): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/SELinux (12283): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12283):  
I/SELinux (12283): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12283):  
I/SELinux (12283):  
I/SELinux (12283): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12283): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12283): >>>>> Normal User
E/dalvikvm(12283): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (12283): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(12283): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(12283): in addTimaSignatureService
D/TimaKeyStoreProvider(12283): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12283): Added TimaKesytore provider
D/dalvikvm(12283): GC_CONCURRENT freed 2991K, 28% free 9580K/13252K, paused 3ms+2ms, total 26ms
D/dalvikvm(12283): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(12283): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(12283): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12283): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12283): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(12283): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(12283): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(12283): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(12283): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12283): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12283): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12283): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12283): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12283): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12283): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12283): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12283): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12283): Shutting down VM
W/dalvikvm(12283): threadid=1: thread exiting with uncaught exception (group=0x41938c08)
E/AndroidRuntime(12283): FATAL EXCEPTION: main
E/AndroidRuntime(12283): Process: com.sec.pcw.device, PID: 12283
E/AndroidRuntime(12283): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12283): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(12283): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(12283): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(12283): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12283): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12283): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12283): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12283): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12283): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12283): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12283): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12283): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12283): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12283): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12283): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12283): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(12283): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(12283): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(12283): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(12283): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(12283): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(12283): 	... 12 more
E/DropBoxManagerService( 2407): Can't write: system_app_crash
E/DropBoxManagerService( 2407): java.io.FileNotFoundException: /data/system/dropbox/drop240.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2407): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2407): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2407): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2407): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2407): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2407): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2407): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2407): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2407): 	... 5 more
I/SELinux (12296): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12296):  
I/Process (12283): Sending signal. PID: 12283 SIG: 9
I/ActivityManager( 2407): Process com.sec.pcw.device (pid 12283) (adj 0) has died.
I/SELinux (12296): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12296):  
I/SELinux (12296):  
I/SELinux (12296): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12296): >>>>> Normal User
E/dalvikvm(12296): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12296): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12296): in addTimaSignatureService
D/TimaKeyStoreProvider(12296): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12296): Added TimaKesytore provider
D/BatteryService( 2407): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2407): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2407): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2407): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/dalvikvm(12296): GC_CONCURRENT freed 2997K, 28% free 9575K/13252K, paused 3ms+1ms, total 26ms
D/dalvikvm(12296): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/System.err(12296): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12296): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12296): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12296): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12296): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12296): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12296): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12296): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12296): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12296): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12296): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12296): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12296): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12296): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12296): 	at libcore.io.Posix.open(Native Method)
W/System.err(12296): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12296): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12296): 	... 21 more
D/GalaxyFinderApplication(12296): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12296): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12310): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12310):  
I/ActivityManager( 2407): Killing 7801:com.sec.android.app.voicenote/1000 (adj 15): empty for 1809s
I/SELinux (12310): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12310):  
I/SELinux (12310):  
I/SELinux (12310): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12310): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12310): >>>>> Normal User
E/dalvikvm(12310): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12310): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12310): in addTimaSignatureService
D/TimaKeyStoreProvider(12310): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12310): Added TimaKesytore provider
D/dalvikvm(12310): GC_CONCURRENT freed 3011K, 28% free 9563K/13260K, paused 2ms+2ms, total 24ms
D/dalvikvm(12310): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(12310): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12310): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12310): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12310): ContentProvider is not null
W/ResourceType(12310): No package identifier when getting value for resource number 0x00000000
I/System.out(12310): resource Id::2131361807
E/SQLiteDatabase(12310): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12310): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12310): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12310): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12310): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12310): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12310): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12310): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12310): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12310): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12310): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12310): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12310): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12310): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12310): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12310): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12310): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12310): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12310): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase
```
