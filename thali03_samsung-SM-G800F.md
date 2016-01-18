#### Test 5615109370bee58_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7197): 
D/AndroidRuntime( 7197): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7197): CheckJNI is OFF
D/AndroidRuntime( 7197): setted country_code = Poland
D/AndroidRuntime( 7197): setted countryiso_code = PL
D/AndroidRuntime( 7197): setted sales_code = PLS
D/AndroidRuntime( 7197): readGMSProperty: start
D/AndroidRuntime( 7197): readGMSProperty: already setted!!
D/AndroidRuntime( 7197): readGMSProperty: end
D/AndroidRuntime( 7197): addProductProperty: start
D/dalvikvm( 7197): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7197): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7197): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7197): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7197): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7197): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7197): failed to load memtrack module: -2
D/dalvikvm( 7197): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7197): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SELinux ( 7224): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7224):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7197): Shutting down VM
D/dalvikvm( 7197): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7224): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7224):  
I/SELinux ( 7224):  
I/SELinux ( 7224): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7224): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7224): >>>>> Normal User
E/dalvikvm( 7224): >>>>> com.test.thalitest [ userId:0 | appId:10634 ]
E/SELinux ( 7224): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7224): in addTimaSignatureService
D/TimaKeyStoreProvider( 7224): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7224): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4170): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4170): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7224): GC_FOR_ALLOC freed 3017K, 31% free 9550K/13752K, paused 17ms, total 17ms
D/dalvikvm( 7224): GC_CONCURRENT freed 219K, 31% free 9566K/13752K, paused 2ms+17ms, total 29ms
V/WebViewChromium( 7224): Binding Chromium to the background looper Looper (main, tid 1) {428d1280}
I/chromium( 7224): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7224): Initializing chromium process, renderers=0
,W/chromium( 7224): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7224): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7224): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7224): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7224): Mali API Version : 401
,I/Mali    ( 7224): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7224): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7224): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7224): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7224): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7224): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7224): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2582): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:7224,o:f
,W/dalvikvm( 7224): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7224): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7224): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7224): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7224): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7224): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7224): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
,W/dalvikvm( 7224): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7224): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7224): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7224): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7224): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7224): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2582): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:7224,o:f
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7224): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7224): Enabling debug mode 0
,W/AwContents( 7224): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,W/AwContents( 7224): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
W/IInputConnectionWrapper( 7224): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7224): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7224): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428cda28
,D/dalvikvm( 7224): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x428cda28
D/jxcore_app_log( 7224): JniHelper::setJavaVM(0x41e4d220), pthread_self() = 2028057608
,D/JX-Cordova( 7224): jxcore cordova android initializing
,D/dalvikvm( 7224): GC_CONCURRENT freed 1440K, 18% free 12221K/14840K, paused 1ms+2ms, total 26ms
,D/dalvikvm( 7224): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7224): GC_FOR_ALLOC freed 3926K, 25% free 15983K/21108K, paused 41ms, total 41ms
,D/dalvikvm( 7224): GC_FOR_ALLOC freed 6047K, 31% free 17301K/24772K, paused 45ms, total 45ms
,I/dalvikvm-heap( 7224): Grow heap (frag case) to 20.390MB for 2459024-byte allocation
D/AmoledAdjustTimer( 2422): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,D/dalvikvm( 7224): GC_FOR_ALLOC freed 1624K, 34% free 18078K/27176K, paused 35ms, total 35ms
,D/dalvikvm( 7224): GC_CONCURRENT freed 6799K, 30% free 19438K/27448K, paused 2ms+10ms, total 60ms
,D/dalvikvm( 7224): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/dalvikvm( 7224): GC_FOR_ALLOC freed 1038K, 31% free 19197K/27448K, paused 55ms, total 55ms
,I/dalvikvm-heap( 7224): Grow heap (frag case) to 22.805MB for 3049822-byte allocation
,D/dalvikvm( 7224): GC_FOR_ALLOC freed 5657K, 46% free 16518K/30428K, paused 47ms, total 47ms
,W/jxcore-log( 7224): Initializing JXcore engine
,W/jxcore-log( 7224): JXcore engine is ready
,W/jxcore-log( 7224): Starting JXcore engine
,W/jxcore-log( 7224): Platform android
W/jxcore-log( 7224): 
,W/jxcore-log( 7224): Process ARCH arm
W/jxcore-log( 7224): 
,I/jxcore-log( 7224): JXcore Cordova bridge is ready!
I/jxcore-log( 7224): 
,W/jxcore-log( 7224): JXcore engine is started
,I/chromium( 7224): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7224): Toggling radios to true
I/jxcore-log( 7224): 
,D/BluetoothAdapter( 7224): enable(): BT is already enabled..!
,I/WifiManager( 7224): packageName : com.test.thalitest
,I/WifiManager( 7224): setWifiEnabled : true
,I/WifiService( 2422): setWifiEnabled: true pid=7224, uid=10634
,W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=7224, uid=10634 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7224, uid=10634 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2422): disconnect: pid=7224, uid=10634
I/jxcore-log( 7224): Radios toggled
I/jxcore-log( 7224): 
I/jxcore-log( 7224): My device name is: samsung-SM-G800F
I/jxcore-log( 7224): 
I/wpa_supplicant( 3967): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3967): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3967): First Scan Start
W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3967): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/CommandListener( 1915): Clearing all IP addresses on wlan0,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): Skip scan - already scanning,
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling,
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/STATUSBAR-IconMerger( 2582): checkOverflow(336), More:false, Req:false Child:3,
,I/SELinux ( 7271): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7271):  
D/ConnectivityService( 2422): Attempting to switch to mobile
D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
D/CommandListener( 1915): Clearing all IP addresses on wlan0
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-46ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-45ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1,
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7271): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7271):  
I/SELinux ( 7271):  
I/SELinux ( 7271): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,E/SELinux ( 7271): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7271): >>>>> Normal User,
E/dalvikvm( 7271): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,E/SELinux ( 7271): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-2ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService( 2422): route cmd failed: 
W/NetworkManagementService( 2422): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7271): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7271): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7271): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2422): android_net_utils_resetConnections in env=0x77ce5b38 clazz=0x62300001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
,D/dalvikvm( 7271): GC_CONCURRENT freed 2990K, 31% free 9578K/13752K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7271): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,V/NativeCrypto( 2850): Read error: ssl=0x7bbae9a0: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7bbae9a0: I/O error during system call, Broken pipe
,E/SPPClientService( 5585): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,E/SPPClientService( 5585): [e] exceptionCaught(). NET_TIMEOUT,
,E/SPPClientService( 5585): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.,
,E/SPPClientService( 5585): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5585): [b] ResponseMap empty,
,I/System.out( 7271): Inside WakeupProvider,
,I/System.out( 7271): Inside onCreate() of WakeupTriggerProvide,
,V/NetworkStats( 2422): updateIfacesLocked(),
D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
I/VlingoApplication( 7271): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/VlingoApplication( 7271): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/VlingoApplication( 7271): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 26ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4754): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2422): Killing 6212:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7271): initQueue()
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4754): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2422): updateDataUsageMap
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6624): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6624): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6624): noConnectivity : true
,I/DBG_DM  ( 4779): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7300):  
,I/SELinux ( 7300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7300):  
I/SELinux ( 7300):  
,I/SELinux ( 7300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7300): >>>>> Normal User
,E/dalvikvm( 7300): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7300): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7300): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7300): Added TimaKesytore provider,
,I/wpa_supplicant( 3967): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 3967): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz),
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/dalvikvm( 7300): GC_CONCURRENT freed 3001K, 31% free 9566K/13748K, paused 2ms+1ms, total 21ms,
,D/dalvikvm( 7300): WAIT_FOR_CONCURRENT_GC blocked 19ms,
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true,
,D/Tethering( 2422): interfaceStatusChanged wlan0, true,
I/ActivityManager( 2422): Killing 6281:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3967): Associated with C0.AA.48
,I/wpa_supplicant( 3967): freq(2412) increment count 2
,I/wpa_supplicant( 3967): meet head of list.
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030,
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030,
I/wpa_supplicant( 3967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=],
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/WifiNative( 2422): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7315): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7315):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9501K/10728K, paused 4ms+4ms, total 43ms
,I/SELinux ( 7315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7315):  
I/SELinux ( 7315):  
,I/SELinux ( 7315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7315): >>>>> Normal User
,E/dalvikvm( 7315): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 3ms+4ms, total 40ms
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/TimaKeyStoreProvider( 7315): in addTimaSignatureService
D/TimaKeyStoreProvider( 7315): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7315): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 4ms+4ms, total 40ms
,D/dalvikvm( 7315): GC_CONCURRENT freed 2998K, 31% free 9571K/13748K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7315): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/ActivityManager( 2422): Killing 6326:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7332):  
,I/dhcpcd  ( 7327): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7327): bssid match
,I/SELinux ( 7332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7332):  
I/SELinux ( 7332):  
,I/SELinux ( 7332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7332): >>>>> Normal User
,E/dalvikvm( 7332): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7332): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7332): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7332): Added TimaKesytore provider
,D/dalvikvm( 7332): GC_CONCURRENT freed 3014K, 31% free 9557K/13752K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7332): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/KLMS-2.3.201 : ( 7332): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7332): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453126796392
,I/KLMS-2.3.201 : ( 7332): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2422): Killing 6370:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7346): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7346):  
,I/SELinux ( 7346): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7346):  
I/SELinux ( 7346):  
,I/SELinux ( 7346): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7346): >>>>> Normal User
,E/dalvikvm( 7346): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7346): in addTimaSignatureService
D/TimaKeyStoreProvider( 7346): Cannot add TimaSignature Service, License check Failed
D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
D/ActivityThread( 7346): Added TimaKesytore provider
,D/dalvikvm( 7346): GC_CONCURRENT freed 2993K, 31% free 9564K/13744K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7346): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5848): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5848): [BDLM] already registered in spp
I/SA      ( 5848): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5848): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5848): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5848): [OR] == isSIMCardReady false ==
I/SA      ( 5848): [SCU] == networkStateCheck == false
,I/SA      ( 5848): [OR] onReceive END
I/ActivityManager( 2422): Killing 6425:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7358): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7358):  
,I/SELinux ( 7358): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7358):  
I/SELinux ( 7358):  
,I/SELinux ( 7358): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7358): >>>>> Normal User
,E/dalvikvm( 7358): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7358): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7358): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7358): Added TimaKesytore provider
,D/dalvikvm( 7358): GC_CONCURRENT freed 2997K, 31% free 9569K/13748K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7358): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/sCloudBackupApp( 7358): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7358): Other Intent
I/ActivityManager( 2422): Killing 5633:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7371): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7371):  
,I/SELinux ( 7371): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7371):  
I/SELinux ( 7371):  
,I/SELinux ( 7371): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7371): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7371): >>>>> Normal User
,E/dalvikvm( 7371): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7371): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7371): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7371): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7371): Added TimaKesytore provider
,D/dalvikvm( 7371): GC_CONCURRENT freed 3001K, 31% free 9562K/13748K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7371): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5383): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5383): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7371): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5383): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2422): Killing 6318:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5911): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5911): getCountryCode(): countryCode = PL
,D/Headlines( 5911): Breath.onCreate
,D/Headlines( 5911): Breath timer started. interval : 30000
,I/SELinux ( 7383): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7383):  
,D/Headlines( 5911): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5911): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5911): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5911): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2422): waitForAlarm result :8
,I/SELinux ( 7383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7383):  
I/SELinux ( 7383):  
,I/SELinux ( 7383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7383): >>>>> Normal User
,E/dalvikvm( 7383): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7383): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7383): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7383): Added TimaKesytore provider
,D/dalvikvm( 7383): GC_CONCURRENT freed 2998K, 31% free 9570K/13752K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7383): WAIT_FOR_CONCURRENT_GC blocked 12ms
,V/WebViewChromium( 7383): Binding Chromium to the background looper Looper (main, tid 1) {428cdf90}
,I/chromium( 7383): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7383): Initializing chromium process, renderers=0
,W/chromium( 7383): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7383): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7383): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 7383): loaded /system/lib/egl/libGLESv2_mali.so,
,I/Mali    ( 7383): Mali API Version : 401,
,I/Mali    ( 7383): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,W/GAV2    ( 7383): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7383): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache,
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7383): Starting up...,
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2422): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.Environment( 5979): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.SyncManager( 5979): SYNC; picasa accounts
,D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2422): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/QuickConnect[1.1][2] ( 5185): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/iu.UploadsManager( 5979): num queued entries: 0
I/iu.UploadsManager( 5979): num updated entries: 0
I/QuickConnect[1.1][2] ( 5185): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/iu.SyncManager( 5979): NEXT; no task
V/QuickConnect[1.1][2] ( 5185): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@428dc398
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2582): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2582): refreshSignalCluster: data=-1 bt=false
,I/SELinux ( 7443): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7443):  
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1915): RTNETLINK answers: No such file or directory,
V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,I/SELinux ( 7443): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7443):  
I/SELinux ( 7443):  
,I/SELinux ( 7443): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7443): >>>>> Normal User
,E/dalvikvm( 7443): >>>>> com.android.email [ userId:0 | appId:10157 ],
,E/SELinux ( 7443): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
,D/TimaKeyStoreProvider( 7443): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7443): Cannot add TimaSignature Service, License check Failed,
V/RouteController( 1915): RTNETLINK answers: No such process
,D/ActivityThread( 7443): Added TimaKesytore provider,
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2422): updateIfacesLocked(),
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,V/NetworkStats( 2422): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
V/NetworkStats( 2422): performPollLocked() took 22ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,D/dalvikvm( 7443): GC_CONCURRENT freed 2984K, 31% free 9580K/13744K, paused 4ms+2ms, total 29ms,
,D/dalvikvm( 7443): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId,
,I/SELinux ( 7477): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7477):  
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/ActivityManager( 2422): Killing 6385:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7477): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7477):  
I/SELinux ( 7477):  
,I/SELinux ( 7477): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7477): >>>>> Normal User
,E/dalvikvm( 7477): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7477): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7477): in addTimaSignatureService
,I/SELinux ( 7490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7490):  
,D/TimaKeyStoreProvider( 7477): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7477): Added TimaKesytore provider
,I/ActivityManager( 2422): Killing 6025:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7490):  
I/SELinux ( 7490):  
,I/SELinux ( 7490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,E/dalvikvm( 7490): >>>>> Normal User
,E/dalvikvm( 7490): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7490): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7490): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7490): Added TimaKesytore provider
D/dalvikvm( 7477): GC_CONCURRENT freed 3006K, 31% free 9564K/13752K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7477): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2582): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2582): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2582): updateDataNetType()
D/STATUSBAR-NetworkController( 2582): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4779): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/BadgeProvider( 7477): onCreate
,D/BadgeProvider( 7477): DatabaseHelper
,D/BadgeProvider( 7477): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,D/BadgeProvider( 7477): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7477): sendNotify, [notify] : null
D/BadgeProvider( 7477): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7477): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7477): update, [UpdateCount] : 1
,D/Launcher.Model( 2767): reloadBadges entered.
,D/dalvikvm( 7490): GC_CONCURRENT freed 2992K, 31% free 9575K/13748K, paused 4ms+2ms, total 37ms
,D/dalvikvm( 7490): WAIT_FOR_CONCURRENT_GC blocked 31ms
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4383, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2582): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2582):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2582): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
,D/hcjo    ( 6000): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6000): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6000): exit::IDLE
,D/InitializeManagerStateMachine( 6000): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6000): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6000): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6000): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6000): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 6000): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6000): entry::SUCCESS
,D/hcjo    ( 6000): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6000): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6000): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6000): exit::SUCCESS
,D/InitializeManagerStateMachine( 6000): entry::IDLE
,E/SPPClientService( 5585): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5585): [SystemStateMoniter] Current Time : 277097
,E/SPPClientService( 5585): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5585): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,D/Headlines( 5911): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5911): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5911): Breath 1605 latestRequest time : 1453126797234 current time : 1453126798839
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5585): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5585): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4754): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4754): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4754): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,E/SPPClientService( 5585): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2422): Killing 6357:com.android.providers.calendar/u0a45 (adj 15): empty #43
,E/SPPClientService( 5585): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19,
,D/NearbySettings( 4754): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 4754): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast,
I/PCWCLIENTTRACE_PushUtil( 6624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6624): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6624): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422,
,D/dalvikvm( 2422): GC_EXPLICIT freed 4121K, 74% free 25392K/97536K, paused 11ms+23ms, total 262ms,
,E/SPPClientService( 5585): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false,
,E/SPPClientService( 5585): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5585): [g] getNetMCC return empty string,
,I/KLMS-2.3.201 : ( 7332): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,I/KLMS-2.3.201 : ( 7332): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453126799553,
,I/KLMS-2.3.201 : ( 7332): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,I/LocationTagReadyService( 3466): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true,
D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3466): [Slink platform] The state of Slink geocode service is true,
,I/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3594): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7515): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7515):  
,I/SELinux ( 7515): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7515):  
I/SELinux ( 7515):  
,I/SELinux ( 7515): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7515): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7515): >>>>> Normal User
,E/dalvikvm( 7515): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
E/SELinux ( 7515): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7515): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7515): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7515): Added TimaKesytore provider
,D/dalvikvm( 7515): GC_CONCURRENT freed 2989K, 31% free 9578K/13752K, paused 4ms+2ms, total 22ms
,D/dalvikvm( 7515): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/SA      ( 5848): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5848): [BDLM] already registered in spp
,I/SA      ( 5848): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5848): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5848): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5848): [OR] == isSIMCardReady false ==
I/SA      ( 5848): [SCU] == networkStateCheck == true
,I/SA      ( 5848): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5848): isChinaCountryCode : false
,I/SA      ( 5848): [OR] == networkStateCheck true ==
,I/SA      ( 5848): [OR] GetMyCountryZoneTask
,I/SA      ( 5848): [OR] onReceive END
,I/SA      ( 5848): [SRS] prepareGetMyCountryZone
,I/SA      ( 5848): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5848): [SSP] query invoked
,I/SA      ( 5848): [TPMU] GetMccFromDB : null
,I/SA      ( 5848): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5848): [TPM] isNoProxy(default) : true
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SA      ( 5848): [RC New] Execute method=[GET] start
,I/System.out( 7315): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SELinux ( 7532): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7532):  
,I/SCloudBackupReceiver( 7358): Other Intent
,I/System.out( 7315): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7315): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2582): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2582): handleTimeUpdate
D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/SELinux ( 7532): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7532):  
I/SELinux ( 7532):  
I/SELinux ( 7532): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7532): >>>>> Normal User
E/dalvikvm( 7532): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
E/SELinux ( 7532): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/Headlines( 5911): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
D/HeadlinesChannelUtil( 5911): getCountryCode(): countryCode = PL
D/STATUSBAR-IconMerger( 2582): checkOverflow(288), More:false, Req:false Child:3
D/Headlines( 5911): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/TimaKeyStoreProvider( 7532): in addTimaSignatureService
D/TimaKeyStoreProvider( 7532): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7532): Added TimaKesytore provider
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5911): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5911): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5911): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5911): requestUpdateNewsWelcomeCard !!! no welcome card
I/iu.Environment( 5979): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 5979): num queued entries: 0
I/iu.UploadsManager( 5979): num updated entries: 0
I/iu.SyncManager( 5979): NEXT; no task
D/QuickConnect[1.1][2] ( 5185): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5185): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5185): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@428dc398
D/RCPManagerService( 2422): exchangeData() failure , invalid userId
D/RCPManagerService( 2422): exchangeData() failure , invalid userId
D/dalvikvm( 7532): GC_CONCURRENT freed 2999K, 31% free 9572K/13752K, paused 4ms+1ms, total 25ms
D/dalvikvm( 7532): WAIT_FOR_CONCURRENT_GC blocked 22ms
D/hcjo    ( 6000): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6000): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6000): exit::IDLE
D/InitializeManagerStateMachine( 6000): entry::NETWORK_CHECK
V/KVNProvider( 7532): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
D/InitializeManagerStateMachine( 6000): execute::NETWORK_CHECK:NETWORK_STATE_OK
V/KVNProvider( 7532): getFindoCursor query string : 
D/InitializeManagerStateMachine( 6000): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6000): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6000): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6000): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6000): entry::SUCCESS
D/hcjo    ( 6000): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 6000): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 6000): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6000): exit::SUCCESS
D/InitializeManagerStateMachine( 6000): entry::IDLE
V/KVNProvider( 7532): getTagSearchCursor() tagSearchCursor count : 0
E/SPPClientService( 5585): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5585): [SystemStateMoniter] Current Time : 278584
E/SPPClientService( 5585): [SystemStateMoniter] No Connect : false
I/System.out( 7315): AsyncTask #1 calls detatch()
W/System.err( 7315): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7315): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7315): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7315): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7315): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7315): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7315): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7315): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7315): Caused by: java.lang.NullPointerException
W/System.err( 7315): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7315): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7315): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7315): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 7315): 	... 8 more
I/ActivityManager( 2422): Killing 6199:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
D/dalvikvm( 5585): GC_CONCURRENT freed 1985K, 24% free 10439K/13732K, paused 3ms+4ms, total 38ms
I/SA      ( 5848): [RC New] [v2liruge] api execute + 686
I/SA      ( 5848): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
I/System.out( 5848): AsyncTask #2 calls detatch()
I/SA      ( 5848): [TPMU] getNetworkMcc : 
I/SA      ( 5848): [SCU] saveMccToPreferece Start
I/SA      ( 5848): [SCU] RegionMCC : 260
I/SA      ( 5848): [SSP] query invoked
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
I/SA      ( 5848): [TPMU] GetMccFromDB : null
I/SA      ( 5848): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5848): [SCU] saveMccToPreferece End
I/SA      ( 5848): [RC New] executeRequest [v2liruge] end. 702
I/SA      ( 5848): [RC New] Execute end
I/SA      ( 5848): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5848): [OR] GetMyCountryZoneTask Success
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 340, Delta = 10
,E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7224): 
,E/SPPClientService( 5585): [b] __InitReply__
,D/AmoledAdjustTimer( 2422): prevTemp = 303, currTemp = 303, prevStep = 4, currStep = 4
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7224): 
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2422): Killing 6234:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 280773
D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3449)
,I/GAV2    ( 7383): Thread[GAThread,5,main]: No campaign data found.
,W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
,I/jxcore-log( 7224): Test app app.js loaded
I/jxcore-log( 7224): 
,I/Choreographer( 7224): Skipped 527 frames!  The application may be doing too much work on its main thread.
,I/dalvikvm( 7224): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7224): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7224): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7224): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7224): BLE advertisement is supported
I/jxcore-log( 7224): 
,I/chromium( 7224): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7224): --= Surplus to requirements =--
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ****TEST TOOK:  ms ****
I/jxcore-log( 7224): 
,I/jxcore-log( 7224): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7224): 
,D/AndroidRuntime( 7558): 
D/AndroidRuntime( 7558): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7558): CheckJNI is OFF
,D/AndroidRuntime( 7558): setted country_code = Poland
,D/AndroidRuntime( 7558): setted countryiso_code = PL
D/AndroidRuntime( 7558): setted sales_code = PLS
D/AndroidRuntime( 7558): readGMSProperty: start
,D/AndroidRuntime( 7558): readGMSProperty: already setted!!
D/AndroidRuntime( 7558): readGMSProperty: end
,D/AndroidRuntime( 7558): addProductProperty: start
,D/dalvikvm( 7558): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7558): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7558): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7558): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7558): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6624): mConnectivityHandler : connected
,E/memtrack( 7558): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7558): failed to load memtrack module: -2
,W/PCWCLIENTTRACE_AccountUtil( 6624): [hasSamungAccount] - No Samsung Account
,D/dalvikvm( 7558): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
E/PCWCLIENTTRACE_SecurePreferencesJNI( 6624): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6624): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6624): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6624): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6624): [ensureRegistration] - No Samsung account
,D/AndroidRuntime( 7558): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2422): START PACKAGE DELETE: observer{1125462256}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
,D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2422): !@killApplicatoin: 10634, uninstall pkg
,I/ActivityManager( 2422): Killing 7224:com.test.thalitest/u0a634 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/WindowState( 2422): WIN DEATH: Window{435ede10 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2422): Skipping PackageSetting{42f00730 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2422): setPackageStoppedState - Execution time: 123 ms
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10634, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6786): GC_EXPLICIT freed 160K, 29% free 9957K/13964K, paused 7ms+4ms, total 51ms
,D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10634, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/DBG_DM  ( 4779): [3.19.140541][Line:408][onResume] 
,I/FPMS_FingerprintManagerService( 2602): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2963): mOCRHelper is null
,I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
,D/QuickConnect[1.1][2] ( 5185): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/DBG_DM  ( 4779): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,D/dalvikvm( 2959): GC_EXPLICIT freed 1465K, 28% free 10033K/13748K, paused 7ms+6ms, total 93ms
,I/SELinux ( 7570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7570):  
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4779): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 12% free 9501K/10728K, paused 2ms+3ms, total 31ms
,I/DBG_DM  ( 4779): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4779): [3.19.140541][Line:418][onResume] Postpone Count : 30
I/SELinux ( 7570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7570):  
I/SELinux ( 7570):  
,I/SELinux ( 7570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 2ms+3ms, total 26ms
,E/dalvikvm( 7570): >>>>> Normal User
,E/dalvikvm( 7570): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
,I/DBG_DM  ( 4779): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 4ms+6ms, total 32ms
,I/DBG_DM  ( 4779): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/RegisteredServicesCache( 2756): empty dynamic service
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,D/TimaKeyStoreProvider( 7570): in addTimaSignatureService
,D/dalvikvm( 3310): GC_EXPLICIT freed 2211K, 22% free 12426K/15820K, paused 8ms+78ms, total 275ms
,D/TimaKeyStoreProvider( 7570): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7570): Added TimaKesytore provider
,I/DBG_DM  ( 4779): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 6465): GC_EXPLICIT freed 2480K, 29% free 9883K/13748K, paused 8ms+77ms, total 299ms
,D/dalvikvm( 2422): GC_EXPLICIT freed 2543K, 75% free 24975K/97536K, paused 10ms+23ms, total 293ms
,D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 245ms
,I/DBG_DM  ( 4779): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4779): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4779): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4779): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4779): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4779): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4779): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
D/Activity( 4779): setTransGradationMode to true
,D/PhoneStatusBar( 2582): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/StatusBarManagerService( 2422): semi p:4779,o:t
I/DBG_DM  ( 4779): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2422): PackageReceiver onReceive()
,I/HarmonyEASService( 2422): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 7224 uid 10634
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 2756): GC_CONCURRENT freed 1210K, 28% free 10672K/14644K, paused 18ms+3ms, total 96ms
,D/dalvikvm( 2756): WAIT_FOR_CONCURRENT_GC blocked 58ms
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/EnterpriseDeviceManagerService( 2422): Package has changed for user 0
,D/dalvikvm( 7570): GC_CONCURRENT freed 3004K, 31% free 9564K/13752K, paused 4ms+1ms, total 56ms
,D/dalvikvm( 7570): WAIT_FOR_CONCURRENT_GC blocked 49ms
,D/elm:14132( 7570): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7570): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7570): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7570): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7570): ElmAgentService : onCreate()
D/elm:14132( 7570): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7570): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7570): MDMBridge.getInstance()
,D/elm:14132( 7570): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7570): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7585): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7585):  
,D/elm:14132( 7570): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,I/SELinux ( 7585): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7585):  
I/SELinux ( 7585):  
,I/SELinux ( 7585): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7585): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7585): >>>>> Normal User
,E/dalvikvm( 7585): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7585): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7570): ElmAgentService : onDestroy().
I/ActivityManager( 2422): Killing 6568:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7585): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7585): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7585): Added TimaKesytore provider
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2422): GC_EXPLICIT freed 943K, 75% free 25026K/97536K, paused 13ms+30ms, total 437ms
,D/PackageManager( 2422): delete sourFile : 
,D/BackupManagerService( 2422): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2422): removePackageParticipantsLocked: uid=10634 #1
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 2422): delete native library directory: 
D/PackageManager( 2422): return delete result to caller: 1125462256
,D/AndroidRuntime( 7558): Shutting down VM
D/PackageManager( 2422): returnCode: 1
,D/dalvikvm( 7558): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 5ms
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
D/dalvikvm( 7585): GC_CONCURRENT freed 2990K, 31% free 9577K/13748K, paused 5ms+1ms, total 45ms
,D/dalvikvm( 7585): WAIT_FOR_CONCURRENT_GC blocked 40ms
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Scheme: "mms"
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7600): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7600):  
,I/ActivityManager( 2422): Killing 6485:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7600): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7600):  
I/SELinux ( 7600):  
,I/SELinux ( 7600): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7600): >>>>> Normal User
,E/dalvikvm( 7600): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7600): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7600): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7600): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7600): Added TimaKesytore provider
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/dalvikvm( 7600): GC_CONCURRENT freed 3001K, 31% free 9570K/13752K, paused 2ms+2ms, total 18ms
D/dalvikvm( 7600): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2422): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2422): clearDefaults: com.test.thalitest
,I/PCWCLIENTTRACE_PushUtil( 6624): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6624): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6624): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6624): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/ApplicationsProvider( 2959): Could not fetch usage stats
W/ApplicationsProvider( 2959): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2959): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2959): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2959): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2959): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2959): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2959): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2959): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2959): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2959): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SA      ( 5848): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5848): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,E/SQLiteLog( 6044): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6044): threadid=12: thread exiting with uncaught exception (group=0x41e60c08)
,E/AndroidRuntime( 6044): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6044): Process: com.sec.android.app.shealth, PID: 6044
E/AndroidRuntime( 6044): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6044): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6044): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6044): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6044): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6044): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6044): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6044): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6044): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6044): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6044): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6044): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6044): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6044): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6044): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6044): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SharedPreferencesImpl( 3594): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,I/Process ( 6044): Sending signal. PID: 6044 SIG: 9
,I/Icing.InternalIcingCorporaProvider( 6465): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
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
E/SQLiteLog( 6465): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 6465): threadid=10: thread exiting with uncaught exception (group=0x41e60c08)
,I/SELinux ( 7622): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7622):  
I/ActivityManager( 2422): Process com.sec.android.app.shealth (pid 6044) (adj 5) has died.
,E/AndroidRuntime( 6465): FATAL EXCEPTION: IntentService[UpdateCorporaService],
E/AndroidRuntime( 6465): Process: com.google.android.googlequicksearchbox:search, PID: 6465
E/AndroidRuntime( 6465): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323),
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6465): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
,E/AndroidRuntime( 6465): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6465): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6465): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6465): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6465): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6465): ,	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6465): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6465): Sending signal. PID: 6465 SIG: 9,
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
,E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method),
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
,I/SELinux ( 7622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7622):  
I/SELinux ( 7622):  
,I/SELinux ( 7622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,I/ActivityManager( 2422): Process com.google.android.googlequicksearchbox:search (pid 6465) (adj 5) has died.,
E/SELinux ( 7622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7622): >>>>> Normal User
E/dalvikvm( 7622): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
E/SELinux ( 7622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7622): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7622): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7622): Added TimaKesytore provider
,D/dalvikvm( 7622): GC_CONCURRENT freed 2997K, 31% free 9568K/13752K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 7622): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,D/UserAnalysis.PlaceProvider( 7622): Create SecureDbHelper,
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7622): Create SecureDbHelper,
,E/SQLiteDatabase( 7622): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
E/SQLiteDatabase( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889),
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384),
E/SQLiteDatabase( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7622): 	at java.lang.reflect.Method.invokeNative(Native Method),
E/SQLiteDatabase( 7622): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7622): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7622): Couldn't open privacy for writing (will try read-only):,
E/SQLiteOpenHelper( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7622): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322),
E/SQLiteOpenHelper( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7622): 	,at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7622): 	,at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7622): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7622): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7622): Opened privacy in read-only mode
,E/SQLiteDatabase( 7622): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.,
E/SQLiteDatabase( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232),
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7622): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
,E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7622): 	,at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7622): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7622): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,E/SQLiteDatabase( 7622): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7622): Couldn't open privacy for writing (will try read-only):,
E/SQLiteOpenHelper( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
,E/SQLiteOpenHelper( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
,E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7622): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7622): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7622): 	at java.lang.reflect.Method.invoke(Method.java:515),
E/SQLiteOpenHelper( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7622): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7622): Opened privacy in read-only mode
E/SQLiteDatabase( 7622): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
,E/SQLiteDatabase( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
,E/SQLiteDatabase( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7622): 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384),
E/SQLiteDatabase( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7622): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7622): ,	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7622): 	at dalvik.system.NativeStart.main(Native Method)
,W/System.err( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
W/System.err( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7622): ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,W/System.err( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889),
W/System.err( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7622): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,W/System.err( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,W/System.err( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7622): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7622): 	,at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7622): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7622): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7622): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7622): 	at android.os.Looper.loop(Looper.java:146)
,W/System.err( 7622): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7622): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7622): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 7622): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7622): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7622): ,	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6398): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6479):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2422):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2422): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6695): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6695): The package(com.test.thalitest) removed
E/SQLiteDatabase( 6398): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6398): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6398): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6398): 	at android.data,base.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6398): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6398): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2422): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2422): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2422): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2422): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2422): 	... 8 more
W/System.err( 2422): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2422): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2422): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2422): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2422): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2422): 	... 8 more
D/MagazineService::MagazineBroadcastReceiver( 6722): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
I/MagazineService::MagazineService( 6722): [onHandleIntent] ACTION_PACKAGE_REMOVED
D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
E/SQLiteDatabase( 6722): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6722): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407),
E/SQLiteDatabase( 6722): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6722): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6722): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6722): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6722): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6722): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 6722): threadid=10: thread exiting with uncaught exception (group=0x41e60c08)
I/SELinux ( 7637): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7637):  
E/AndroidRuntime( 6722): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6722): Process: com.samsung.android.magazine.service, PID: 6722
E/AndroidRuntime( 6722): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6722): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6722): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6722): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6722): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6722): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6722): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6722): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6722): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6722): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6722): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 6722): Sending signal. PID: 6722 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
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
I/ActivityManager( 2422): Process com.samsung.android.magazine.service (pid 6722) (adj 5) has died.
I/SELinux ( 7637): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7637):  
I/SELinux ( 7637):  
I/SELinux ( 7637): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7637): >>>>> Normal User
E/dalvikvm( 7637): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
E/SELinux ( 7637): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7637): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7637): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7637): Added TimaKesytore provider
,D/dalvikvm( 7637): GC_CONCURRENT freed 3008K, 31% free 9564K/13752K, paused 1ms+1ms, total 21ms
,D/dalvikvm( 7637): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/ContextImpl( 7637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6748): onReceive intent data =  package:com.test.thalitest
,E/SQLiteDatabase( 7637): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7637): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7637): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7637): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7637): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7637): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7637): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7637): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7637): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7637): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/KidsPlatformStub( 6748): Package not found : com.sec.android.app.kidshome
,W/dalvikvm( 7637): threadid=10: thread exiting with uncaught exception (group=0x41e60c08)
,E/AndroidRuntime( 7637): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7637): Process: com.android.keychain, PID: 7637
E/AndroidRuntime( 7637): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7637): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7637): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7637): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7637): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7637): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7637): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7637): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7637): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7637): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 6786): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6786): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6786): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6786): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
,W/System.err( 6786): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6786): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6786): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 6786): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6786): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6786): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 6786): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6786): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6786): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6786): 	at dalvik.system.NativeStart.main(Native Method)
,I/Process ( 7637): Sending signal. PID: 7637 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
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
,D/PackageBroadcastService( 3310): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3310): Clearing selected account for com.test.thalitest
I/ActivityManager( 2422): Process com.android.keychain (pid 7637) (adj 5) has died.
,E/SQLiteLog( 3310): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3310): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3310): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3310): disk I/O error (code 3850)
E/DriveAsyncService( 3310): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3310): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3310): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3310): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3310): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3310): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3310): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3310): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3310): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3310): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3310): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3310): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3310): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3310): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3310): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3310): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3310): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3310): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3310): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3310): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3310): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3310): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3310): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3310): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3310): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3310): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3310): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3310): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3310): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3310): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3310): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3310): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 3310): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3310): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3310): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3310): 	at android.databas,e.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3310): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3310): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3310): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3310): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3310): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 2850): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
E/PhenotypeInitializer( 3310): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3310): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3310): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3310): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3310): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3310): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3310): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3310): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3310): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3310): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/SQLiteOpenHelper( 3310): Opened metrics.db in read-only mode
D/ChimeraCfgMgr( 3310): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3310): Module APK com.google.android.play.games already loaded
D/gH_CompatibleDatabase( 3310): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 3310): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/SQLiteLog( 3310): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/AndroidRuntime( 2850): Shutting down VM
,W/dalvikvm( 2850): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
,E/ClearPendingStateOp( 3310): Runtime exception while performing operation
E/ClearPendingStateOp( 3310): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3310): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3310): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3310): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3310): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3310): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 3310): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3310): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,W/dalvikvm( 3310): threadid=48: thread exiting with uncaught exception (group=0x41e60c08)
,F/ClearPendingStateOp( 3310): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3310): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3310): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3310): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3310): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3310): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3310): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3310): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3310): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 3310): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3310): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3310): threadid=52: thread exiting with uncaught exception (group=0x41e60c08)
,I/Process ( 3310): Sending signal. PID: 3310 SIG: 9
E/AndroidRuntime( 2850): FATAL EXCEPTION: main
E/AndroidRuntime( 2850): Process: com.google.process.gapps, PID: 2850
E/AndroidRuntime( 2850): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2850): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2850): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2850): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2850): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2850): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2850): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2850): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2850): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2850): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2850): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2850): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2850): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2850): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2850): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2850): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2850): 	... 10 more
,E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 2850): Sending signal. PID: 2850 SIG: 9
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 2850) (adj 5) has died.
,D/PowerManagerService( 2422): [api] handleWakeLockDeath : release WakeLock : PARTIAL_WAKE_LOCK              'Icing' (uid=10012, pid=3310, ws=WorkSource{10012 com.google.android.gms}) (elapsedTime=45)
,E/SQLiteDatabase( 5585): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5585): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5585): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5585): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5585): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5585): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5585): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5585): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5585): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5585): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5585): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5585): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5585): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5585): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5585): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5585): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5585): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5585): 	at dalvik.system.NativeStart.main(Native Method)
E/SPPClientService( 5585): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5676): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5676): Thread[main,5,main]: Unexpected disconnect.
,I/ActivityManager( 2422): Process com.google.android.gms (pid 3310) (adj 0) has died.,
E/SQLiteDatabase( 6442): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6442): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6442): ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6442): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6442): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6442): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6442): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6442): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6442): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6442): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6442): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6442): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6442): [g] not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 6442): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.,
E/SQLiteDatabase( 6442): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6442): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6442): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6442): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6442): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6442): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6442): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6442): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6442): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6442): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6442): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6442): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6442): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7668): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7668):  
,I/SELinux ( 7668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7668):  
I/SELinux ( 7668):  
,I/SELinux ( 7668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7668): >>>>> Normal User
,E/dalvikvm( 7668): >>>>> com.android.documentsui [ userId:0 | appId:10093 ],
,E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7668): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7668): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7668): Added TimaKesytore provider
,D/dalvikvm( 7668): GC_CONCURRENT freed 2999K, 31% free 9566K/13748K, paused 3ms+1ms, total 19ms,
,D/dalvikvm( 7668): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/Documents( 7668): Loading roots for com.android.externalstorage.documents,
,E/SQLiteDatabase( 7668): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.,
E/SQLiteDatabase( 7668): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7668): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7668): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7668): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7668): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7668): 	,at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7668): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7668): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7668): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7668): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7668): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7668): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7668): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7668): 	at dalvik.system.NativeStart.main(Native Method)
I/SELinux ( 7681): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7681):  
D/AndroidRuntime( 7668): Shutting down VM
,W/dalvikvm( 7668): threadid=1: thread exiting with uncaught exception (group=0x41e60c08),
E/AndroidRuntime( 7668): FATAL EXCEPTION: main
E/AndroidRuntime( 7668): Process: com.android.documentsui, PID: 7668
E/AndroidRuntime( 7668): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7668): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.main(ActivityThread.java:5694),
E/AndroidRuntime( 7668): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7668): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7668): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7668): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7668): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7668): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7668): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7668): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7668): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7668): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7668): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7668): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7668): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7668): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7668): 	... 10 more
,I/SELinux ( 7685): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7685):  
,I/Process ( 7668): Sending signal. PID: 7668 SIG: 9,
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
,E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
I/SELinux ( 7681): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7681):  
I/SELinux ( 7681):  
I/SELinux ( 7681): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7681): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
E/dalvikvm( 7681): >>>>> Normal User
,E/dalvikvm( 7681): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ],
,E/SELinux ( 7681): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/ActivityManager( 2422): Process com.android.documentsui (pid 7668) (adj 9) has died.,
,D/TimaKeyStoreProvider( 7681): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7681): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7681): Added TimaKesytore provider
I/SELinux ( 7685): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7685):  
I/SELinux ( 7685):  
,I/SELinux ( 7685): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7685): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7685): >>>>> Normal User
,E/dalvikvm( 7685): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7685): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7685): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7685): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7685): Added TimaKesytore provider
,D/dalvikvm( 7681): GC_CONCURRENT freed 3003K, 31% free 9564K/13748K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7681): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/ExternalStorage( 7681): After updating volumes, found 1 active roots
,D/dalvikvm( 7685): GC_CONCURRENT freed 2941K, 30% free 9630K/13752K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7685): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/dalvikvm( 7685): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7685): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7685): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7685): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7685): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7685): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7685): install
,I/MultiDex( 7685): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7685): loading existing secondary dex files
,I/MultiDex( 7685): load found 3 secondary dex files
,I/MultiDex( 7685): install done
,I/SELinux ( 7707): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7707):  
,I/SELinux ( 7707): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7707):  
I/SELinux ( 7707):  
,I/SELinux ( 7707): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7707): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7707): >>>>> Normal User
,E/dalvikvm( 7707): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7707): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7707): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7707): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7707): Added TimaKesytore provider
,I/SELinux ( 7721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7721):  
,D/dalvikvm( 7707): GC_CONCURRENT freed 2993K, 31% free 9575K/13748K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7707): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/SELinux ( 7721): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7721):  
I/SELinux ( 7721):  
,I/SELinux ( 7721): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7721): >>>>> Normal User
,E/dalvikvm( 7721): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7721): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7721): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7721): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7721): Added TimaKesytore provider
,I/Icing.InternalIcingCorporaProvider( 7707): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7737): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7737):  
,D/LocationManagerService( 2422): getProviders()=[passive]
,D/dalvikvm( 7721): GC_CONCURRENT freed 2973K, 31% free 9592K/13748K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7721): WAIT_FOR_CONCURRENT_GC blocked 9ms
,I/SELinux ( 7737): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7737):  
I/SELinux ( 7737):  
,I/SELinux ( 7737): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7737): >>>>> Normal User
,E/dalvikvm( 7737): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7737): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7737): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7737): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7737): Added TimaKesytore provider
,I/GservicesProvider( 7721): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7721): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7721): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7721): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7721): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7721): Shutting down VM
,W/dalvikvm( 7721): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
E/AndroidRuntime( 7721): FATAL EXCEPTION: main
E/AndroidRuntime( 7721): Process: com.google.process.gapps, PID: 7721
E/AndroidRuntime( 7721): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7721): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7721): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7721): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7721): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7721): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7721): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7721): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7721): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7721): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7721): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7721): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7721): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7721): 	... 12 more
,I/Process ( 7721): Sending signal. PID: 7721 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
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
,D/dalvikvm( 7737): GC_CONCURRENT freed 3001K, 31% free 9566K/13752K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7737): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7721) (adj 0) has died.
,W/ActivityManager( 2422): Service crashed 2 times, stopping: ServiceRecord{435cd6b0 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7755): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7755):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9501K/10728K, paused 2ms+3ms, total 27ms
,I/SELinux ( 7755): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7755):  
I/SELinux ( 7755):  
,I/SELinux ( 7755): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7755): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7755): >>>>> Normal User
,E/dalvikvm( 7755): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7755): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 1ms+3ms, total 23ms,
,D/TimaKeyStoreProvider( 7755): in addTimaSignatureService,
D/TimaKeyStoreProvider( 7755): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7755): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9501K/10728K, paused 2ms+2ms, total 22ms,
,D/dalvikvm( 7755): GC_CONCURRENT freed 2987K, 31% free 9580K/13752K, paused 3ms+1ms, total 20ms,
,D/dalvikvm( 7755): WAIT_FOR_CONCURRENT_GC blocked 11ms,
,I/GservicesProvider( 7755): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7755): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.,
E/SQLiteDatabase( 7755): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
,E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7755): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7755): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
,E/SQLiteDatabase( 7755): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7755): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7755): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
,E/SQLiteDatabase( 7755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7755): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7755): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7755): 	at dalvik.system.NativeStart.main(Native Method),
D/AndroidRuntime( 7755): Shutting down VM
,W/dalvikvm( 7755): threadid=1: thread exiting with uncaught exception (group=0x41e60c08),
E/AndroidRuntime( 7755): FATAL EXCEPTION: main
E/AndroidRuntime( 7755): Process: com.google.process.gapps, PID: 7755
E/AndroidRuntime( 7755): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7755): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7755): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
,E/AndroidRuntime( 7755): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7755): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7755): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7755): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7755): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7755): 	at android.app.ActivityThread.main(ActivityThread.java:5694),
E/AndroidRuntime( 7755): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7755): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7755): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7755): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7755): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7755): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7755): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7755): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7755): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7755): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/AndroidRuntime( 7755): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7755): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7755): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7755): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562),
E/AndroidRuntime( 7755): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7755): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7755:com.google.process.gapps/u0a12 (adj 0): crash,
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7685): Failed to find provider info for com.google.android.gsf.gservices,
E/ActivityThread( 7737): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7707): Failed to find provider info for com.google.settings
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
,I/SELinux ( 7773): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7773):  
,I/SELinux ( 7773): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7773):  
I/SELinux ( 7773):  
,I/SELinux ( 7773): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7773): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7773): >>>>> Normal User
,E/dalvikvm( 7773): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7773): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7773): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7773): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7773): Added TimaKesytore provider,
,D/dalvikvm( 7773): GC_CONCURRENT freed 2990K, 31% free 9577K/13748K, paused 3ms+1ms, total 19ms,
,D/dalvikvm( 7773): WAIT_FOR_CONCURRENT_GC blocked 8ms,
,I/GservicesProvider( 7773): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7773): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7773): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232),
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322),
E/SQLiteDatabase( 7773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7773): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7773): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7773): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
,E/SQLiteDatabase( 7773): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7773): 	at android.os.Handler.dispatchMessage(Handler.java:102),
E/SQLiteDatabase( 7773): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7773): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7773): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7773): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7773): 	,at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7773): Shutting down VM
,W/dalvikvm( 7773): threadid=1: thread exiting with uncaught exception (group=0x41e60c08),
,E/AndroidRuntime( 7773): FATAL EXCEPTION: main
E/AndroidRuntime( 7773): Process: com.google.process.gapps, PID: 7773,
E/AndroidRuntime( 7773): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7773): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7773): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7773): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7773): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7773): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7773): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7773): ,	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7773): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206),
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7773): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7773): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7773): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/AndroidRuntime( 7773): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7773): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7773): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7773): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7773): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7773): 	... 12 more
,I/Process ( 7773): Sending signal. PID: 7773 SIG: 9,
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
,E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): ,	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7773) (adj 0) has died.
,I/SELinux ( 7788): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7788):  
,I/SELinux ( 7788): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7788):  
I/SELinux ( 7788):  
,I/SELinux ( 7788): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7788): >>>>> Normal User
,E/dalvikvm( 7788): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7788): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7788): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7788): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7788): Added TimaKesytore provider,
,D/dalvikvm( 7788): GC_CONCURRENT freed 2994K, 31% free 9577K/13752K, paused 2ms+2ms, total 18ms,
,D/dalvikvm( 7788): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7788): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7788): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7788): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
,E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7788): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7788): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7788): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7788): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294),
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7788): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7788): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/SQLiteDatabase( 7788): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7788): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7788): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7788): Shutting down VM
,W/dalvikvm( 7788): threadid=1: thread exiting with uncaught exception (group=0x41e60c08),
E/AndroidRuntime( 7788): FATAL EXCEPTION: main
E/AndroidRuntime( 7788): Process: com.google.process.gapps, PID: 7788
E/AndroidRuntime( 7788): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7788): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7788): ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7788): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7788): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7788): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7788): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7788): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7788): 	,at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7788): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7788): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7788): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7788): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7788): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7788): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7788): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7788): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7788): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7788): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7788): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7788): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7788): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7788): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7788): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7788): 	... 12 more
,W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7788:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
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
,E/ActivityThread( 7685): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7737): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7685): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7685): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7685): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7685): VFY: unable to resolve instance field 36
D/dalvikvm( 7685): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7685): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7685): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7685): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7685): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7685): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,I/ActivityManager( 2422): Killing 6597:com.samsung.groupcast/u0a15 (adj 15): empty #43,
D/dalvikvm( 7685): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x428c9eb0
D/dalvikvm( 7685): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x428c9eb0
D/dalvikvm( 7685): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x428c9eb0, skipping init
D/dalvikvm( 7685): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x428c9eb0
D/dalvikvm( 7685): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x428c9eb0
V/JNIHelp ( 7685): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7685): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x428c9eb0,
D/dalvikvm( 7685): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x428c9eb0
D/dalvikvm( 7685): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x428c9eb0
,D/dalvikvm( 7685): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428c9eb0,
,I/ProviderInstaller( 7685): Installed default security provider GmsCore_OpenSSL,
,I/SELinux ( 7803): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7803):  
,I/SELinux ( 7803): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7803):  
I/SELinux ( 7803):  
I/SELinux ( 7803): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7803): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7803): >>>>> Normal User
,E/dalvikvm( 7803): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7803): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7803): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7803): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7803): Added TimaKesytore provider
,D/dalvikvm( 7803): GC_FOR_ALLOC freed 3015K, 31% free 9553K/13752K, paused 16ms, total 16ms
,D/dalvikvm( 7803): GC_CONCURRENT freed 206K, 31% free 9590K/13752K, paused 3ms+2ms, total 16ms
,I/GservicesProvider( 7803): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7803): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7803): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7803): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7803): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7803): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7803): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7803): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7803): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7803): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7803): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7803): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7803): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7803): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7803): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7803): Shutting down VM
,W/dalvikvm( 7803): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
,E/AndroidRuntime( 7803): FATAL EXCEPTION: main
E/AndroidRuntime( 7803): Process: com.google.process.gapps, PID: 7803
E/AndroidRuntime( 7803): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7803): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7803): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7803): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7803): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7803): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7803): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7803): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7803): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7803): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7803): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7803): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7803): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7803): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7803): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7803): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7803): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7803): 	... 12 more
,I/Process ( 7803): Sending signal. PID: 7803 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7803) (adj 0) has died.
,I/SELinux ( 7818): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7818):  
,I/SELinux ( 7818): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7818):  
I/SELinux ( 7818):  
,I/SELinux ( 7818): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7818): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7818): >>>>> Normal User
,E/dalvikvm( 7818): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7818): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7818): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7818): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7818): Added TimaKesytore provider
,D/dalvikvm( 7818): GC_CONCURRENT freed 2985K, 31% free 9580K/13748K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7818): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/dalvikvm( 2959): threadid=12: thread exiting with uncaught exception (group=0x41e60c08)
,E/AndroidRuntime( 2959): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2959): Process: android.process.acore, PID: 2959
E/AndroidRuntime( 2959): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2959): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2959): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2959): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2959): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2959): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2959): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2959): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2959): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2959): Sending signal. PID: 2959 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
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
,I/GservicesProvider( 7818): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7818): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7818): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7818): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7818): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7818): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7818): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7818): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7818): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7818): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7818): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7818): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7818): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7818): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7818): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7818): Shutting down VM
,W/dalvikvm( 7818): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
E/AndroidRuntime( 7818): FATAL EXCEPTION: main
E/AndroidRuntime( 7818): Process: com.google.process.gapps, PID: 7818
E/AndroidRuntime( 7818): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7818): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7818): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7818): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7818): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7818): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7818): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7818): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7818): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7818): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7818): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7818): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7818): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7818): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7818): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7818): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7818): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7818): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7818:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7685): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
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
,W/NativeLibraryUtils( 7685): Failed to open lock file
W/NativeLibraryUtils( 7685): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7685): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7685): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7685): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7685): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7685): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7685): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7685): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7685): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7685): 	... 3 more
I/ActivityManager( 2422): Process android.process.acore (pid 2959) (adj -12) has died.
,I/SELinux ( 7837): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7837):  
,I/SELinux ( 7845): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7845):  
I/dalvikvm( 7685): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7685): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7685): VFY: replacing opcode 0x6e at 0x000d,
I/SELinux ( 7837): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7837):  
I/SELinux ( 7837):  
,I/SELinux ( 7837): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7837): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7837): >>>>> Normal User
,E/dalvikvm( 7837): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7837): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7837): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7837): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7837): Added TimaKesytore provider
,I/SELinux ( 7845): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7845):  
I/SELinux ( 7845):  
,I/SELinux ( 7845): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7845): >>>>> Normal User
,E/dalvikvm( 7845): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7845): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7845): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7845): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7845): Added TimaKesytore provider
,D/dalvikvm( 7837): GC_CONCURRENT freed 2989K, 31% free 9578K/13748K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7837): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/dalvikvm( 7845): GC_CONCURRENT freed 2986K, 31% free 9577K/13744K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7845): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7845): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7845): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7845): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7845): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7845): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7845): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7845): Shutting down VM
,W/dalvikvm( 7845): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
,I/Process ( 7845): Sending signal. PID: 7845 SIG: 9
E/AndroidRuntime( 7845): FATAL EXCEPTION: main
E/AndroidRuntime( 7845): Process: com.google.process.gapps, PID: 7845
E/AndroidRuntime( 7845): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7845): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7845): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7845): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7845): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7845): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7845): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7845): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7845): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7845): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7845): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7845): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7845): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7845): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7845): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7845): 	... 12 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7845) (adj 0) has died.
,I/SELinux ( 7870): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7870):  
,E/SQLiteDatabase( 7837): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7837): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7837): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7837): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7837): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7837): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7837): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7837): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7837): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7837): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7837): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7837): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7837): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7837): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7837): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7837): (14) unable to open database file
,E/SQLiteDatabase( 7837): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7837): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7837): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7837): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7837): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7837): threadid=13: thread exiting with uncaught exception (group=0x41e60c08)
E/AndroidRuntime( 7837): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7837): Process: android.process.acore, PID: 7837
E/AndroidRuntime( 7837): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7837): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7837): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7837): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7837): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7837): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7837): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7837): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7837): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 2422): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7837): Sending signal. PID: 7837 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
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
,I/SELinux ( 7870): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7870):  
I/SELinux ( 7870):  
,I/SELinux ( 7870): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7870): >>>>> Normal User
,E/dalvikvm( 7870): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
I/ActivityManager( 2422): Process android.process.acore (pid 7837) (adj -12) has died.
,F/ActivityManager( 2422): Service ServiceRecord{438babd8 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{43032628 7837:android.process.acore/u0a20} not same as in map: null
,E/SELinux ( 7870): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/DropBoxManagerService( 2422): Can't write: system_server_wtf
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2422): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2422): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2422): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2422): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2422): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 18 more
,D/TimaKeyStoreProvider( 7870): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7870): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7870): Added TimaKesytore provider
,I/SELinux ( 7886): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7886):  
,I/SELinux ( 7886): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7886):  
I/SELinux ( 7886):  
,I/SELinux ( 7886): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7886): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7886): >>>>> Normal User
,E/dalvikvm( 7886): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7886): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7886): in addTimaSignatureService
,D/dalvikvm( 7870): GC_CONCURRENT freed 3000K, 31% free 9567K/13748K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 7870): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/TimaKeyStoreProvider( 7886): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7886): Added TimaKesytore provider
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.78/generate_204
,D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
I/GservicesProvider( 7870): Gservices pushing to system: true; secure/global: true
E/SQLiteDatabase( 7870): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7870): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7870): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7870): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7870): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7870): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7870): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7870): Shutting down VM
,W/dalvikvm( 7870): threadid=1: thread exiting with uncaught exception (group=0x41e60c08)
,E/AndroidRuntime( 7870): FATAL EXCEPTION: main
E/AndroidRuntime( 7870): Process: com.google.process.gapps, PID: 7870
E/AndroidRuntime( 7870): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7870): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7870): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7870): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7870): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7870): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7870): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7870): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7870): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7870): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7870): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7870): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7870): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7870): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7870): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7870): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7870): 	... 12 more
D/dalvikvm( 7886): GC_CONCURRENT freed 2994K, 31% free 9575K/13752K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7886): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7870:com.google.process.gapps/u0a12 (adj 0): crash
,I/GAv4-SVC( 7685): Google Analytics 8.4.89 is starting up.
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7685): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7685): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop240.tmp: open failed: EROFS (Read-only file system)
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
,I/SELinux ( 7903): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7903):  
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/SELinux ( 7903): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7903):  
I/SELinux ( 7903):  
,I/SELinux ( 7903): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7903): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7903): >>>>> Normal User
,E/dalvikvm( 7903): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7903): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7903): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7903): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7903): Added TimaKesytore provider
,E/SQLiteDatabase( 7886): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7886): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7886): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7886): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7886): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7886): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7886): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7886): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7886): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7886): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7886): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7886): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7886): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7886): (14) unable to open database file
E/SQLiteDatabase( 7886): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7886): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7886): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7886): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7886): threadid=13: thread exiting with uncaught exception (group=0x41e60c08)
E/AndroidRuntime( 7886): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7886): Process: android.process.acore, PID: 7886
E/AndroidRuntime( 7886): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7886): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7886): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7886): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7886): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7886): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7886): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7886): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7886): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager( 2422): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7886): Sending signal. PID: 7886 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop241.tmp: open failed: EROFS (Read-only file system)
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

```
