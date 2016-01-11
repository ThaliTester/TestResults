#### Test 55613145dd493c6_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
I/PowerManagerService( 2421): [PWL] Off : 140s ago,
D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/AndroidRuntime( 7245): 
D/AndroidRuntime( 7245): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7245): CheckJNI is OFF
D/AndroidRuntime( 7245): setted country_code = Poland
D/AndroidRuntime( 7245): setted countryiso_code = PL
D/AndroidRuntime( 7245): setted sales_code = PLS
D/AndroidRuntime( 7245): readGMSProperty: start
D/AndroidRuntime( 7245): readGMSProperty: already setted!!
D/AndroidRuntime( 7245): readGMSProperty: end
D/AndroidRuntime( 7245): addProductProperty: start
D/dalvikvm( 7245): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7245): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7245): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7245): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7245): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7245): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7245): failed to load memtrack module: -2
D/dalvikvm( 7245): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7245): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2421): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.acquire()
I/SELinux ( 7256): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7256):  
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7245): Shutting down VM
D/dalvikvm( 7245): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
I/SELinux ( 7256): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7256):  
I/SELinux ( 7256):  
I/SELinux ( 7256): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7256): >>>>> Normal User
E/dalvikvm( 7256): >>>>> com.test.thalitest [ userId:0 | appId:10608 ]
E/SELinux ( 7256): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7256): in addTimaSignatureService
D/TimaKeyStoreProvider( 7256): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7256): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4179): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4179): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7256): GC_CONCURRENT freed 2996K, 30% free 9573K/13592K, paused 2ms+1ms, total 18ms
D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7256): Binding Chromium to the background looper Looper (main, tid 1) {422533d8}
I/chromium( 7256): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7256): Initializing chromium process, renderers=0
W/chromium( 7256): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7256): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7256): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7256): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7256): Mali API Version : 401
,I/Mali    ( 7256): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7256): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7256): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7256): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7256): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2421): tr p:7256,o:f
,W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7256): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7256): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7256): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7256): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7256): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7256): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7256): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7256): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7256): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2421): semi p:7256,o:f
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7256): EGLImpl-HWUI Protected EGL context created
E/Watchdog( 2421): !@Sync 8
D/OpenGLRenderer( 7256): Enabling debug mode 0
W/AwContents( 7256): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.release()
,W/AwContents( 7256): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7256): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7256): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7256): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4224fb80
,D/dalvikvm( 7256): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4224fb80
D/jxcore_app_log( 7256): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027622984
,D/JX-Cordova( 7256): jxcore cordova android initializing
,D/dalvikvm( 7256): GC_CONCURRENT freed 1298K, 17% free 11348K/13664K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7256): GC_CONCURRENT freed 1879K, 17% free 15007K/17924K, paused 2ms+2ms, total 45ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 5393K, 30% free 16256K/22904K, paused 51ms, total 51ms
,D/dalvikvm( 7256): GC_CONCURRENT freed 6684K, 31% free 17714K/25468K, paused 2ms+11ms, total 65ms
,D/dalvikvm( 7256): WAIT_FOR_CONCURRENT_GC blocked 56ms
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 1323K, 32% free 17527K/25468K, paused 56ms, total 56ms
,I/dalvikvm-heap( 7256): Grow heap (frag case) to 21.650MB for 3713210-byte allocation
,D/dalvikvm( 7256): GC_FOR_ALLOC freed 2494K, 36% free 18659K/29096K, paused 50ms, total 50ms
,W/jxcore-log( 7256): Initializing JXcore engine
,W/jxcore-log( 7256): JXcore engine is ready
,W/jxcore-log( 7256): Starting JXcore engine
,W/jxcore-log( 7256): Platform android
W/jxcore-log( 7256): 
,W/jxcore-log( 7256): Process ARCH arm
W/jxcore-log( 7256): 
,I/jxcore-log( 7256): JXcore Cordova bridge is ready!
I/jxcore-log( 7256): 
,W/jxcore-log( 7256): JXcore engine is started
,I/chromium( 7256): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7256): Toggling radios to true
I/jxcore-log( 7256): 
,D/BluetoothAdapter( 7256): enable(): BT is already enabled..!
,I/WifiManager( 7256): packageName : com.test.thalitest
,I/WifiManager( 7256): setWifiEnabled : true
,I/WifiService( 2421): setWifiEnabled: true pid=7256, uid=10608
,W/ActivityManager( 2421): Permission Denial: getCurrentUser() from pid=7256, uid=10608 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): Failed getting userId using ActivityManagerNative
W/WifiService( 2421): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7256, uid=10608 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2421): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2421): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2421): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2421): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2421): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2421): disconnect: pid=7256, uid=10608
I/jxcore-log( 7256): Radios toggled
I/jxcore-log( 7256): 
I/wpa_supplicant( 3982): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7256): Received device characteristics:
I/jxcore-log( 7256): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7256): Bluetooth name: S5mini-1
I/jxcore-log( 7256): Device name: samsung-SM-G800F
I/jxcore-log( 7256): 
,I/jxcore-log( 7256): Perf Test app loaded loaded
I/jxcore-log( 7256): 
,I/wpa_supplicant( 3982): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/jxcore-log( 7256): check test folder
I/jxcore-log( 7256): 
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030,
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true,
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true,
I/wpa_supplicant( 3982): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3982): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3982): First Scan Start,
I/wpa_supplicant( 3982): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2421): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,I/WifiStateMachine( 2421): ignore requestNetworkTransitionWakelock airplane:true
,I/jxcore-log( 7256): found test : ./testFindPeers.js
I/jxcore-log( 7256): 
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3982): wlan0: Setting scan request: 0 sec 0 usec,
,I/wpa_supplicant( 3982): Skip scan - already scanning
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2421): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2421): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2421): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2421): net.tcp.delack.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2421): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2421): Attempting to switch to mobile
,D/ConnectivityService( 2421): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7304): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7304):  
I/jxcore-log( 7256): found test : ./testSendData.js
I/jxcore-log( 7256): 
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2421): route cmd failed: 
W/NetworkManagementService( 2421): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2421): '
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2421): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2421): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2421): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2421): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2421): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2421): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1,
,I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
I/SELinux ( 7304): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7304):  
I/SELinux ( 7304):  
,I/SELinux ( 7304): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7304): >>>>> Normal User
,E/dalvikvm( 7304): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ],
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/SELinux ( 7304): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2421): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2421): Error! unhandled message{ when=-85ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,E/WifiStateMachine( 2421): Error! unhandled message{ when=-13ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7304): in addTimaSignatureService,
,D/NetUtils( 2421): android_net_utils_resetConnections in env=0x77d50800 clazz=0x62300001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2421): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 7304): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7304): Added TimaKesytore provider
,E/SPPClientService( 5562): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5562): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5562): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5562): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5562): [b] ResponseMap empty
,V/NativeCrypto( 2853): Read error: ssl=0x7ba42288: I/O error during system call, Connection timed out
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7ba42288: I/O error during system call, Broken pipe
,D/dalvikvm( 7304): GC_CONCURRENT freed 2993K, 30% free 9576K/13588K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7304): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/System.out( 7304): Inside WakeupProvider
,I/System.out( 7304): Inside onCreate() of WakeupTriggerProvide
,I/Choreographer( 7256): Skipped 160 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7256): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/VlingoApplication( 7304): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7304): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7304): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/ConnectivityService( 2421): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2421): updateIfacesLocked()
,V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 24ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,D/DialogFlow( 7304): initQueue()
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2421): Killing 6193:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2832): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2421): updateDataUsageMap
,D/Tethering( 2421): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2421): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0,
,I/PCWCLIENTTRACE_PushUtil( 6611): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6611): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6611): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6611): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6611): noConnectivity : true
,I/DBG_DM  ( 4759): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7333): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7333):  
,I/SELinux ( 7333): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7333):  
I/SELinux ( 7333):  
,I/SELinux ( 7333): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7333): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7333): >>>>> Normal User
,E/dalvikvm( 7333): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7333): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7333): in addTimaSignatureService
,I/wpa_supplicant( 3982): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3982): wlan0: Setting scan request: 8 sec 0 usec
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3982): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/TimaKeyStoreProvider( 7333): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7333): Added TimaKesytore provider
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2421): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3982): Associated with C0.AA.48
I/wpa_supplicant( 3982): freq(2412) increment count 2
,I/wpa_supplicant( 3982): meet head of list.
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/dalvikvm( 7333): GC_CONCURRENT freed 2997K, 30% free 9571K/13588K, paused 5ms+4ms, total 53ms
,D/dalvikvm( 7333): WAIT_FOR_CONCURRENT_GC blocked 47ms
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3982): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3982): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3982): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2421): interfaceLinkStateChanged wlan0, true
D/Tethering( 2421): interfaceStatusChanged wlan0, true
D/WifiNative( 2421): callSECApiVoid - ID [50]
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2421): Killing 6262:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
,D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
,I/SELinux ( 7347): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7347):  
,I/SELinux ( 7347): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7347):  
I/SELinux ( 7347):  
,I/SELinux ( 7347): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7347): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7347): >>>>> Normal User
,E/dalvikvm( 7347): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7347): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7347): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7347): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7347): Added TimaKesytore provider,
,D/dalvikvm( 7347): GC_CONCURRENT freed 3001K, 30% free 9569K/13592K, paused 4ms+3ms, total 39ms
,D/dalvikvm( 7347): WAIT_FOR_CONCURRENT_GC blocked 35ms
,I/dhcpcd  ( 7359): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7359): bssid match
,I/ActivityManager( 2421): Killing 6352:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7366): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7366):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 11% free 9506K/10572K, paused 3ms+4ms, total 42ms
,I/SELinux ( 7366): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7366):  
I/SELinux ( 7366):  
,I/SELinux ( 7366): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7366): >>>>> Normal User
,E/dalvikvm( 7366): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7366): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9506K/10572K, paused 3ms+4ms, total 35ms
,D/dalvikvm( 1921): WAIT_FOR_CONCURRENT_GC blocked 1ms
,D/TimaKeyStoreProvider( 7366): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7366): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7366): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9506K/10572K, paused 3ms+4ms, total 34ms
,D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7366): GC_CONCURRENT freed 3005K, 30% free 9569K/13592K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7366): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/KLMS-2.3.201 : ( 7366): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7366): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452517171624
,I/KLMS-2.3.201 : ( 7366): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2421): Killing 6368:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7378): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7378):  
,I/SELinux ( 7378): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7378):  
I/SELinux ( 7378):  
,I/SELinux ( 7378): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7378): >>>>> Normal User
,E/dalvikvm( 7378): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7378): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7378): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7378): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7378): Added TimaKesytore provider
,D/dalvikvm( 7378): GC_CONCURRENT freed 3007K, 30% free 9562K/13592K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7378): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5826): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5826): [BDLM] already registered in spp
I/SA      ( 5826): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5826): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5826): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5826): [OR] == isSIMCardReady false ==
I/SA      ( 5826): [SCU] == networkStateCheck == false
,I/SA      ( 5826): [OR] onReceive END
I/ActivityManager( 2421): Killing 6405:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7390): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7390):  
,I/SELinux ( 7390): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7390):  
I/SELinux ( 7390):  
,I/SELinux ( 7390): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7390): >>>>> Normal User
,E/dalvikvm( 7390): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7390): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7390): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7390): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7390): Added TimaKesytore provider
D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7390): GC_CONCURRENT freed 2994K, 30% free 9574K/13588K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 7390): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/sCloudBackupApp( 7390): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7390): Other Intent
I/ActivityManager( 2421): Killing 5608:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7405):  
,I/SELinux ( 7405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7405):  
I/SELinux ( 7405):  
,I/SELinux ( 7405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7405): >>>>> Normal User
,E/dalvikvm( 7405): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7405): Added TimaKesytore provider
,D/dalvikvm( 7405): GC_CONCURRENT freed 2998K, 30% free 9574K/13592K, paused 4ms+2ms, total 43ms
,D/dalvikvm( 7405): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7405): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7405): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7405): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7405): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5359): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2421): Killing 6314:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5890): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5890): getCountryCode(): countryCode = PL
,D/Headlines( 5890): Breath.onCreate
,D/Headlines( 5890): Breath timer started. interval : 30000
,I/SELinux ( 7437): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7437):  
,V/AlarmManager( 2421): waitForAlarm result :8
D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5890): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5890): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5890): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7437): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7437):  
I/SELinux ( 7437):  
,I/SELinux ( 7437): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7437): >>>>> Normal User
,E/dalvikvm( 7437): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7437): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7437): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7437): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7437): Added TimaKesytore provider
,D/dalvikvm( 7437): GC_CONCURRENT freed 3002K, 30% free 9575K/13596K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7437): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/WifiP2pService( 2421): InactiveState{ what=143375 }
D/WifiP2pService( 2421): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2421): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2421): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 2421): CaptivePortalCheckState enter
I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/WifiStateMachine( 2421): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2421): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/WifiTrafficPoller( 2421): evaluateTrafficStatsPolling
D/ConnectivityService( 2421): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2421): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2421): net.tcp.delack.wifi not found in system properties. Using defaults
D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 10
D/PackageManager( 2421): [MSG] WRITE_PACKAGE_RESTRICTIONS
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info 
V/WebViewChromium( 7437): Binding Chromium to the background looper Looper (main, tid 1) {422501d0}
I/chromium( 7437): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
I/BrowserProcessMain( 7437): Initializing chromium process, renderers=0
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
W/chromium( 7437): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
V/RouteController( 1915): RTNETLINK answers: No such file or directory
V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
D/libEGL  ( 7437): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7437): loaded /system/lib/egl/libGLESv1_CM_mali.so
V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
D/libEGL  ( 7437): loaded /system/lib/egl/libGLESv2_mali.so
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
I/Mali    ( 7437): Mali API Version : 401
I/Mali    ( 7437): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
V/NetworkStats( 2421): updateIfacesLocked()
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 24ms
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
W/GAV2    ( 7437): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/ContextImpl( 7437): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
I/NSApplication( 7437): Starting up...
I/iu.Environment( 5957): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
D/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5160): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4225fd30
I/SELinux ( 7491): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7491):  
I/SELinux ( 7491): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7491):  
I/SELinux ( 7491):  
I/SELinux ( 7491): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7491): >>>>> Normal User
E/dalvikvm( 7491): >>>>> com.android.email [ userId:0 | appId:10157 ]
E/SELinux ( 7491): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider( 7491): in addTimaSignatureService
D/TimaKeyStoreProvider( 7491): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7491): Added TimaKesytore provider
D/Tethering( 2421): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2421): MasterInitialState.processMessage what=3
D/CaptivePortalTracker( 2421): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
I/jxcore-log( 7256): Connected to the server!
I/jxcore-log( 7256): 
I/DBG_DM  ( 4759): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
I/chromium( 7256): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7491): GC_CONCURRENT freed 2988K, 30% free 9588K/13596K, paused 2ms+3ms, total 28ms,
,D/dalvikvm( 7491): WAIT_FOR_CONCURRENT_GC blocked 25ms,
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId,
,I/SELinux ( 7509): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7509):  
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId,
,W/ActivityManager( 2421): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,I/ActivityManager( 2421): Killing 6333:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7509):  
I/SELinux ( 7509):  
,I/SELinux ( 7509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7509): >>>>> Normal User
,E/dalvikvm( 7509): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7509): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7509): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7509): Added TimaKesytore provider
,I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7523):  
,I/ActivityManager( 2421): Killing 6008:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7523):  
I/SELinux ( 7523):  
,I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService
,D/dalvikvm( 7509): GC_CONCURRENT freed 3002K, 30% free 9569K/13592K, paused 5ms+3ms, total 31ms
,D/dalvikvm( 7509): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7523): Added TimaKesytore provider
,D/BadgeProvider( 7509): onCreate
,D/BadgeProvider( 7509): DatabaseHelper
,D/BadgeProvider( 7509): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7509): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7509): sendNotify, [notify] : null
D/BadgeProvider( 7509): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2770): reloadBadges entered.
D/BadgeProvider( 7509): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7509): update, [UpdateCount] : 1
,D/dalvikvm( 7523): GC_CONCURRENT freed 3013K, 30% free 9562K/13596K, paused 4ms+3ms, total 37ms
,D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 32ms
,I/dalvikvm( 7256): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7256): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7256): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7256): Shutting down VM
,W/dalvikvm( 7256): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7256): FATAL EXCEPTION: main
E/AndroidRuntime( 7256): Process: com.test.thalitest, PID: 7256
E/AndroidRuntime( 7256): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7256): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7256): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7256): 	at io.jxcore.node.JXcoreExtension$4.Receiver(JXcoreExtension.java:112)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7256): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7256): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7256): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7256): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7256): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7256): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7256): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7256): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7256): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7256): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2421):   Force finishing activity com.test.thalitest/.MainActivity
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2421): Killing 6282:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/Process ( 7256): Sending signal. PID: 7256 SIG: 9
,D/CrashAnrDetector( 2421): processName: com.test.thalitest
,D/CrashAnrDetector( 2421): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/hcjo    ( 5980): AutoUpdateManager:IDLE:execute
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2421): mDVFSHelper.acquire()
D/InitializeManagerStateMachine( 5980): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5980): exit::IDLE
D/InitializeManagerStateMachine( 5980): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5980): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5980): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5980): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5980): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5980): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5980): entry::SUCCESS
D/hcjo    ( 5980): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5980): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5980): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5980): exit::SUCCESS
,D/InitializeManagerStateMachine( 5980): entry::IDLE
,I/DBG_DM  ( 4759): [3.19.140541][Line:408][onResume] 
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (8/10)
I/WindowState( 2421): WIN DEATH: Window{42f9b9b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
I/ActivityManager( 2421): Process com.test.thalitest (pid 7256) (adj 9) has died.
,I/DBG_DM  ( 4759): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 269464
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5562): [[SystemStateMonitorService]] No Active Internet
,I/DBG_DM  ( 4759): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4759): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/DBG_DM  ( 4759): [3.19.140541][Line:418][onResume] Postpone Count : 29
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
,I/DBG_DM  ( 4759): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,D/Headlines( 5890): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5890): Breath 1982 latestRequest time : 1452517172705 current time : 1452517174687
,I/DBG_DM  ( 4759): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,E/SPPClientService( 5562): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5562): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/DBG_DM  ( 4759): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2832): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - P2P: IDLE
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,I/NearbySettings( 2832): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,D/STATUSBAR-StatusBarManagerService( 2421): sendNotification(2) - 4
I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
I/DBG_DM  ( 4759): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/DBG_DM  ( 4759): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4759): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4759): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4759): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4759): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4759): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4759): setTransGradationMode to true
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4759): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2421): semi p:4759,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2421): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2421): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2421): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2421): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2421): setHoveringSpenCustomIcon IconType is same.1
W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2421): Got RemoteException sending setActive(false) notification to pid 7256 uid 10608
,D/NearbySettings( 2832): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2832): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
I/PCWCLIENTTRACE_PushUtil( 6611): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6611): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6611): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6611): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2421): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421
,E/SPPClientService( 5562): [a] [ConnectionManager] Connection is already disconnected.
D/libgps  ( 2421): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SPPClientService( 5562): [g] getNetMCC return empty string
D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2421): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2421): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 2421): GC_EXPLICIT freed 4801K, 71% free 25166K/86008K, paused 8ms+16ms, total 171ms
,I/KLMS-2.3.201 : ( 7366): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7366): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452517175200
,I/KLMS-2.3.201 : ( 7366): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3435): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3435): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7378): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3563): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7551): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7551):  
,I/SELinux ( 7551): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7551):  
I/SELinux ( 7551):  
,I/SELinux ( 7555): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7555):  
,I/SELinux ( 7551): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7551): >>>>> Normal User
,E/dalvikvm( 7551): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7551): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7551): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7551): Added TimaKesytore provider
,I/SELinux ( 7555): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7555):  
I/SELinux ( 7555):  
,I/SELinux ( 7555): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/SA      ( 5826): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
E/SELinux ( 7555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7555): >>>>> Normal User
,E/dalvikvm( 7555): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,I/SA      ( 5826): [BDLM] already registered in spp
I/SA      ( 5826): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5826): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,E/SELinux ( 7555): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SA      ( 5826): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5826): [OR] == isSIMCardReady false ==
,I/SA      ( 5826): [SCU] == networkStateCheck == true
I/SA      ( 5826): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5826): isChinaCountryCode : false
,I/SA      ( 5826): [OR] == networkStateCheck true ==
,I/System.out( 7347): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 5826): [OR] GetMyCountryZoneTask
,I/SA      ( 5826): [OR] onReceive END
,D/TimaKeyStoreProvider( 7555): in addTimaSignatureService
,I/System.out( 7347): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7347): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/TimaKeyStoreProvider( 7555): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7555): Added TimaKesytore provider
,I/SA      ( 5826): [SRS] prepareGetMyCountryZone
,I/SA      ( 5826): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5826): [SSP] query invoked
,I/SA      ( 5826): [TPMU] GetMccFromDB : null
I/SA      ( 5826): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5826): [TPM] isNoProxy(default) : true
,I/SA      ( 5826): [RC New] Execute method=[GET] start
,D/dalvikvm( 7551): GC_CONCURRENT freed 2993K, 30% free 9577K/13592K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 7551): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7390): Other Intent
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7405): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5890): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5890): getCountryCode(): countryCode = PL
D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5890): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5890): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5890): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5890): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 7555): GC_CONCURRENT freed 3012K, 30% free 9560K/13596K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7555): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/iu.Environment( 5957): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5160): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5160): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4225fd30
,V/KVNProvider( 7555): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7555): getFindoCursor query string : 
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/RCPManagerService( 2421): exchangeData() failure , invalid userId
,D/dalvikvm( 5957): GC_CONCURRENT freed 505K, 6% free 26848K/28384K, paused 3ms+5ms, total 39ms
,V/KVNProvider( 7555): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5980): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5980): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5980): exit::IDLE
,D/InitializeManagerStateMachine( 5980): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5980): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5980): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5980): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5980): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5980): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5980): entry::SUCCESS
,D/hcjo    ( 5980): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5980): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5980): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5980): exit::SUCCESS
,D/InitializeManagerStateMachine( 5980): entry::IDLE
,E/SPPClientService( 5562): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5562): [SystemStateMoniter] Current Time : 270406
,E/SPPClientService( 5562): [SystemStateMoniter] No Connect : false
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/libgps  ( 2421): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2421): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2421): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/CustomFrequencyManagerService( 2421): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2421  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 5562): GC_CONCURRENT freed 2017K, 24% free 10438K/13572K, paused 5ms+4ms, total 47ms
,I/System.out( 7347): AsyncTask #1 calls detatch()
,W/System.err( 7347): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7347): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7347): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7347): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7347): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7347): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7347): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7347): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7347): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7347): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7347): Caused by: java.lang.NullPointerException
,W/System.err( 7347): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7347): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7347): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7347): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7347): 	... 8 more
,I/ActivityManager( 2421): Killing 6180:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/SA      ( 5826): [RC New] [v2liruge] api execute + 894
,I/SA      ( 5826): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5826): AsyncTask #2 calls detatch()
,I/SA      ( 5826): [TPMU] getNetworkMcc : 
,I/SA      ( 5826): [SCU] saveMccToPreferece Start
I/SA      ( 5826): [SCU] RegionMCC : 260
,I/SA      ( 5826): [SSP] query invoked
I/SA      ( 5826): [TPMU] GetMccFromDB : null
,I/SA      ( 5826): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5826): [SCU] saveMccToPreferece End
I/SA      ( 5826): [RC New] executeRequest [v2liruge] end. 939
,I/SA      ( 5826): [RC New] Execute end
I/SA      ( 5826): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5826): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2421): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5562): [b] __InitReply__,
,W/WifiP2pStateTracker( 2421): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
,D/ConnectivityService( 2421): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0,
D/ConnectivityService( 2421):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
D/ConnectivityService( 2421): handleConnectivityChange: setting default proxy info ,
,D/ConnectivityService( 2421): updateSourceRoutes : no source routing conditions,
,I/ActivityManager( 2421): Killing 6215:com.google.android.music:main/u0a125 (adj 15): empty #43,
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11),
,D/PowerManagerService( 2421): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2421) eventTime = 273143,
,D/PowerManagerService( 2421): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2421 (0x0)
,D/PowerManagerService( 2421): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2421, ws=WorkSource{1000}) (elapsedTime=3490),
,I/GAV2    ( 7437): Thread[GAThread,5,main]: No campaign data found.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6611): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6611): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6611): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6611): [GetString-S]
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6611): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6611): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6611): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6611): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6611): [ensureRegistration] - No Samsung account,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 320, Delta = 0,
,D/CaptivePortalTracker( 2421): DelayedCaptiveCheckState{ when=-7ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2421): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2421): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2421): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2421): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2421): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2421): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2421): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5980): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5980): exit::IDLE,
,D/PreloadUpdateManagerStateMachine( 5980): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5980): AutoUpdateTriggerManager:IDLE:notifyNextTime,
,D/PreloadUpdateManagerStateMachine( 5980): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
,D/PreloadUpdateManagerStateMachine( 5980): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5980): entry::IDLE,
,D/PreloadUpdateManagerStateMachine( 5980): execute::IDLE:EXECUTE,
D/PreloadUpdateManagerStateMachine( 5980): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5980): entry::CHECK_TIMEOUT_FOR_UPDATE,
D/hcjo    ( 5980): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5980): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
D/PreloadUpdateManagerStateMachine( 5980): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5980): entry::IDLE,
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4,
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{4485bef0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/ActivityManager( 2421): Waited long enough for: ServiceRecord{448faaf8 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4009): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = -10,
,E/Watchdog( 2421): !@Sync 9,
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,I/PowerManagerService( 2421): [PWL] Off : 180s ago,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,D/Headlines( 5890): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5890): Breath 27250 latestRequest time : 1452517175460 current time : 1452517202711
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. ,
D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2421): initializing...,
I/TLC_TIMA_PKM_initialize( 2421): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32,
I/TZ: mc_tlc_communication( 2421): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2421): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 2421): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2421): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2421): aligned max_sendmsg_size = 262208,
I/TZ: mc_tlc_communication( 2421): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2421): device_id = 0x0
,I/TZ: mc_tlc_communication( 2421): tlc_open() was called
,I/TZ: mc_tlc_communication( 2421): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2421): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2421): Opening the session,
,I/TZ: mc_tlc_communication( 2421): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2421): Trustlet response is completed,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 10
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged,
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2581): GC_CONCURRENT freed 15703K, 34% free 33879K/50600K, paused 9ms+9ms, total 88ms
,V/AlarmManager( 2421): waitForAlarm result :8
,D/Headlines( 5890): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5890): Breath 57250 latestRequest time : 1452517175460 current time : 1452517232710
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2421): [PWL] Off : 225s ago,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 11,
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4,
,V/AlarmManager( 2421): waitForAlarm result :4,
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8030):  
,I/SELinux ( 8030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 8030):  
I/SELinux ( 8030):  
I/SELinux ( 8030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 8030): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 8030): >>>>> Normal User
,E/dalvikvm( 8030): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 8030): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 8030): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 8030): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 8030): Added TimaKesytore provider,
,D/dalvikvm( 8030): GC_CONCURRENT freed 3010K, 30% free 9558K/13588K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 8030): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,I/ActivityManager( 2421): Killing 6552:com.android.defcontainer/u0a6 (adj 15): empty #43,
,V/AlarmManager( 2421): waitForAlarm result :8,
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,V/AlarmManager( 2421): waitForAlarm result :8,
,D/Headlines( 5890): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5890): Breath 87259 latestRequest time : 1452517175460 current time : 1452517262719,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4,
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 12
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5890): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5890): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5890): Breath 120444 latestRequest time : 1452517175460 current time : 1452517295904
,D/Headlines( 5890): stop 
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
I/SELinux ( 8129): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8129):  
,D/Headlines( 5890): Breath.onDestroy : 
,I/ActivityManager( 2421): Killing 6466:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 11% free 9506K/10572K, paused 3ms+4ms, total 64ms
,I/SELinux ( 8129): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8129):  
I/SELinux ( 8129):  
,I/SELinux ( 8129): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8129): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8129): >>>>> Normal User
,E/dalvikvm( 8129): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8129): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9506K/10572K, paused 4ms+4ms, total 37ms
,D/TimaKeyStoreProvider( 8129): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8129): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8129): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 11% free 9506K/10572K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 8129): GC_CONCURRENT freed 2997K, 30% free 9576K/13592K, paused 3ms+3ms, total 30ms
,D/dalvikvm( 8129): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/SPPClientService( 8129): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8129): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8129): PushLog.txt file is not deleted.
D/SPPClientService( 8129): PushLog.txt file is not deleted.
,D/SPPClientService( 8129): ============PushLog. stop!
,I/ActivityManager( 2421): Killing 6585:com.samsung.groupcast/u0a15 (adj 15): empty #43
,E/SPPClientService( 5562): [b] __PingReply__
,I/PowerManagerService( 2421): [PWL] Off : 275s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 13
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 14
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2421): [PWL] Off : 330s ago
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 15
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 16
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/GKI_LINUX( 4009): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/        ( 4009): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4009): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.NAME_CHANGED
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,I/PowerManagerService( 2421): [PWL] Off : 390s ago
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/        ( 4009): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.NAME_CHANGED
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: S5-1
,D/dalvikvm( 6446): GC_CONCURRENT freed 2568K, 27% free 10094K/13680K, paused 4ms+3ms, total 64ms
D/dalvikvm( 6446): WAIT_FOR_CONCURRENT_GC blocked 26ms
,E/bt-btm  ( 4009): tBTM_SEC_DEV:0x77dcc2f0 rs_disc_pending=1
E/bt-btm  ( 4009): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 4009): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/dalvikvm( 6446): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2832): ACTION_ACL_DISCONNECTED
,I/SELinux ( 8450): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8450):  
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
I/SELinux ( 8450): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8450):  
I/SELinux ( 8450):  
,I/SELinux ( 8450): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8450): >>>>> Normal User
,E/dalvikvm( 8450): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8450): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 8450): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8450): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8450): Added TimaKesytore provider
,D/dalvikvm( 8450): GC_CONCURRENT freed 2990K, 30% free 9573K/13588K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 8450): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/UserAnalysis.PlaceProvider( 8450): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8450): Create SecureDbHelper
,I/ActivityManager( 2421): Killing 6597:com.android.musicfx/u0a24 (adj 15): empty #43
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: XT1072
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/bt-btm  ( 4009): btm_sec_disconnected - Clearing Pending flag
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,E/BluetoothEventManager( 2832): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: S5-1
,D/GKI_LINUX( 4009): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/btif_config_util( 4009): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/GKI_LINUX( 4009): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/        ( 4009): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,E/BluetoothRemoteDevices( 4009): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.NAME_CHANGED
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,E/bt-btm  ( 4009): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4009): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,E/BluetoothEventManager( 2832): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: A5-1
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/btif_config_util( 4009): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
E/Watchdog( 2421): !@Sync 17
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 2421): GC_CONCURRENT freed 3888K, 71% free 25110K/86008K, paused 17ms+18ms, total 306ms
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 286, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,E/Watchdog( 2421): !@Sync 18
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 455s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 19
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 34:fc:ef:11:ae:67
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:24841
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 6:2003
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 20
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 525s ago
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4009): db_query_execute: result 1
D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,W/ContextImpl( 2421): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2421): !@Sync 21
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2421): Skipping unknown process pid 8994
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/GAV2    ( 5654): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5654): Thread[disconnect check,5,main]: Disconnected from service
,D/GKI_LINUX( 4009): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,E/Watchdog( 2421): !@Sync 22
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2421): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/GKI_LINUX( 4009): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4009): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/        ( 4009): remote version info [7c:f9:0e:37:96:ab]: 7, 1d, 7d3
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: A5-1
,D/UserAnalysis.CarAnalyzer( 8450): Create SecureDbHelper
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,E/bt-btm  ( 4009): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4009): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4009): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:37:96:ab
D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_LMP_VER, value 7:2003
,D/IOP_DB_BT( 4009): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4009): db_query_execute: result 1
,D/KeyguardViewMediator( 2581): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2581): isGear1: device is not B1!
,V/BluetoothEventManager( 2832): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2832): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6446): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:37:96:AB, alias=null, name=A5-1, majorDeviceClass=0, deviceClass=0])
,I/BluetoothClassifier( 6446): Bluetooth Device Name: A5-1
,D/GKI_LINUX( 4009): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/BluetoothAdapterService(1109688568)( 4009): Get Bonded Devices being called
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/btif_config_util( 4009): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 23
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4080): GC_CONCURRENT freed 2893K, 29% free 9729K/13640K, paused 17ms+3ms, total 66ms
,I/PowerManagerService( 2421): [PWL] Off : 600s ago
,V/AlarmManager( 2421): waitForAlarm result :8
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2421): LightSensor enable = 0
D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 3
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 24
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 25
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 680s ago
,E/Watchdog( 2421): !@Sync 26
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 27
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 28
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 765s ago
,E/Watchdog( 2421): !@Sync 29
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 30
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 31
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_CONCURRENT freed 4090K, 72% free 24927K/86008K, paused 20ms+17ms, total 232ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 855s ago
,E/Watchdog( 2421): !@Sync 32
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 33
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 34
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 950s ago
,E/Watchdog( 2421): !@Sync 35
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2770): GC_CONCURRENT freed 7043K, 38% free 18948K/30512K, paused 15ms+7ms, total 99ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 36
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 37
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2421): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 38
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 39
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 40
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 41
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1155s ago
,E/Watchdog( 2421): !@Sync 42
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5562): [b] __PingReply__
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 43
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
V/AlarmManager( 2421): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2421): waitForAlarm result :4
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3280): Aggregate from 1452516318193 (log), 1452516318193 (data)
,D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 6
D/Sensors ( 2421): LightSensor enable = 0
D/Sensors ( 2421): LightSensor enableSensor = 0
D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/dalvikvm( 3280): GC_CONCURRENT freed 1773K, 19% free 12669K/15468K, paused 6ms+8ms, total 71ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 44
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 45
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_CONCURRENT freed 3763K, 72% free 24920K/86004K, paused 14ms+16ms, total 210ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 46
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 47
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4080): GC_CONCURRENT freed 2050K, 29% free 9726K/13640K, paused 2ms+3ms, total 31ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 48
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 49
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 50
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 51
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 52
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :4
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5562): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,E/SPPClientService( 5562): [b] __PingReply__
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 53
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2421): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2421): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 54
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 55
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 56
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 57
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,I/PowerManagerService( 2421): [PWL] Off : 1625s ago
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 58
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 59
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2421): GC_CONCURRENT freed 3806K, 72% free 24916K/86004K, paused 11ms+16ms, total 205ms
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/TimaService( 2421): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2421): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2421): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
W/ProcessCpuTracker( 2421): Skipping unknown process pid 11858
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2421): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2421): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2421): !@Sync 60
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 61
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2421): Prepared write state in 42ms
,I/ProcessStatsService( 2421): Prepared write state in 52ms
,I/ProcessStatsService( 2421): Pruning old procstats: /data/system/procstats/state-2016-01-10-15-24-00.bin
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2421): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 62
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 63
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2421): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2421): <AppSync3 Whitelist>
,V/AlarmManager( 2421): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2421): waitForAlarm result :4
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked(flags=0x3)
,V/AlarmManager( 2421): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
V/NetworkStats( 2421): performPollLocked() took 50ms
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2421): currentTimeMillis() cache hit
,I/SELinux (12068): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12068):  
,I/SELinux (12068): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12068):  
I/SELinux (12068):  
,I/SELinux (12068): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12068): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12068): >>>>> Normal User
,E/dalvikvm(12068): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12068): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12068): in addTimaSignatureService
,D/TimaKeyStoreProvider(12068): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12068): Added TimaKesytore provider
,D/dalvikvm(12068): GC_CONCURRENT freed 3005K, 30% free 9559K/13588K, paused 3ms+2ms, total 27ms
,D/dalvikvm(12068): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/@ WidgetProvider(12068): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12068): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12068): Widget random data : 4
,D/@ WidgetProvider(12068): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12068): Widget random data : 2
,I/ActivityManager( 2421): Killing 6623:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,E/dalvikvm(12068): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
,W/dalvikvm(12068): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12068): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12068): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
,W/dalvikvm(12068): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12068): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12068): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12068): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(12068): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12068): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12068): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12068): VFY: replacing opcode 0x22 at 0x0038
,I/SensorManagerA( 2421): getReportingMode :: sensor.mType = 5
,D/LightsService( 2421): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/dalvikvm(12068): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(12068): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12068): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12068): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
D/Sensors ( 2421): LightSensor setDelay = 200000000
D/Sensors ( 2421): LightSensor setSensorDelay = 200000000
D/Sensors ( 2421): Light sensor flush: not enabled 0
D/Sensors ( 2421): LightSensor enable = 1
D/Sensors ( 2421): LightSensor enableSensor = 1
D/SensorManager( 2421): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2853): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12068): Thread-678(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7bac2868: I/O error during system call, Connection timed out
,I/System.out(12068): Thread-678(ApacheHTTPLog):isShipBuild true
,I/System.out(12068): Thread-678(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2421): LightSensor enable = 0
,D/Sensors ( 2421): LightSensor enableSensor = 0
,D/SensorManager( 2421): unregisterListener ::   
D/LightsService( 2421): [SvcLED]  onSensorChanged::light value = 4
D/LightsService( 2421): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12068): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12068): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12068): Max ALLOWED memory (MB): 128
V/ImageManager(12068): Max SHOULD USE memory (MB): 128
,V/ImageManager(12068): Max Image Cache memory (MB): 32
,D/skia    (12068): getTotalSize : Do not get file length
,D/@ WidgetProvider(12068): Building widget : 5
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 64
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 65
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,I/ActivityManager( 2421): Killing 6460:com.sec.knox.bridge/1000 (adj 15): empty for 1821s
,I/ActivityManager( 2421): Killing 4880:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1821s
,I/ActivityManager( 2421): Killing 6422:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1830s
,I/ActivityManager( 2421): Killing 6771:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1831s
,I/ActivityManager( 2421): Killing 6757:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1831s
,I/ActivityManager( 2421): Killing 6745:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1832s
I/ActivityManager( 2421): Killing 6733:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1832s
,I/ActivityManager( 2421): Killing 6720:com.samsung.helphub/1000 (adj 15): empty for 1832s
,I/ActivityManager( 2421): Killing 6707:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1832s
,I/ActivityManager( 2421): Killing 6694:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1832s
,I/ActivityManager( 2421): Killing 6681:com.sec.android.service.cm/u0a82 (adj 15): empty for 1833s
,I/ActivityManager( 2421): Killing 6381:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1833s
I/ActivityManager( 2421): Killing 5710:com.android.mms/u0a49 (adj 15): empty for 1833s
,I/ActivityManager( 2421): Killing 6655:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1833s
,I/ActivityManager( 2421): Killing 6024:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1833s
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2421): No listener is left
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2421): mCoverManager.getCoverState() : true
V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): stay LED for fully charged
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 66
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2421): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 273, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2421): stay LED for fully charged
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2421): !@Sync 67
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2421): waitForAlarm result :8
,V/AlarmManager( 2421): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2421): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2421): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2421): mCoverManager.getCoverState() : true
,D/BatteryService( 2421): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4009): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4009): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2421): !@Sync 68
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2421): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2421): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
