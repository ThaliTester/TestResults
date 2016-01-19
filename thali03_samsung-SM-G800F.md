#### Test 564317025f150b2_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7129): 
D/AndroidRuntime( 7129): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7129): CheckJNI is OFF
D/AndroidRuntime( 7129): setted country_code = Poland
D/AndroidRuntime( 7129): setted countryiso_code = PL
D/AndroidRuntime( 7129): setted sales_code = PLS
D/AndroidRuntime( 7129): readGMSProperty: start
D/AndroidRuntime( 7129): readGMSProperty: already setted!!
D/AndroidRuntime( 7129): readGMSProperty: end
D/AndroidRuntime( 7129): addProductProperty: start
D/dalvikvm( 7129): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7129): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7129): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7129): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7129): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7129): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7129): failed to load memtrack module: -2
D/dalvikvm( 7129): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7129): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2409): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2409): mDVFSHelper.acquire()
I/SELinux ( 7157): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7157):  
D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7129): Shutting down VM
D/dalvikvm( 7129): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7157): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7157):  
I/SELinux ( 7157):  
I/SELinux ( 7157): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7157): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7157): >>>>> Normal User
E/dalvikvm( 7157): >>>>> com.test.thalitest [ userId:0 | appId:10637 ]
E/SELinux ( 7157): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7157): in addTimaSignatureService
D/TimaKeyStoreProvider( 7157): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7157): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4170): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4170): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7157): GC_CONCURRENT freed 3014K, 31% free 9558K/13688K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7157): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7157): Binding Chromium to the background looper Looper (main, tid 1) {4226a308}
I/chromium( 7157): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7157): Initializing chromium process, renderers=0
,W/chromium( 7157): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7157): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7157): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7157): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7157): Mali API Version : 401
,I/Mali    ( 7157): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7157): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7157): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7157): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7157): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7157): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7157): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2409): tr p:7157,o:f
W/dalvikvm( 7157): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7157): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7157): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7157): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7157): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7157): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7157): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7157): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7157): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7157): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7157): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7157): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7157): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2409): semi p:7157,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7157): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7157): Enabling debug mode 0
,W/AwContents( 7157): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7157): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@8,
,W/ActivityManager( 2409): mDVFSHelper.release()
,D/JsMessageQueue( 7157): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7157): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4226b090
,D/dalvikvm( 7157): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4226b090,
D/jxcore_app_log( 7157): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028068872
,D/JX-Cordova( 7157): jxcore cordova android initializing,
,I/io.jxcore.node.ConnectionHelper( 7157): Build version SDK_INT: 19,
,D/dalvikvm( 7157): GC_CONCURRENT freed 1283K, 18% free 11347K/13744K, paused 2ms+2ms, total 22ms,
,D/dalvikvm( 7157): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,D/dalvikvm( 7157): GC_CONCURRENT freed 1715K, 16% free 15173K/18032K, paused 2ms+3ms, total 39ms,
,D/dalvikvm( 7157): WAIT_FOR_CONCURRENT_GC blocked 23ms,
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7157): GC_FOR_ALLOC freed 5699K, 30% free 16759K/23612K, paused 44ms, total 45ms,
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4361, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged,
,D/UiModeManager( 2409): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4012): Disconnected process message: 10,
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/dalvikvm( 7157): GC_CONCURRENT freed 6772K, 31% free 18144K/26068K, paused 3ms+11ms, total 78ms,
,D/dalvikvm( 7157): WAIT_FOR_CONCURRENT_GC blocked 50ms,
,D/dalvikvm( 7157): GC_FOR_ALLOC freed 925K, 31% free 18049K/26068K, paused 45ms, total 45ms,
,I/dalvikvm-heap( 7157): Grow heap (frag case) to 22.229MB for 3688532-byte allocation
,D/dalvikvm( 7157): GC_FOR_ALLOC freed 2484K, 36% free 19166K/29672K, paused 34ms, total 34ms
,D/dalvikvm( 7157): GC_FOR_ALLOC freed 2225K, 36% free 19194K/29672K, paused 40ms, total 40ms
,W/jxcore-log( 7157): Initializing JXcore engine
,W/jxcore-log( 7157): JXcore engine is ready
,W/jxcore-log( 7157): Starting JXcore engine
,W/jxcore-log( 7157): Platform android
W/jxcore-log( 7157): 
,W/jxcore-log( 7157): Process ARCH arm
W/jxcore-log( 7157): 
,I/jxcore-log( 7157): JXcore Cordova bridge is ready!
I/jxcore-log( 7157): 
,W/jxcore-log( 7157): JXcore engine is started
,I/chromium( 7157): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7157): Toggling radios to true
I/jxcore-log( 7157): 
,D/BluetoothAdapter( 7157): enable(): BT is already enabled..!
,I/WifiManager( 7157): packageName : com.test.thalitest
,I/WifiManager( 7157): setWifiEnabled : true
,I/WifiService( 2409): setWifiEnabled: true pid=7157, uid=10637
,W/ActivityManager( 2409): Permission Denial: getCurrentUser() from pid=7157, uid=10637 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2409): Failed getting userId using ActivityManagerNative
W/WifiService( 2409): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7157, uid=10637 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2409): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2409): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2409): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2409): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2409): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2409): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2409): disconnect: pid=7157, uid=10637
I/jxcore-log( 7157): Radios toggled
I/jxcore-log( 7157): 
I/wpa_supplicant( 3976): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7157): My device name is: samsung-SM-G800F
I/jxcore-log( 7157): 
,I/wpa_supplicant( 3976): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3976): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3976): First Scan Start
,W/Settings( 2409): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3976): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2409): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2409): InactiveState{ what=143375 }
D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 330, Delta = 0
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
I/wpa_supplicant( 3976): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3976): Skip scan - already scanning
D/ConnectivityService( 2409): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2409): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2409): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2409): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2409): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2409): InactiveState{ what=143375 }
D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2409): Attempting to switch to mobile
,D/ConnectivityService( 2409): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 7206): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7206):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2409): route cmd failed: 
W/NetworkManagementService( 2409): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2409): '
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2409): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2409): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2409): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2409): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2409): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2409): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,V/RouteController( 1915): RTNETLINK answers: No such process
,I/SELinux ( 7206): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7206):  
I/SELinux ( 7206):  
I/SELinux ( 7206): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
E/SELinux ( 7206): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7206): >>>>> Normal User
,E/dalvikvm( 7206): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/SELinux ( 7206): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2409): Error! unhandled message{ when=-108ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2409): Error! unhandled message{ when=-109ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
E/WifiStateMachine( 2409): Error! unhandled message{ when=-7ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/NetUtils( 2409): android_net_utils_resetConnections in env=0x77d19528 clazz=0x62400001 iface=wlan0 mask=0x3
,D/ConnectivityService( 2409): resetConnections(wlan0, 3)
D/TimaKeyStoreProvider( 7206): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7206): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7206): Added TimaKesytore provider
E/SPPClientService( 5592): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5592): [e] exceptionCaught(). NET_TIMEOUT
E/SPPClientService( 5592): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5592): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5592): [b] ResponseMap empty
,V/NativeCrypto( 2847): Read error: ssl=0x7bb101b8: I/O error during system call, Connection timed out
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7bb101b8: I/O error during system call, Broken pipe
,D/dalvikvm( 7206): GC_CONCURRENT freed 2993K, 31% free 9572K/13680K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7206): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/System.out( 7206): Inside WakeupProvider
,I/System.out( 7206): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2409): handleInetConditionChange: no active default network - ignore
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): updateIfacesLocked()
V/NetworkStats( 2409): performPollLocked(flags=0x1)
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7206): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7206): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7206): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 25ms
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4723): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7206): initQueue()
I/ActivityManager( 2409): Killing 6223:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4723): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2409): updateDataUsageMap
,D/Tethering( 2409): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2409): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6642): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6642): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6642): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6642): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6642): noConnectivity : true
,I/DBG_DM  ( 4774): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7234): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7234):  
,I/SELinux ( 7234): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7234):  
I/SELinux ( 7234):  
,I/SELinux ( 7234): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7234): >>>>> Normal User
,E/dalvikvm( 7234): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7234): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/wpa_supplicant( 3976): nl80211: Received scan results (3 BSSes)
I/wpa_supplicant( 3976): wlan0: Setting scan request: 8 sec 0 usec
,D/TimaKeyStoreProvider( 7234): in addTimaSignatureService
I/wpa_supplicant( 3976): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7234): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7234): Added TimaKesytore provider
,D/dalvikvm( 7234): GC_CONCURRENT freed 2997K, 31% free 9566K/13680K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7234): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3976): Associated with C0.AA.48
I/wpa_supplicant( 3976): freq(2412) increment count 2
,I/wpa_supplicant( 3976): meet head of list.
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3976): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3976): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3976): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2409): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2409): interfaceStatusChanged wlan0, true
,D/WifiNative( 2409): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,I/ActivityManager( 2409): Killing 6292:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 },
,I/SELinux ( 7249): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7249):  
,I/SELinux ( 7249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7249):  
I/SELinux ( 7249):  
,I/SELinux ( 7249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7249): >>>>> Normal User
,E/dalvikvm( 7249): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ],
,E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7249): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7249): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7249): Added TimaKesytore provider
,D/dalvikvm( 7249): GC_CONCURRENT freed 3011K, 31% free 9554K/13684K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/dhcpcd  ( 7261): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7261): bssid match
,I/ActivityManager( 2409): Killing 6347:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7268): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7268):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 11% free 9502K/10664K, paused 2ms+3ms, total 34ms
,I/SELinux ( 7268): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7268):  
I/SELinux ( 7268):  
,I/SELinux ( 7268): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7268): >>>>> Normal User
,E/dalvikvm( 7268): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7268): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7268): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7268): Cannot add TimaSignature Service, License check Failed
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 2ms+3ms, total 25ms
,D/ActivityThread( 7268): Added TimaKesytore provider
,D/dalvikvm( 7268): GC_CONCURRENT freed 2998K, 31% free 9571K/13684K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7268): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/KLMS-2.3.201 : ( 7268): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7268): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453190963957
,I/KLMS-2.3.201 : ( 7268): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2409): Killing 6371:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7300):  
,I/SELinux ( 7300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7300):  
I/SELinux ( 7300):  
,I/SELinux ( 7300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7300): >>>>> Normal User
,E/dalvikvm( 7300): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7300): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7300): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7300): Added TimaKesytore provider
,D/dalvikvm( 7300): GC_CONCURRENT freed 2997K, 31% free 9568K/13684K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7300): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/SO_AGENT( 7300): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7300): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5857): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5857): [BDLM] already registered in spp
,I/SA      ( 5857): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5857): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5857): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5857): [OR] == isSIMCardReady false ==
I/SA      ( 5857): [SCU] == networkStateCheck == false
,I/SA      ( 5857): [OR] onReceive END
I/ActivityManager( 2409): Killing 6367:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/WifiP2pService( 2409): InactiveState{ what=143375 }
,D/WifiP2pService( 2409): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2409): VerifyingLinkState enter
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2409): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2409): CaptivePortalCheckState enter
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2409): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2409): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2409): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2409): evaluateTrafficStatsPolling
D/ConnectivityService( 2409): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2409): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2409): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7313):  
I/SELinux ( 7313):  
I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7313): >>>>> Normal User
E/dalvikvm( 7313): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7313): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/dalvikvm( 7313): GC_CONCURRENT freed 2994K, 31% free 9569K/13680K, paused 4ms+1ms, total 26ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): updateIfacesLocked()
V/NetworkStats( 2409): performPollLocked(flags=0x1)
V/NetworkStats( 2409): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
V/NetworkStats( 2409): performPollLocked() took 26ms
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2409): currentTimeMillis() cache hit
,I/sCloudBackupApp( 7313): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7313): Other Intent
I/ActivityManager( 2409): Killing 6435:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7341): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7341):  
,I/SELinux ( 7341): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7341):  
I/SELinux ( 7341):  
,I/SELinux ( 7341): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7341): >>>>> Normal User
,E/dalvikvm( 7341): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7341): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7341): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7341): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7341): Added TimaKesytore provider
,D/dalvikvm( 7341): GC_CONCURRENT freed 2998K, 31% free 9570K/13684K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7341): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7341): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7341): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5389): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7341): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5389): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7341): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5389): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2409): Killing 5640:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/dalvikvm( 5389): GC_CONCURRENT freed 2565K, 28% free 9989K/13684K, paused 5ms+3ms, total 43ms
,D/Headlines( 5920): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5920): getCountryCode(): countryCode = PL
,D/Headlines( 5920): Breath.onCreate
,D/Headlines( 5920): Breath timer started. interval : 30000
,I/SELinux ( 7353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7353):  
,D/Headlines( 5920): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,V/AlarmManager( 2409): waitForAlarm result :8
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5920): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5920): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5920): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7353):  
I/SELinux ( 7353):  
,I/SELinux ( 7353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7353): >>>>> Normal User
,E/dalvikvm( 7353): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7353): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7353): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7353): Added TimaKesytore provider
,D/Tethering( 2409): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2409): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2409): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4774): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/dalvikvm( 7353): GC_CONCURRENT freed 2995K, 31% free 9571K/13684K, paused 10ms+2ms, total 41ms
,D/dalvikvm( 7353): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection...
,V/WebViewChromium( 7353): Binding Chromium to the background looper Looper (main, tid 1) {42267238}
,I/chromium( 7353): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7353): Initializing chromium process, renderers=0
,W/chromium( 7353): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7353): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7353): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7353): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7353): Mali API Version : 401
,I/Mali    ( 7353): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7353): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7353): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7353): Starting up...
,D/dalvikvm( 5988): GC_FOR_ALLOC freed 502K, 7% free 26750K/28476K, paused 47ms, total 47ms
,I/iu.Environment( 5988): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42274e10
,I/SELinux ( 7391): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7391):  
,I/SELinux ( 7391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7391):  
I/SELinux ( 7391):  
,I/SELinux ( 7391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7391): >>>>> Normal User
,E/dalvikvm( 7391): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7391): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7391): Added TimaKesytore provider
,D/dalvikvm( 7391): GC_CONCURRENT freed 2988K, 30% free 9584K/13688K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7391): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,I/SELinux ( 7409): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7409):  
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
I/SELinux ( 7409): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7409):  
I/SELinux ( 7409):  
,I/SELinux ( 7409): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7409): >>>>> Normal User
,E/dalvikvm( 7409): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7409): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2409): Killing 6325:com.sec.phone/1001 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7409): in addTimaSignatureService
,I/SELinux ( 7422): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7422):  
,D/TimaKeyStoreProvider( 7409): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7409): Added TimaKesytore provider
,I/SELinux ( 7422): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7422):  
I/SELinux ( 7422):  
,I/SELinux ( 7422): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7422): >>>>> Normal User
,E/dalvikvm( 7422): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,D/libgps  ( 2409): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/SELinux ( 7422): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager( 2409): Killing 6395:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7422): in addTimaSignatureService
,W/ActivityManager( 2409): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/TimaKeyStoreProvider( 7422): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7422): Added TimaKesytore provider
,D/dalvikvm( 7409): GC_CONCURRENT freed 3002K, 31% free 9565K/13684K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7409): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/BadgeProvider( 7409): onCreate
,D/BadgeProvider( 7409): DatabaseHelper
,D/dalvikvm( 7422): GC_CONCURRENT freed 2989K, 31% free 9575K/13684K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7422): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/BadgeProvider( 7409): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7409): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7409): sendNotify, [notify] : null
D/BadgeProvider( 7409): update, [uri] : content://com.sec.badge/apps/1
D/Launcher.Model( 2779): reloadBadges entered.
D/BadgeProvider( 7409): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7409): update, [UpdateCount] : 1
,D/hcjo    ( 6010): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6010): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6010): exit::IDLE
,D/InitializeManagerStateMachine( 6010): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6010): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6010): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6010): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6010): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6010): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6010): entry::SUCCESS
,D/hcjo    ( 6010): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6010): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6010): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6010): exit::SUCCESS
,D/InitializeManagerStateMachine( 6010): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 273729
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5592): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 2409): Killing 6038:com.android.calendar/u0a144 (adj 15): empty #43
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.,
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5592): [[PushClientService]] <<--- deInitPushClientService  END  --->>,
,E/SPPClientService( 5592): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state,
,D/Headlines( 5920): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,D/Headlines( 5920): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5920): Breath 1695 latestRequest time : 1453190964849 current time : 1453190966544
D/PowerManagerService( 2409): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409
,I/PCWCLIENTTRACE_PushUtil( 6642): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6642): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6642): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6642): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5592): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5592): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7268): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7268): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453190966742
,I/KLMS-2.3.201 : ( 7268): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7300): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3465): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3465): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7300): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3593): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7445): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7445):  
,I/SELinux ( 7445): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7445):  
I/SELinux ( 7445):  
,I/SELinux ( 7445): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7445): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7445): >>>>> Normal User
,E/dalvikvm( 7445): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7445): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7445): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7445): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7445): Added TimaKesytore provider
,I/System.out( 7249): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7249): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7249): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2409): GC_EXPLICIT freed 3990K, 74% free 25415K/97732K, paused 12ms+20ms, total 217ms
,I/SA      ( 5857): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5857): [BDLM] already registered in spp
I/SA      ( 5857): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5857): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5857): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5857): [OR] == isSIMCardReady false ==
,I/SA      ( 5857): [SCU] == networkStateCheck == true
,I/SELinux ( 7461): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7461):  
I/SA      ( 5857): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5857): isChinaCountryCode : false
,I/SA      ( 5857): [OR] == networkStateCheck true ==
,I/SELinux ( 7461): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7461):  
I/SELinux ( 7461):  
,I/SELinux ( 7461): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7461): >>>>> Normal User
,E/dalvikvm( 7461): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7461): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 7445): GC_FOR_ALLOC freed 3010K, 31% free 9555K/13684K, paused 50ms, total 50ms
,D/TimaKeyStoreProvider( 7461): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7461): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7461): Added TimaKesytore provider
,I/SA      ( 5857): [OR] GetMyCountryZoneTask
,I/SA      ( 5857): [OR] onReceive END
,D/dalvikvm( 7445): GC_CONCURRENT freed 239K, 15% free 9569K/11176K, paused 2ms+9ms, total 39ms
,D/libgps  ( 2409): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2409): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2409): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5857): [SRS] prepareGetMyCountryZone
,I/SA      ( 5857): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5857): [SSP] query invoked
,D/dalvikvm( 7461): GC_CONCURRENT freed 3002K, 31% free 9566K/13688K, paused 5ms+1ms, total 29ms
,D/dalvikvm( 7461): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled
,I/SA      ( 5857): [TPMU] GetMccFromDB : null
I/SA      ( 5857): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5857): [TPM] isNoProxy(default) : true
,I/SA      ( 5857): [RC New] Execute method=[GET] start
,I/SCloudBackupReceiver( 7313): Other Intent
,V/KVNProvider( 7461): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7461): getFindoCursor query string : 
,V/KVNProvider( 7461): getTagSearchCursor() tagSearchCursor count : 0
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7341): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/System.out( 7249): AsyncTask #1 calls detatch()
D/Headlines( 5920): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5920): getCountryCode(): countryCode = PL
D/Headlines( 5920): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5920): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5920): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5920): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5920): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5988): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,W/System.err( 7249): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7249): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7249): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7249): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7249): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7249): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7249): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7249): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7249): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7249): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7249): Caused by: java.lang.NullPointerException
W/System.err( 7249): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7249): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7249): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7249): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7249): 	... 8 more
D/PackageManager( 2409): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager( 2409): Killing 6210:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,I/QuickConnect[1.1][2] ( 5192): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5192): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42274e10
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/RCPManagerService( 2409): exchangeData() failure , invalid userId
,D/hcjo    ( 6010): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6010): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6010): exit::IDLE
,D/InitializeManagerStateMachine( 6010): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6010): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6010): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6010): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6010): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6010): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6010): entry::SUCCESS
,D/hcjo    ( 6010): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6010): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6010): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6010): exit::SUCCESS
,D/InitializeManagerStateMachine( 6010): entry::IDLE
,E/SPPClientService( 5592): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5592): [SystemStateMoniter] Current Time : 274899
,E/SPPClientService( 5592): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 5592): GC_CONCURRENT freed 2000K, 24% free 10444K/13664K, paused 5ms+5ms, total 55ms
,E/WifiStateMachine( 2409): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SA      ( 5857): [RC New] [v2liruge] api execute + 821
,I/SA      ( 5857): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5857): AsyncTask #2 calls detatch()
,I/SA      ( 5857): [TPMU] getNetworkMcc : 
,I/SA      ( 5857): [SCU] saveMccToPreferece Start
I/SA      ( 5857): [SCU] RegionMCC : 260
,I/SA      ( 5857): [SSP] query invoked
I/SA      ( 5857): [TPMU] GetMccFromDB : null
,I/SA      ( 5857): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5857): [SCU] saveMccToPreferece End
I/SA      ( 5857): [RC New] executeRequest [v2liruge] end. 847
I/SA      ( 5857): [RC New] Execute end
I/SA      ( 5857): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5857): [OR] GetMyCountryZoneTask Success
,E/SPPClientService( 5592): [b] __InitReply__
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7157): 
,D/BatteryService( 2409): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2409): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2409): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2409): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4012): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4012): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7157): 
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7157): 
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7157): 
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7157): 
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7157): 
,I/ActivityManager( 2409): Killing 6245:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
,I/jxcore-log( 7157): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7157): 
D/PowerManagerService( 2409): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2409) eventTime = 277373
D/PowerManagerService( 2409): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2409 (0x0)
D/PowerManagerService( 2409): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2409, ws=WorkSource{1000}) (elapsedTime=3474)
,W/WifiP2pStateTracker( 2409): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2409): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2409):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2409): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2409): updateSourceRoutes : no source routing conditions
,I/GAV2    ( 7353): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7157): Test app app.js loaded
I/jxcore-log( 7157): 
,I/dalvikvm( 7157): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7157): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7157): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7157): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7157): BLE advertisement is supported
I/jxcore-log( 7157): 
,I/chromium( 7157): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7157): --= Surplus to requirements =--
I/jxcore-log( 7157): 
I/jxcore-log( 7157): ****TEST TOOK:  ms ****
I/jxcore-log( 7157): 
,I/jxcore-log( 7157): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7157): 
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6642): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6642): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6642): failed to loading secure library
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 6642): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6642): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6642): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6642): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6642): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6642): [ensureRegistration] - No Samsung account
,D/AndroidRuntime( 7492): 
D/AndroidRuntime( 7492): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7492): CheckJNI is OFF
,D/AndroidRuntime( 7492): setted country_code = Poland
,D/AndroidRuntime( 7492): setted countryiso_code = PL
D/AndroidRuntime( 7492): setted sales_code = PLS
D/AndroidRuntime( 7492): readGMSProperty: start
,D/AndroidRuntime( 7492): readGMSProperty: already setted!!
D/AndroidRuntime( 7492): readGMSProperty: end
,D/AndroidRuntime( 7492): addProductProperty: start
,D/dalvikvm( 7492): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7492): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7492): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7492): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7492): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7492): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7492): failed to load memtrack module: -2
,D/dalvikvm( 7492): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/SSRMv2:SIOP( 2409): SIOP:: AP = 340, Delta = 10
,D/AndroidRuntime( 7492): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2409): START PACKAGE DELETE: observer{1121275496}
D/PackageManager( 2409): pkg{<packageName>}
D/PackageManager( 2409): user{0}
,D/PackageManager( 2409): deletePackageAsUser : uid = 2000 userId = 0
,D/ApplicationPolicy( 2409): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2409): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2409): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2409): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2409): !@killApplicatoin: 10637, uninstall pkg
,I/ActivityManager( 2409): Killing 7157:com.test.thalitest/u0a637 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2409): mDVFSHelper.acquire(),
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10),
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10),
,I/WindowState( 2409): WIN DEATH: Window{42fc91f8 u0 com.test.thalitest/com.test.thalitest.MainActivity},
D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2409): Skipping PackageSetting{42a84e78 com.example.hello/10614} due to missing metadata,
,D/PackageManager( 2409): setPackageStoppedState - Execution time: 109 ms,
D/PackageManager( 2409): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10637, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6475): GC_EXPLICIT freed 2530K, 28% free 9883K/13684K, paused 4ms+4ms, total 53ms,
,I/DBG_DM  ( 4774): [3.19.140541][Line:408][onResume] ,
,D/dalvikvm( 6801): GC_EXPLICIT freed 196K, 29% free 9957K/13900K, paused 13ms+8ms, total 98ms,
,D/dalvikvm( 3281): GC_EXPLICIT freed 1554K, 21% free 12394K/15556K, paused 18ms+8ms, total 108ms
,D/dalvikvm( 2941): GC_EXPLICIT freed 1464K, 27% free 10031K/13684K, paused 6ms+5ms, total 96ms,
,W/SQLiteConnectionPool( 3281): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.,
,I/DBG_DM  ( 4774): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30,
,D/PackageManager( 2409): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10637, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4774): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4774): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4774): [3.19.140541][Line:418][onResume] Postpone Count : 30
,I/DBG_DM  ( 4774): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,I/InputReader( 2409): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "sms"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/QuickConnect[1.1][2] ( 5192): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,E/SamsungIME( 2981): mOCRHelper is null
,I/DBG_DM  ( 4774): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4774): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/SELinux ( 7504): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7504):  
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "smsto"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
,I/SELinux ( 7504): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7504):  
I/SELinux ( 7504):  
,I/SELinux ( 7504): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7504): >>>>> Normal User
,E/dalvikvm( 7504): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7504): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "mms"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7504): in addTimaSignatureService
,D/dalvikvm( 2409): GC_EXPLICIT freed 2164K, 75% free 25009K/97732K, paused 13ms+26ms, total 291ms
,I/DBG_DM  ( 4774): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,D/dalvikvm( 2409): WAIT_FOR_CONCURRENT_GC blocked 177ms
,I/DBG_DM  ( 4774): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/TimaKeyStoreProvider( 7504): Cannot add TimaSignature Service, License check Failed
D/RegisteredServicesCache( 2760): empty dynamic service
,D/ActivityThread( 7504): Added TimaKesytore provider
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2409):   Scheme: "mmsto"
I/DBG_DM  ( 4774): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4774): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4774): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4774): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
I/DBG_DM  ( 4774): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/AmoledAdjustTimer( 2409): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,D/Activity( 4774): setTransGradationMode to true
,I/DBG_DM  ( 4774): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2409): semi p:4774,o:t
,D/RCPManagerService( 2409): PackageReceiver onReceive()
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
I/HarmonyEASService( 2409): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2409):   Scheme: "sms"
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-StatusBarManagerService( 2409): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2409): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2409): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2409): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2409): setHoveringSpenCustomIcon IconType is same.1
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "smsto"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "mms"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "mmsto"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@4
D/dalvikvm( 7504): GC_CONCURRENT freed 3000K, 31% free 9565K/13684K, paused 3ms+1ms, total 40ms
,D/dalvikvm( 7504): WAIT_FOR_CONCURRENT_GC blocked 33ms
W/ActivityManager( 2409): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2409): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 2760): GC_CONCURRENT freed 2329K, 26% free 10254K/13696K, paused 15ms+2ms, total 89ms
,D/elm:14132( 7504): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7504): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7504): MDMBridge.setEnterpriseBridge()
,D/EnterpriseDeviceManagerService( 2409): Package has changed for user 0
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/InputMethodManagerService( 2409): Got RemoteException sending setActive(false) notification to pid 7157 uid 10637
,D/elm:14132( 7504): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7504): ElmAgentService : onCreate()
D/elm:14132( 7504): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7504): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7504): MDMBridge.getInstance()
,D/elm:14132( 7504): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7504): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7518): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7518):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 11% free 9502K/10664K, paused 3ms+3ms, total 40ms
,I/SELinux ( 7518): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7518):  
I/SELinux ( 7518):  
,I/SELinux ( 7518): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7518): >>>>> Normal User
,E/dalvikvm( 7518): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7518): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 2ms+3ms, total 27ms
,D/TimaKeyStoreProvider( 7518): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7518): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7518): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 3ms+3ms, total 28ms
,D/elm:14132( 7504): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7504): ElmAgentService : onDestroy().
I/ActivityManager( 2409): Killing 6584:com.android.defcontainer/u0a6 (adj 15): empty #43
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 2409): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2409): removePackageParticipantsLocked: uid=10637 #1
,W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/STATUSBAR-StatusBarManagerService( 2409): sendNotification(2) - 4
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7518): GC_CONCURRENT freed 2998K, 31% free 9567K/13684K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7518): WAIT_FOR_CONCURRENT_GC blocked 14ms
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2409): GC_EXPLICIT freed 1301K, 75% free 25053K/97732K, paused 16ms+43ms, total 558ms
,D/PackageManager( 2409): delete sourFile : 
,I/SELinux ( 7533): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7533):  
D/PackageManager( 2409): delete native library directory: 
I/ActivityManager( 2409): Killing 6495:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/AndroidRuntime( 7492): Shutting down VM
D/PackageManager( 2409): return delete result to caller: 1121275496
D/PackageManager( 2409): returnCode: 1
,D/dalvikvm( 7492): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 6ms
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "sms"
I/SELinux ( 7533): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7533):  
I/SELinux ( 7533):  
,I/SELinux ( 7533): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7533): >>>>> Normal User
E/dalvikvm( 7533): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 7533): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7533): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7533): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7533): Added TimaKesytore provider
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2409):   Scheme: "smsto"
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "mms"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2409):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2409):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2409):   Scheme: "mmsto"
I/PackageManager( 2409): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,D/dalvikvm( 7533): GC_CONCURRENT freed 2997K, 31% free 9570K/13684K, paused 2ms+4ms, total 34ms
,D/dalvikvm( 7533): WAIT_FOR_CONCURRENT_GC blocked 31ms
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6642): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6642): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6642): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6642): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2409): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SA      ( 5857): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5857): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,I/CrashAnrDetector( 2409): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2409): clearDefaults: com.test.thalitest
,I/Icing.InternalIcingCorporaProvider( 6475): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7553):  
,W/ApplicationsProvider( 2941): Could not fetch usage stats,
W/ApplicationsProvider( 2941): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2941): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2941): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2941): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2941): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2941): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2941): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2941): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2941): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2941): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2941): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2941): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7553):  
I/SELinux ( 7553):  
,I/SELinux ( 7553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7553): >>>>> Normal User
,E/dalvikvm( 7553): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7553): in addTimaSignatureService
,E/SQLiteLog( 6475): (10) unixWrite() gets errno : 9
,D/TimaKeyStoreProvider( 7553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7553): Added TimaKesytore provider
,E/SQLiteLog( 6475): (10) unixWrite() gets errno : 9
,W/dalvikvm( 6475): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6475): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6475): Process: com.google.android.googlequicksearchbox:search, PID: 6475
E/AndroidRuntime( 6475): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6475): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6475): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6475): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 6475): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 6475): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:248)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6475): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6475): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6475): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6475): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6475): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6475): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6475): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6475): Sending signal. PID: 6475 SIG: 9
,E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.android.googlequicksearchbox:search (pid 6475) (adj 5) has died.
,D/dalvikvm( 7553): GC_CONCURRENT freed 2993K, 31% free 9569K/13680K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7553): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/UserAnalysis.PlaceProvider( 7553): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7553): Create SecureDbHelper
,E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7553): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7553): Opened privacy in read-only mode
E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7553): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7553): Opened privacy in read-only mode
E/SQLiteDatabase( 7553): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7553): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7553): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7553): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7553): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7553): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7553): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7553): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7553): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7553): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7553): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7553): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7553): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7553): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7553): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7553): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7553): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7553): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7553): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7553): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7553): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6489):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2409):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2409): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6710): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6710): The package(com.test.thalitest) removed
E/SQLiteDatabase( 6410): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6410): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6410): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6410): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6410): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6410): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6410): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6410): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6410): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6410): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6410): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6410): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6410): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6410): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6410): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6410): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6410): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6410): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6410): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6410): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6410): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6410): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6410): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6410): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6410): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2409): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2409): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2409): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2409): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2409): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2409): 	... 8 more
W/System.err( 2409): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2409): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2409): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2409): 	at android.os.Binder.execTransact(Binder.java:404)
D/CustomFrequencyManagerService( 2409): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2409  tag : ACTIVITY_RESUME_BOOSTER@8
W/System.err( 2409): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2409): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2409): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6736): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6736): [onHandleIntent] ACTION_PACKAGE_REMOVED
,I/SELinux ( 7568): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7568):  
E/SQLiteDatabase( 6736): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6736): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6736): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6736): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6736): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6736): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6736): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6736): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6736): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6736): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6736): Process: com.samsung.android.magazine.service, PID: 6736
E/AndroidRuntime( 6736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6736): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6736): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6736): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6736): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6736): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6736): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6736): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6736): Sending signal. PID: 6736 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.samsung.android.magazine.service (pid 6736) (adj 5) has died.
,I/SELinux ( 7568): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7568):  
I/SELinux ( 7568):  
,I/SELinux ( 7568): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7568): >>>>> Normal User
,E/dalvikvm( 7568): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7568): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7568): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7568): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7568): Added TimaKesytore provider
,D/dalvikvm( 7568): GC_CONCURRENT freed 3003K, 31% free 9565K/13688K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7568): WAIT_FOR_CONCURRENT_GC blocked 13ms
,W/ContextImpl( 7568): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7568): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7568): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7568): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7568): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7568): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6763): onReceive intent data =  package:com.test.thalitest
E/AndroidRuntime( 7568): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7568): Process: com.android.keychain, PID: 7568
E/AndroidRuntime( 7568): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7568): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7568): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7568): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7568): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7568): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7568): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7568): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7568): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7568): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/KidsPlatformStub( 6763): Package not found : com.sec.android.app.kidshome
,I/Process ( 7568): Sending signal. PID: 7568 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.android.keychain (pid 7568) (adj 5) has died.
,W/System.err( 6801): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6801): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6801): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6801): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6801): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6801): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6801): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 6801): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6801): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6801): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 6801): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6801): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6801): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3281): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3281): Clearing selected account for com.test.thalitest
,E/SQLiteLog( 3281): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/ChimeraCfgMgr( 3281): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3281): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3281): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 3281): disk I/O error (code 3850)
E/DriveAsyncService( 3281): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3281): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3281): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3281): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3281): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3281): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3281): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3281): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3281): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3281): 	at java.lang.Thread.run(Thread.java:841)
D/ChimeraCfgMgr( 3281): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3281): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 3281): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3281): threadid=49: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 2847): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2847): Shutting down VM
,W/dalvikvm( 2847): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3281): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3281): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3281): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3281): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3281): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3281): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 2847): FATAL EXCEPTION: main
E/AndroidRuntime( 2847): Process: com.google.process.gapps, PID: 2847
E/AndroidRuntime( 2847): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2847): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2847): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2847): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2847): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2847): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2847): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2847): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2847): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2847): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2847): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2847): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2847): 	... 10 more
E/SQLiteOpenHelper( 3281): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQ,LiteOpenHelper( 3281): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3281): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3281): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3281): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3281): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3281): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteDatabase( 3281): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3281): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3281): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 3281): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 3281): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
E/PhenotypeInitializer( 3281): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3281): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3281): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3281): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3281): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3281): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3281): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3281): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3281): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3281): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/gH_CompatibleDatabase( 3281): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/ClearPendingStateOp( 3281): Runtime exception while performing operation
E/ClearPendingStateOp( 3281): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3281): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3281): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.commo,n.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3281): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3281): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3281): 	at java.lang.Thread.run(Thread.java:841)
,I/Process ( 2847): Sending signal. PID: 2847 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,F/ClearPendingStateOp( 3281): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3281): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3281): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3281): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3281): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3281): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3281): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3281): 	at java.lang.Thread.run(Thread.java:841)
E/AndroidRuntime( 3281): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3281): Process: com.google.android.gms, PID: 3281
E/AndroidRuntime( 3281): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3281): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3281): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3281): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3281): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3281): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3281): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3281): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3281): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
E/AndroidRuntime( 3281): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3281): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3281): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3281): 	a,t java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3281): 	at java.lang.Thread.run(Thread.java:841)
,I/Process ( 3281): Sending signal. PID: 3281 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,E/SQLiteDatabase( 5592): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5592): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5592): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5592): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5592): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5592): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5592): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5592): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5592): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5592): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5592): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5592): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5592): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5592): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5592): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5592): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5592): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5592): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5592): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
E/DropBoxManagerService( 2409): Can't write: system_app_wtf
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,E/SQLiteDatabase( 6452): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6452): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6452): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6452): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6452): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6452): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6452): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6452): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6452): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6452): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6452): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6452): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7596): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7596):  
I/ActivityManager( 2409): Process com.google.process.gapps (pid 2847) (adj 5) has died.
,E/SQLiteDatabase( 6452): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6452): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6452): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6452): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6452): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6452): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6452): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6452): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6452): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6452): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6452): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6452): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6452): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6452): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6452): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/ActivityManager( 2409): Process com.google.android.gms (pid 3281) (adj 5) has died.
,I/SELinux ( 7596): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7596):  
I/SELinux ( 7596):  
,I/SELinux ( 7596): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7596): >>>>> Normal User
,E/dalvikvm( 7596): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7596): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/GAV2    ( 5685): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,D/TimaKeyStoreProvider( 7596): in addTimaSignatureService
,I/GAV2    ( 5685): Thread[main,5,main]: Unexpected disconnect.
,D/TimaKeyStoreProvider( 7596): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7596): Added TimaKesytore provider
,D/dalvikvm( 7596): GC_CONCURRENT freed 3002K, 31% free 9567K/13684K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7596): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/Documents( 7596): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7596): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7596): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7596): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7596): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7596): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7596): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7596): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7596): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7596): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7596): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7596): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7596): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7596): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7596): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7596): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7596): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7596): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7596): Shutting down VM
,W/dalvikvm( 7596): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7596): FATAL EXCEPTION: main
E/AndroidRuntime( 7596): Process: com.android.documentsui, PID: 7596
E/AndroidRuntime( 7596): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7596): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7596): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7596): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7596): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7596): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7596): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7596): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7596): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7596): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7596): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7596): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7596): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7596): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7596): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7596): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7596): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7596): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7596): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7596): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7596): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7596): 	... 10 more
,I/SELinux ( 7612): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7612):  
,I/SELinux ( 7616): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7616):  
,I/ActivityManager( 2409): Killing 6614:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/Process ( 7596): Sending signal. PID: 7596 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/SELinux ( 7612): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7612):  
I/SELinux ( 7612):  
,I/SELinux ( 7612): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2409): Process com.android.documentsui (pid 7596) (adj 9) has died.
E/SELinux ( 7612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7612): >>>>> Normal User
E/dalvikvm( 7612): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
E/SELinux ( 7612): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7612): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7612): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 7616): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7616):  
I/SELinux ( 7616):  
,I/SELinux ( 7616): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7616): >>>>> Normal User
E/dalvikvm( 7616): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,D/ActivityThread( 7612): Added TimaKesytore provider
E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7616): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7616): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7616): Added TimaKesytore provider
,D/dalvikvm( 7612): GC_CONCURRENT freed 2999K, 31% free 9565K/13684K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7612): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/ExternalStorage( 7612): After updating volumes, found 1 active roots
,D/dalvikvm( 7616): GC_CONCURRENT freed 2937K, 30% free 9629K/13684K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7616): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/dalvikvm( 7616): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7616): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7616): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7616): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7616): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7616): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7616): install
,I/MultiDex( 7616): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7616): loading existing secondary dex files
,I/MultiDex( 7616): load found 3 secondary dex files
,I/MultiDex( 7616): install done
,I/SELinux ( 7639): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7639):  
,I/SELinux ( 7644): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7644):  
,I/SELinux ( 7639): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7639):  
I/SELinux ( 7639):  
,I/SELinux ( 7639): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7639): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7639): >>>>> Normal User
,E/dalvikvm( 7639): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7639): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7639): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7639): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 7644): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7644):  
I/SELinux ( 7644):  
,I/SELinux ( 7644): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/ActivityThread( 7639): Added TimaKesytore provider
,E/SELinux ( 7644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7644): >>>>> Normal User
,E/dalvikvm( 7644): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7644): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7644): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7644): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7644): Added TimaKesytore provider
,D/dalvikvm( 7639): GC_CONCURRENT freed 2989K, 31% free 9575K/13680K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7639): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7644): GC_CONCURRENT freed 2993K, 31% free 9580K/13688K, paused 2ms+1ms, total 32ms
,D/dalvikvm( 7644): WAIT_FOR_CONCURRENT_GC blocked 30ms
,I/Icing.InternalIcingCorporaProvider( 7639): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/GservicesProvider( 7644): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7644): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7644): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7644): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7644): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7644): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7644): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7644): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7644): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7644): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7644): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7644): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7644): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7644): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7644): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7644): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7644): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7644): Shutting down VM
W/dalvikvm( 7644): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7670): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7670):  
E/AndroidRuntime( 7644): FATAL EXCEPTION: main
E/AndroidRuntime( 7644): Process: com.google.process.gapps, PID: 7644
E/AndroidRuntime( 7644): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7644): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7644): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7644): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7644): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7644): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7644): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7644): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7644): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7644): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7644): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7644): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7644): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7644): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7644): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7644): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7644): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7644): 	... 12 more
,I/Process ( 7644): Sending signal. PID: 7644 SIG: 9
,D/LocationManagerService( 2409): getProviders()=[passive]
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.process.gapps (pid 7644) (adj 0) has died.
,W/ActivityManager( 2409): Service crashed 2 times, stopping: ServiceRecord{42f8f258 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7670): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7670):  
I/SELinux ( 7670):  
,I/SELinux ( 7670): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/SELinux ( 7678): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7678):  
,E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7670): >>>>> Normal User
,E/dalvikvm( 7670): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7670): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7670): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7670): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7670): Added TimaKesytore provider
,I/SELinux ( 7678): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7678):  
I/SELinux ( 7678):  
,I/SELinux ( 7678): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7678): >>>>> Normal User
,E/dalvikvm( 7678): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7678): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7678): in addTimaSignatureService
,D/CaptivePortalTracker( 2409): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2409): Checking http://216.58.209.174/generate_204
,D/TimaKeyStoreProvider( 7678): Cannot add TimaSignature Service, License check Failed
,D/ConnectivityService( 2409): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/ActivityThread( 7678): Added TimaKesytore provider
,D/dalvikvm( 7670): GC_CONCURRENT freed 2997K, 31% free 9566K/13680K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7670): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7678): GC_CONCURRENT freed 2984K, 30% free 9581K/13684K, paused 1ms+1ms, total 21ms
,D/dalvikvm( 7678): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/GservicesProvider( 7678): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7678): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7678): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7678): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7678): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7678): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7678): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7678): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7678): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7678): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7678): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7678): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7678): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7678): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7678): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7678): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7678): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7678): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7678): Shutting down VM
,W/dalvikvm( 7678): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7678): FATAL EXCEPTION: main
E/AndroidRuntime( 7678): Process: com.google.process.gapps, PID: 7678
E/AndroidRuntime( 7678): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7678): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7678): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7678): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7678): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7678): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7678): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7678): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7678): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7678): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7678): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7678): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7678): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7678): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7678): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7678): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7678): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7678): 	... 12 more
W/ActivityManager( 2409): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2409): Killing 7678:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /d,ata/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7639): Failed to find provider info for com.google.settings
E/ActivityThread( 7670): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7616): Failed to find provider info for com.google.android.gsf.gservices
,D/CaptivePortalTracker( 2409): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2409): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2409): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2409): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,I/SELinux ( 7707): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7707):  
D/ConnectivityService( 2409): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 11% free 9502K/10664K, paused 2ms+2ms, total 27ms
,I/SELinux ( 7707): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7707):  
I/SELinux ( 7707):  
,I/SELinux ( 7707): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7707): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7707): >>>>> Normal User
,E/dalvikvm( 7707): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7707): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 3ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7707): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7707): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7707): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10664K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 7707): GC_CONCURRENT freed 2998K, 31% free 9571K/13688K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7707): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7707): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7707): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7707): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7707): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7707): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7707): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7707): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7707): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7707): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7707): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7707): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7707): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7707): Shutting down VM
,W/dalvikvm( 7707): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 7707): Sending signal. PID: 7707 SIG: 9
E/AndroidRuntime( 7707): FATAL EXCEPTION: main
E/AndroidRuntime( 7707): Process: com.google.process.gapps, PID: 7707
E/AndroidRuntime( 7707): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7707): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7707): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7707): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7707): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7707): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7707): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7707): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7707): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7707): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7707): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7707): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7707): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7707): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7707): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7707): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7707): 	... 12 more
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.process.gapps (pid 7707) (adj 0) has died.,
,I/SELinux ( 7722): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7722):  
,I/SELinux ( 7722): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7722):  
I/SELinux ( 7722):  
,I/SELinux ( 7722): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7722): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7722): >>>>> Normal User
,E/dalvikvm( 7722): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7722): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7722): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7722): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7722): Added TimaKesytore provider
,D/dalvikvm( 7722): GC_CONCURRENT freed 2990K, 31% free 9578K/13684K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7722): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7722): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7722): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7722): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7722): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7722): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7722): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7722): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7722): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7722): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7722): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7722): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7722): Shutting down VM
,W/dalvikvm( 7722): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7722): FATAL EXCEPTION: main
E/AndroidRuntime( 7722): Process: com.google.process.gapps, PID: 7722
E/AndroidRuntime( 7722): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7722): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7722): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7722): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7722): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7722): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7722): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7722): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7722): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7722): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7722): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7722): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7722): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7722): 	... 12 more
W/ActivityManager( 2409): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2409): Killing 7722:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7616): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7670): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7616): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7616): VFY: unable to resolve instance field 36
D/dalvikvm( 7616): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7616): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7616): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 7616): VFY: replacing opcode 0x62 at 0x0047
,E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
D/dalvikvm( 7616): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7616): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7616): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42262438
,I/ActivityManager( 2409): Killing 5748:com.android.mms/u0a49 (adj 15): empty #43
D/dalvikvm( 7616): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42262438
D/dalvikvm( 7616): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42262438, skipping init
D/dalvikvm( 7616): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42262438
D/dalvikvm( 7616): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42262438
V/JNIHelp ( 7616): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CountryDetector( 2409): No listener is left
,D/dalvikvm( 7616): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42262438
D/dalvikvm( 7616): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42262438
D/dalvikvm( 7616): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42262438
,D/dalvikvm( 7616): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42262438
,I/ProviderInstaller( 7616): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7737):  
,I/SELinux ( 7737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7737):  
I/SELinux ( 7737):  
,I/SELinux ( 7737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7737): >>>>> Normal User
,E/dalvikvm( 7737): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7737): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7737): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7737): Added TimaKesytore provider
,D/dalvikvm( 7737): GC_CONCURRENT freed 2987K, 30% free 9585K/13688K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7737): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7737): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7737): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7737): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7737): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7737): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7737): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7737): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7737): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7737): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7737): Shutting down VM
,W/dalvikvm( 7737): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7737): FATAL EXCEPTION: main
E/AndroidRuntime( 7737): Process: com.google.process.gapps, PID: 7737
E/AndroidRuntime( 7737): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7737): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7737): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7737): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7737): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7737): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7737): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7737): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7737): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7737): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7737): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7737): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7737): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7737): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7737): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7737): 	... 12 more
,I/Process ( 7737): Sending signal. PID: 7737 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.process.gapps (pid 7737) (adj 0) has died.
,I/SELinux ( 7752): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7752):  
,I/SELinux ( 7752): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7752):  
I/SELinux ( 7752):  
,I/SELinux ( 7752): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7752): >>>>> Normal User
,E/dalvikvm( 7752): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7752): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7752): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7752): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7752): Added TimaKesytore provider
,D/dalvikvm( 7752): GC_CONCURRENT freed 2998K, 31% free 9571K/13688K, paused 1ms+2ms, total 17ms
,D/dalvikvm( 7752): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7752): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7752): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7752): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7752): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7752): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7752): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7752): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7752): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7752): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7752): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7752): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7752): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7752): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7752): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7752): Shutting down VM
,W/dalvikvm( 7752): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7752): FATAL EXCEPTION: main
E/AndroidRuntime( 7752): Process: com.google.process.gapps, PID: 7752
E/AndroidRuntime( 7752): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7752): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7752): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7752): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7752): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7752): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7752): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7752): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7752): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7752): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7752): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7752): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7752): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7752): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7752): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7752): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7752): 	... 12 more
W/ActivityManager( 2409): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2409): Killing 7752:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7616): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,W/NativeLibraryUtils( 7616): Failed to open lock file
W/NativeLibraryUtils( 7616): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7616): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7616): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7616): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7616): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7616): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7616): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7616): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7616): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7616): 	... 3 more
W/ContextImpl( 2409): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/dalvikvm( 7616): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7616): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7616): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7771): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7771):  
,I/SELinux ( 7771): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7771):  
I/SELinux ( 7771):  
,I/SELinux ( 7771): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7771): >>>>> Normal User
,E/dalvikvm( 7771): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7771): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7771): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7771): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7771): Added TimaKesytore provider
,D/dalvikvm( 7771): GC_CONCURRENT freed 2995K, 31% free 9571K/13684K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7771): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7771): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7771): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7771): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7771): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7771): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7771): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7771): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7771): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7771): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7771): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7771): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7771): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7771): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7771): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7771): Shutting down VM
,W/dalvikvm( 7771): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7771): FATAL EXCEPTION: main
E/AndroidRuntime( 7771): Process: com.google.process.gapps, PID: 7771
E/AndroidRuntime( 7771): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7771): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7771): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7771): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7771): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7771): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7771): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7771): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7771): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7771): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7771): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7771): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7771): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7771): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7771): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7771): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7771): 	... 12 more
,I/Process ( 7771): Sending signal. PID: 7771 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.process.gapps (pid 7771) (adj 0) has died.
,I/SELinux ( 7786): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7786):  
,I/SELinux ( 7786): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7786):  
I/SELinux ( 7786):  
,I/SELinux ( 7786): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7786): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7786): >>>>> Normal User
,E/dalvikvm( 7786): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7786): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7786): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7786): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7786): Added TimaKesytore provider
,D/PreloadUpdateManagerStateMachine( 6010): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6010): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6010): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6010): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6010): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 6010): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6010): entry::IDLE
,D/dalvikvm( 7786): GC_FOR_ALLOC freed 3006K, 31% free 9564K/13688K, paused 18ms, total 18ms
,D/dalvikvm( 7786): GC_CONCURRENT freed 230K, 31% free 9576K/13688K, paused 1ms+2ms, total 15ms
,I/GservicesProvider( 7786): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7786): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7786): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7786): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7786): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7786): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7786): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7786): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7786): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7786): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7786): Shutting down VM
,W/dalvikvm( 7786): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7786): FATAL EXCEPTION: main
E/AndroidRuntime( 7786): Process: com.google.process.gapps, PID: 7786
E/AndroidRuntime( 7786): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7786): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7786): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7786): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7786): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7786): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7786): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7786): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7786): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7786): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7786): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7786): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7786): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7786): 	... 12 more
W/ActivityManager( 2409): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2409): Killing 7786:com.google.process.gapps/u0a12 (adj 0): crash
,I/GAv4-SVC( 7616): Google Analytics 8.4.89 is starting up.
W/ActivityManager( 2409): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
E/ActivityThread( 7616): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7801): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7801):  
,I/SELinux ( 7801): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7801):  
I/SELinux ( 7801):  
,I/SELinux ( 7801): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7801): >>>>> Normal User
,E/dalvikvm( 7801): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7801): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7801): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7801): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7801): Added TimaKesytore provider
,D/dalvikvm( 7801): GC_CONCURRENT freed 2986K, 31% free 9578K/13684K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7801): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7801): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7801): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7801): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7801): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7801): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7801): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7801): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7801): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7801): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7801): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7801): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7801): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7801): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7801): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7801): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7801): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7801): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7801): Shutting down VM
,W/dalvikvm( 7801): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7801): FATAL EXCEPTION: main
E/AndroidRuntime( 7801): Process: com.google.process.gapps, PID: 7801
E/AndroidRuntime( 7801): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7801): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7801): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7801): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7801): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7801): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7801): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7801): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7801): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7801): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7801): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7801): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7801): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7801): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7801): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7801): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7801): 	... 12 more
,I/Process ( 7801): Sending signal. PID: 7801 SIG: 9
E/DropBoxManagerService( 2409): Can't write: system_app_crash
E/DropBoxManagerService( 2409): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2409): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2409): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2409): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2409): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2409): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2409): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2409): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2409): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2409): 	... 5 more
,I/ActivityManager( 2409): Process com.google.process.gapps (pid 7801) (adj 0) has died.
,I/SELinux ( 7816): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7816):  
,I/SELinux ( 7816): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7816):  
I/SELinux ( 7816):  
,I/SELinux ( 7816): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7816): >>>>> Normal User
,E/dalvikvm( 7816): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7816): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7816): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7816): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7816): Added TimaKesytore provider
,D/dalvikvm( 7816): GC_CONCURRENT freed 2990K, 31% free 9578K/13684K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7816): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7816): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7816): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7816): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7816): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7816): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7816): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7816): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7816): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7816): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7816): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7816): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7816): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7816): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7816): Shutting down VM

```
