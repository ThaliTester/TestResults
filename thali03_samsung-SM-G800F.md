#### Test 56151093f6e24ff_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2413): level:100, scale:100, status:5, health:2, present:true, voltage: 4373, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2413): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2413): mCoverManager.getCoverState() : true
D/BatteryService( 2413): stay LED for fully charged
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3994): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
V/ApplicationPolicy( 2413): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2413): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2413): mDVFSHelper.acquire()
I/SELinux ( 7208): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7208):  
D/PointerIcon( 2413): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2413): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2413): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2413): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7197): Shutting down VM
D/dalvikvm( 7197): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7208): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7208):  
I/SELinux ( 7208):  
I/SELinux ( 7208): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7208): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7208): >>>>> Normal User
E/dalvikvm( 7208): >>>>> com.test.thalitest [ userId:0 | appId:10633 ]
E/SELinux ( 7208): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7208): in addTimaSignatureService
D/TimaKeyStoreProvider( 7208): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7208): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4175): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4175): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1922): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7208): GC_CONCURRENT freed 3005K, 31% free 9560K/13812K, paused 2ms+2ms, total 19ms
D/dalvikvm( 7208): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7208): Binding Chromium to the background looper Looper (main, tid 1) {422881e0}
I/chromium( 7208): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7208): Initializing chromium process, renderers=0
W/chromium( 7208): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7208): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7208): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7208): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7208): Mali API Version : 401
,I/Mali    ( 7208): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7208): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7208): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7208): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7208): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7208): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7208): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2413): tr p:7208,o:f
,W/dalvikvm( 7208): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7208): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7208): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7208): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7208): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7208): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7208): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7208): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7208): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7208): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7208): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7208): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7208): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2413): semi p:7208,o:f
,I/SurfaceFlinger( 1922): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2413): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2413): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2413): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2413): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2413): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2413): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7208): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7208): Enabling debug mode 0
,W/AwContents( 7208): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2413): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7208): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2413): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2413): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2413): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7208): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7208): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42288f68
,D/dalvikvm( 7208): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42288f68
D/jxcore_app_log( 7208): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2028065712
,D/JX-Cordova( 7208): jxcore cordova android initializing
,D/dalvikvm( 7208): GC_CONCURRENT freed 1283K, 19% free 11349K/13872K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7208): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/SSRMv2:SIOP( 2413): SIOP:: AP = 330, Delta = 10
,D/dalvikvm( 7208): GC_CONCURRENT freed 1713K, 17% free 15172K/18156K, paused 1ms+3ms, total 38ms
,D/dalvikvm( 7208): WAIT_FOR_CONCURRENT_GC blocked 30ms
,D/CustomFrequencyManagerService( 2413): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  tag : ACTIVITY_RESUME_BOOSTER@8
,D/AmoledAdjustTimer( 2413): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,D/dalvikvm( 7208): GC_FOR_ALLOC freed 5698K, 30% free 16763K/23740K, paused 47ms, total 48ms
,D/dalvikvm( 7208): GC_CONCURRENT freed 6772K, 31% free 18145K/26196K, paused 3ms+11ms, total 76ms
,D/dalvikvm( 7208): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 7208): GC_FOR_ALLOC freed 848K, 31% free 18123K/26196K, paused 38ms, total 38ms
,I/dalvikvm-heap( 7208): Grow heap (frag case) to 22.425MB for 3688532-byte allocation
,D/dalvikvm( 7208): GC_FOR_ALLOC freed 2429K, 36% free 19296K/29800K, paused 49ms, total 49ms
,W/jxcore-log( 7208): Initializing JXcore engine
,W/jxcore-log( 7208): JXcore engine is ready
,W/jxcore-log( 7208): Starting JXcore engine
,W/jxcore-log( 7208): Platform android
W/jxcore-log( 7208): 
,W/jxcore-log( 7208): Process ARCH arm
W/jxcore-log( 7208): 
,I/jxcore-log( 7208): JXcore Cordova bridge is ready!
I/jxcore-log( 7208): 
,W/jxcore-log( 7208): JXcore engine is started
,I/chromium( 7208): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7208): Toggling radios to true
I/jxcore-log( 7208): 
,D/BluetoothAdapter( 7208): enable(): BT is already enabled..!
,I/WifiManager( 7208): packageName : com.test.thalitest
I/WifiManager( 7208): setWifiEnabled : true
,I/WifiService( 2413): setWifiEnabled: true pid=7208, uid=10633
W/ActivityManager( 2413): Permission Denial: getCurrentUser() from pid=7208, uid=10633 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2413): Failed getting userId using ActivityManagerNative
W/WifiService( 2413): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7208, uid=10633 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2413): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2413): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2413): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2413): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2413): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2413): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2413): disconnect: pid=7208, uid=10633
,I/jxcore-log( 7208): Radios toggled
I/jxcore-log( 7208): 
I/jxcore-log( 7208): My device name is: samsung-SM-G800F
I/jxcore-log( 7208): 
,I/wpa_supplicant( 3968): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3968): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3968): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3968): wlan0: Setting scan request: 0 sec 0 usec
D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
D/Tethering( 2413): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3968): First Scan Start
,W/Settings( 2413): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2413): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3968): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2413): InactiveState{ what=143375 }
D/WifiP2pService( 2413): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2413): evaluateTrafficStatsPolling
I/wpa_supplicant( 3968): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3968): Skip scan - already scanning
D/ConnectivityService( 2413): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2413): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2413): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2413): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2413): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2413): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2413): InactiveState{ what=143375 }
D/WifiP2pService( 2413): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2413): Attempting to switch to mobile
,D/ConnectivityService( 2413): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7254): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7254):  
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1916): RTNETLINK answers: No such process
V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/SELinux ( 7254): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7254):  
I/SELinux ( 7254):  
,I/SELinux ( 7254): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7254): >>>>> Normal User
,E/dalvikvm( 7254): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2413): route cmd failed: 
W/NetworkManagementService( 2413): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2413): '
W/NetworkManagementService( 2413): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2413): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2413): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2413): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2413): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2413): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2413): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2413): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2413): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2413): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2413): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2413): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2413): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2413): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2413): Error! unhandled message{ when=-96ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2413): Error! unhandled message{ when=-96ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,E/WifiStateMachine( 2413): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,D/TimaKeyStoreProvider( 7254): in addTimaSignatureService,
,D/NetUtils( 2413): android_net_utils_resetConnections in env=0x78670dd8 clazz=0x61a00001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2413): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 7254): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7254): Added TimaKesytore provider,
,E/SPPClientService( 5539): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,E/SPPClientService( 5539): [e] exceptionCaught(). NET_TIMEOUT,
,E/SPPClientService( 5539): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.,
,E/SPPClientService( 5539): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5539): [b] ResponseMap empty,
,V/NativeCrypto( 2853): Read error: ssl=0x7baccc30: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2853): SSL shutdown failed: ssl=0x7baccc30: I/O error during system call, Broken pipe,
,D/dalvikvm( 7254): GC_CONCURRENT freed 2985K, 31% free 9584K/13812K, paused 5ms+1ms, total 38ms,
,D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 26ms,
,D/ConnectivityService( 2413): handleInetConditionChange: no active default network - ignore,
,V/NetworkStats( 2413): updateIfacesLocked(),
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
V/NetworkStats( 2413): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
V/NetworkStats( 2413): advisePersistThreshold() given 9223372036854775, clamped to 2097152,
,I/System.out( 7254): Inside WakeupProvider,
,I/System.out( 7254): Inside onCreate() of WakeupTriggerProvide,
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
V/NetworkStats( 2413): performPollLocked() took 32ms
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
I/VlingoApplication( 7254): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7254): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7254): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,W/ContextImpl( 2413): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,I/ActivityManager( 2413): Killing 6170:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7254): initQueue()
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2835): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2835): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2413): Tethering got CONNECTIVITY_ACTION
,I/ApplicationPolicy( 2413): updateDataUsageMap
,D/Tethering( 2413): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2413): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false,
D/ConnectivityService( 2413): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6610): SPPPushClient is installed : true,
I/PCWCLIENTTRACE_PushUtil( 6610): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6610): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6610): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6610): noConnectivity : true,
,D/libgps  ( 2413): agps_ril_update_network_state: Waiting for IPC connection...,
,I/DBG_DM  ( 4736): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected,
,I/SELinux ( 7283): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7283):  
,I/SELinux ( 7283): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7283):  
I/SELinux ( 7283):  
,I/SELinux ( 7283): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7283): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7283): >>>>> Normal User
,E/dalvikvm( 7283): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ],
,E/SELinux ( 7283): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7283): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7283): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7283): Added TimaKesytore provider
,I/wpa_supplicant( 3968): nl80211: Received scan results (3 BSSes),
I/wpa_supplicant( 3968): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3968): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz),
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true,
,D/dalvikvm( 7283): GC_CONCURRENT freed 2989K, 31% free 9579K/13812K, paused 3ms+2ms, total 20ms,
,D/dalvikvm( 7283): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/ActivityManager( 2413): Killing 6239:com.sec.android.app.music:service/u0a152 (adj 15): empty #43,
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true
D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true
,D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3968): Associated with C0.AA.48
I/wpa_supplicant( 3968): freq(2412) increment count 2
,I/wpa_supplicant( 3968): meet head of list.
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3968): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3968): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2413): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2413): interfaceStatusChanged wlan0, true
,D/WifiNative( 2413): callSECApiVoid - ID [50]
,I/SELinux ( 7297): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7297):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7297): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7297):  
I/SELinux ( 7297):  
,I/SELinux ( 7297): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7297): [DEBUG] seapp_context_lookup: seinfoCategory = release
,E/dalvikvm( 7297): >>>>> Normal User
,E/dalvikvm( 7297): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7297): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7297): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7297): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7297): Added TimaKesytore provider
,D/WifiP2pService( 2413): InactiveState{ what=143375 }
,D/WifiP2pService( 2413): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7297): GC_CONCURRENT freed 2992K, 31% free 9577K/13816K, paused 4ms+2ms, total 21ms
,D/dalvikvm( 7297): WAIT_FOR_CONCURRENT_GC blocked 5ms
,D/dalvikvm( 2413): GC_CONCURRENT freed 4339K, 75% free 25462K/98084K, paused 12ms+17ms, total 236ms
,I/ActivityManager( 2413): Killing 6312:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7312): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7312):  
,I/SELinux ( 7312): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7312):  
I/SELinux ( 7312):  
,I/SELinux ( 7312): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7312): >>>>> Normal User
,E/dalvikvm( 7312): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7312): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/dhcpcd  ( 7309): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7309): bssid match
,D/TimaKeyStoreProvider( 7312): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7312): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7312): Added TimaKesytore provider
,D/dalvikvm( 7312): GC_CONCURRENT freed 2996K, 31% free 9566K/13808K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7312): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/KLMS-2.3.201 : ( 7312): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7312): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453125443889
,I/KLMS-2.3.201 : ( 7312): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2413): Killing 6340:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7328): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7328):  
,D/libgps  ( 2413): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2413): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2413): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2413): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7328): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7328):  
I/SELinux ( 7328):  
,I/SELinux ( 7328): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7328): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7328): >>>>> Normal User
,E/dalvikvm( 7328): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ],
,E/SELinux ( 7328): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7328): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7328): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7328): Added TimaKesytore provider
,D/dalvikvm( 7328): GC_CONCURRENT freed 3010K, 31% free 9556K/13808K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7328): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/SO_AGENT( 7328): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7328): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5804): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5804): [BDLM] already registered in spp
I/SA      ( 5804): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5804): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5804): [OR] == isSIMCardReady false ==
I/SA      ( 5804): [SCU] == networkStateCheck == false
,I/SA      ( 5804): [OR] onReceive END,
I/ActivityManager( 2413): Killing 6385:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43,
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SELinux ( 7340): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7340):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 12% free 9503K/10788K, paused 3ms+3ms, total 36ms
I/SELinux ( 7340): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7340):  
I/SELinux ( 7340):  
,I/SELinux ( 7340): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7340): >>>>> Normal User
,E/dalvikvm( 7340): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7340): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7340): in addTimaSignatureService
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 3ms+3ms, total 31ms
,D/TimaKeyStoreProvider( 7340): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7340): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 7340): GC_CONCURRENT freed 3014K, 31% free 9561K/13816K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7340): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/sCloudBackupApp( 7340): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7340): Other Intent
I/ActivityManager( 2413): Killing 5586:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7353): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7353):  
,I/SELinux ( 7353): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7353):  
I/SELinux ( 7353):  
,I/SELinux ( 7353): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7353): >>>>> Normal User
,E/dalvikvm( 7353): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7353): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7353): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7353): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7353): Added TimaKesytore provider
,D/dalvikvm( 7353): GC_CONCURRENT freed 2990K, 31% free 9571K/13808K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7353): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7353): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7353): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5338): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7353): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5338): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7353): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5338): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2413): Killing 6293:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5870): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5870): getCountryCode(): countryCode = PL
,D/Headlines( 5870): Breath.onCreate
,D/Headlines( 5870): Breath timer started. interval : 30000
,I/SELinux ( 7365): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7365):  
D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5870): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5870): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5870): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2413): waitForAlarm result :8
,I/SELinux ( 7365): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7365):  
I/SELinux ( 7365):  
,I/SELinux ( 7365): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7365): >>>>> Normal User
,E/dalvikvm( 7365): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7365): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7365): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7365): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7365): Added TimaKesytore provider
,D/dalvikvm( 7365): GC_CONCURRENT freed 2994K, 31% free 9573K/13808K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7365): WAIT_FOR_CONCURRENT_GC blocked 15ms
,V/WebViewChromium( 7365): Binding Chromium to the background looper Looper (main, tid 1) {42285390}
,I/chromium( 7365): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7365): Initializing chromium process, renderers=0
,W/chromium( 7365): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7365): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7365): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7365): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7365): Mali API Version : 401
,I/Mali    ( 7365): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2413): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2413): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2413): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7365): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7365): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7365): Starting up...
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiP2pService( 2413): InactiveState{ what=143375 }
,D/WifiP2pService( 2413): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2413): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.SyncManager( 5935): SYNC; picasa accounts
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/iu.UploadsManager( 5935): num queued entries: 0
,I/iu.UploadsManager( 5935): num updated entries: 0
,I/iu.SyncManager( 5935): NEXT; no task
,D/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,D/WifiStateMachine( 2413): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
V/QuickConnect[1.1][2] ( 5137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42295608
,D/WifiStateMachine( 2413): CaptivePortalCheckState enter
,I/SELinux ( 7425): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7425):  
,I/WifiTrafficPoller( 2413): evaluateTrafficStatsPolling
D/ConnectivityService( 2413): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2413): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2413): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/WifiTrafficPoller( 2413): evaluateTrafficStatsPolling
D/ConnectivityService( 2413): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2413): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2413): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
I/SELinux ( 7425): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7425):  
I/SELinux ( 7425):  
I/SELinux ( 7425): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7425): >>>>> Normal User
E/dalvikvm( 7425): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7425): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/ConnectivityService( 2413): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/TimaKeyStoreProvider( 7425): in addTimaSignatureService,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,D/TimaKeyStoreProvider( 7425): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7425): Added TimaKesytore provider,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2413): updateIfacesLocked(),
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit,
,V/NetworkStats( 2413): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
D/NtpTrustedTime( 2413): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit,
V/NetworkStats( 2413): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit,
V/NetworkStats( 2413): performPollLocked() took 23ms
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2413): currentTimeMillis() cache hit,
,D/dalvikvm( 7425): GC_CONCURRENT freed 2991K, 31% free 9582K/13816K, paused 3ms+3ms, total 31ms,
,D/dalvikvm( 7425): WAIT_FOR_CONCURRENT_GC blocked 11ms,
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId,
,I/SELinux ( 7460): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7460):  
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId,
I/ActivityManager( 2413): Killing 6316:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7460): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7460):  
I/SELinux ( 7460):  
I/SELinux ( 7460): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,W/ActivityManager( 2413): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
E/SELinux ( 7460): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7460): >>>>> Normal User
E/dalvikvm( 7460): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7460): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7472): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7472):  
,D/TimaKeyStoreProvider( 7460): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7460): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7460): Added TimaKesytore provider
,I/ActivityManager( 2413): Killing 5986:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7472): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7472):  
I/SELinux ( 7472):  
,I/SELinux ( 7472): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7472): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7472): >>>>> Normal User
,E/dalvikvm( 7472): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7472): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7472): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7472): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7472): Added TimaKesytore provider
,D/dalvikvm( 7460): GC_CONCURRENT freed 3012K, 31% free 9556K/13816K, paused 6ms+1ms, total 25ms
,D/dalvikvm( 7460): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/BadgeProvider( 7460): onCreate
,D/BadgeProvider( 7460): DatabaseHelper
,D/BadgeProvider( 7460): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7460): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7460): sendNotify, [notify] : null
D/BadgeProvider( 7460): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7460): update, [BadgeCount] : badgecount=0
D/Launcher.Model( 2774): reloadBadges entered.
,D/BadgeProvider( 7460): update, [UpdateCount] : 1
,D/dalvikvm( 7472): GC_CONCURRENT freed 2999K, 31% free 9567K/13812K, paused 3ms+1ms, total 25ms
,D/dalvikvm( 7472): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/hcjo    ( 5956): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5956): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5956): exit::IDLE
,D/InitializeManagerStateMachine( 5956): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5956): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5956): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5956): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5956): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5956): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5956): entry::SUCCESS
,D/hcjo    ( 5956): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5956): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5956): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/SPPClientService( 5539): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5539): [SystemStateMoniter] Current Time : 286776
,E/SPPClientService( 5539): [SystemStateMoniter] No Connect : true
,D/Tethering( 2413): Tethering got CONNECTIVITY_ACTION
,D/CaptivePortalTracker( 2413): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/Tethering( 2413): MasterInitialState.processMessage what=3
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/InitializeManagerStateMachine( 5956): exit::SUCCESS
D/InitializeManagerStateMachine( 5956): entry::IDLE
,D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,E/SPPClientService( 5539): [[SystemStateMonitorService]] No Active Internet
,I/DBG_DM  ( 4736): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
E/SPPClientService( 5539): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5539): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5870): Breath 1480 latestRequest time : 1453125444628 current time : 1453125446108
,D/libgps  ( 2413): agps_ril_update_network_state: Waiting for IPC connection...
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5539): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2835): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2835): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,D/BatteryService( 2413): level:100, scale:100, status:5, health:2, present:true, voltage: 4348, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2413): stay LED for fully charged
,D/BatteryService( 2413): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2413): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 3994): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3994): Disconnected process message: 10
,E/SPPClientService( 5539): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NearbySettings( 2835): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2835): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1922): id=20 createSurf (1x1),1 flag=4, Uoast
,I/PCWCLIENTTRACE_PushUtil( 6610): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6610): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6610): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6610): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
D/PowerManagerService( 2413): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2413
,E/SPPClientService( 5539): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5539): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5539): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7312): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7312): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1453125446488
,I/KLMS-2.3.201 : ( 7312): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7328): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3252): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7328): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7498): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7498):  
,I/GallerySearchProvider( 3381): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7498): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7498):  
I/SELinux ( 7498):  
,I/SELinux ( 7498): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7498): >>>>> Normal User
,E/dalvikvm( 7498): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7498): in addTimaSignatureService
D/TimaKeyStoreProvider( 7498): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7498): Added TimaKesytore provider
,I/SELinux ( 7510): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7510):  
,I/SELinux ( 7510): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7510):  
I/SELinux ( 7510):  
,I/SELinux ( 7510): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7510): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7510): >>>>> Normal User
,E/dalvikvm( 7510): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7510): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 7498): GC_CONCURRENT freed 2985K, 31% free 9584K/13812K, paused 5ms+1ms, total 24ms
,D/dalvikvm( 7498): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaKeyStoreProvider( 7510): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7510): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7510): Added TimaKesytore provider
,I/System.out( 7297): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7297): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7297): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/SA      ( 5804): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5804): [BDLM] already registered in spp
,I/SA      ( 5804): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5804): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,D/dalvikvm( 7510): GC_CONCURRENT freed 3012K, 31% free 9561K/13816K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7510): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5804): [OR] == isSIMCardReady false ==
,I/SA      ( 5804): [SCU] == networkStateCheck == true
,I/SA      ( 5804): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5804): isChinaCountryCode : false
,I/SA      ( 5804): [OR] == networkStateCheck true ==
,I/SA      ( 5804): [OR] GetMyCountryZoneTask
,I/SA      ( 5804): [OR] onReceive END
,I/SA      ( 5804): [SRS] prepareGetMyCountryZone
,I/SA      ( 5804): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5804): [SSP] query invoked
,V/KVNProvider( 7510): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7510): getFindoCursor query string : 
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SA      ( 5804): [TPMU] GetMccFromDB : null
,I/SA      ( 5804): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5804): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver( 7340): Other Intent
,I/SA      ( 5804): [RC New] Execute method=[GET] start
,V/KVNProvider( 7510): getTagSearchCursor() tagSearchCursor count : 0
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7353): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5870): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5870): getCountryCode(): countryCode = PL
I/ActivityManager( 2413): Killing 6261:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5870): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5870): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5870): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/iu.UploadsManager( 5935): num queued entries: 0
I/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42295608
,I/iu.UploadsManager( 5935): num updated entries: 0
,I/iu.SyncManager( 5935): NEXT; no task
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId
,D/RCPManagerService( 2413): exchangeData() failure , invalid userId
,D/hcjo    ( 5956): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5956): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5956): exit::IDLE
,D/InitializeManagerStateMachine( 5956): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5956): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5956): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5956): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5956): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5956): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5956): entry::SUCCESS
,D/hcjo    ( 5956): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5956): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5956): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5956): exit::SUCCESS
,D/InitializeManagerStateMachine( 5956): entry::IDLE
,E/SPPClientService( 5539): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5539): [SystemStateMoniter] Current Time : 287870
,E/SPPClientService( 5539): [SystemStateMoniter] No Connect : false
,I/System.out( 7297): AsyncTask #1 calls detatch()
,W/System.err( 7297): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7297): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7297): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7297): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7297): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7297): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7297): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7297): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7297): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7297): 	at java.lang.Thread.run(Thread.java:841)
W/System.err( 7297): Caused by: java.lang.NullPointerException
,W/System.err( 7297): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7297): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7297): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7297): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7297): 	... 8 more
,I/ActivityManager( 2413): Killing 6156:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
D/libgps  ( 2413): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2413): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2413): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2413): agps_ril_update_network_availability: Waiting for IPC connection...
,D/PackageManager( 2413): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Watchdog( 2413): !@Sync 9
,D/libgps  ( 2413): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2413): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2413): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7208): 
,D/SSRMv2:SIOP( 2413): SIOP:: AP = 340, Delta = 10
,D/AmoledAdjustTimer( 2413): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4
,E/WifiStateMachine( 2413): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7208): 
,D/dalvikvm( 5539): GC_CONCURRENT freed 2021K, 25% free 10447K/13800K, paused 5ms+4ms, total 44ms
,D/dalvikvm( 5539): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7208): 
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2413): Killing 6192:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2413): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2413) eventTime = 290543
D/PowerManagerService( 2413): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2413 (0x0)
D/PowerManagerService( 2413): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2413, ws=WorkSource{1000}) (elapsedTime=3473)
,I/GAV2    ( 7365): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 7208): Test app app.js loaded
I/jxcore-log( 7208): 
,I/dalvikvm( 7208): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7208): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7208): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7208): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7208): BLE advertisement is supported
I/jxcore-log( 7208): 
,I/Choreographer( 7208): Skipped 499 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7208): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5539): [[PushClientService]] F:false, D:false, E:true, T:false, S:false, R:false
,E/SPPClientService( 5539): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5539): [g] getNetMCC return empty string
,I/jxcore-log( 7208): --= Surplus to requirements =--
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): ****TEST TOOK:  ms ****
I/jxcore-log( 7208): 
,I/jxcore-log( 7208): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7208): 
,D/AndroidRuntime( 7542): 
D/AndroidRuntime( 7542): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7542): CheckJNI is OFF
,D/AndroidRuntime( 7542): setted country_code = Poland
,D/AndroidRuntime( 7542): setted countryiso_code = PL
D/AndroidRuntime( 7542): setted sales_code = PLS
D/AndroidRuntime( 7542): readGMSProperty: start
,D/AndroidRuntime( 7542): readGMSProperty: already setted!!
D/AndroidRuntime( 7542): readGMSProperty: end
,D/AndroidRuntime( 7542): addProductProperty: start
,D/dalvikvm( 7542): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7542): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7542): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 7542): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7542): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6610): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6610): [hasSamungAccount] - No Samsung Account
,W/WifiP2pStateTracker( 2413): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2413): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2413):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2413): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2413): updateSourceRoutes : no source routing conditions
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6610): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6610): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6610): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6610): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6610): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6610): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6610): [ensureRegistration] - No Samsung account
,E/memtrack( 7542): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7542): failed to load memtrack module: -2
,D/dalvikvm( 7542): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7542): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2413): START PACKAGE DELETE: observer{1117423568}
D/PackageManager( 2413): pkg{<packageName>}
D/PackageManager( 2413): user{0}
,D/PackageManager( 2413): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2413): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2413): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2413): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2413): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2413): !@killApplicatoin: 10633, uninstall pkg
,I/ActivityManager( 2413): Killing 7208:com.test.thalitest/u0a633 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2413): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2413): mDVFSHelper.acquire()
,I/WindowState( 2413): WIN DEATH: Window{43d5b1c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (8/10)
I/SurfaceFlinger( 1922): id=19 Removed NainActivit (-2/10)
D/PointerIcon( 2413): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2413): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2413): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2413): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2413): Skipping PackageSetting{4275b6e0 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2413): setPackageStoppedState - Execution time: 124 ms
D/PackageManager( 2413): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10633, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6771): GC_EXPLICIT freed 160K, 30% free 9960K/14036K, paused 3ms+4ms, total 40ms
,D/dalvikvm( 6425): GC_EXPLICIT freed 2494K, 29% free 9886K/13816K, paused 3ms+4ms, total 47ms
,I/DBG_DM  ( 4736): [3.19.140541][Line:408][onResume] 
,E/SamsungIME( 2954): mOCRHelper is null
,I/DBG_DM  ( 4736): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,D/QuickConnect[1.1][2] ( 5137): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
D/PackageManager( 2413): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10633, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 2996): GC_EXPLICIT freed 1472K, 28% free 10035K/13812K, paused 12ms+7ms, total 105ms
,I/DBG_DM  ( 4736): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 7554): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7554):  
I/DBG_DM  ( 4736): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4736): [3.19.140541][Line:418][onResume] Postpone Count : 30
I/DBG_DM  ( 4736): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2413):   Scheme: "sms"
,I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/InputReader( 2413): Reconfiguring input devices.  changes=0x00000010
I/SELinux ( 7554): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7554):  
I/SELinux ( 7554):  
I/SELinux ( 7554): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/DBG_DM  ( 4736): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
E/SELinux ( 7554): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7554): >>>>> Normal User
E/dalvikvm( 7554): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux ( 7554): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/FPMS_FingerprintManagerService( 2600): onReceive: android.intent.action.PACKAGE_REMOVED
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "smsto"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mms"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7554): in addTimaSignatureService
,I/DBG_DM  ( 4736): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/TimaKeyStoreProvider( 7554): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7554): Added TimaKesytore provider
,D/dalvikvm( 3443): GC_EXPLICIT freed 1734K, 21% free 12417K/15636K, paused 12ms+92ms, total 271ms
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mmsto"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4736): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 30
,I/DBG_DM  ( 4736): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
D/RegisteredServicesCache( 2757): empty dynamic service
I/DBG_DM  ( 4736): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
I/DBG_DM  ( 4736): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/dalvikvm( 2413): GC_EXPLICIT freed 3536K, 75% free 25079K/97764K, paused 22ms+20ms, total 294ms
D/dalvikvm( 2413): WAIT_FOR_CONCURRENT_GC blocked 74ms
D/checkbox( 4736): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4736): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4736): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "sms"
,D/Activity( 4736): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/StatusBarManagerService( 2413): semi p:4736,o:t
I/DBG_DM  ( 4736): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1922): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2413): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2413): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2413): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2413): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2413): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2413): setHoveringSpenCustomIcon IconType is same.1
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "smsto"
,D/RCPManagerService( 2413): PackageReceiver onReceive()
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/HarmonyEASService( 2413): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mms"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mmsto"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ContextImpl( 2413): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2413): Got RemoteException sending setActive(false) notification to pid 7208 uid 10633
,D/CustomFrequencyManagerService( 2413): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  tag : ACTIVITY_RESUME_BOOSTER@4
,D/dalvikvm( 7554): GC_CONCURRENT freed 2993K, 31% free 9577K/13816K, paused 4ms+2ms, total 41ms
,D/dalvikvm( 7554): WAIT_FOR_CONCURRENT_GC blocked 28ms
W/ActivityManager( 2413): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2413): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/EnterpriseDeviceManagerService( 2413): Package has changed for user 0
,D/elm:14132( 7554): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7554): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7554): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7554): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7554): ElmAgentService : onCreate()
D/dalvikvm( 2757): GC_CONCURRENT freed 1209K, 28% free 10618K/14708K, paused 25ms+4ms, total 105ms
,D/dalvikvm( 2757): WAIT_FOR_CONCURRENT_GC blocked 75ms
,I/SELinux ( 7569): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7569):  
D/elm:14132( 7554): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7554): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7554): MDMBridge.getInstance()
,D/elm:14132( 7554): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7554): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7554): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
I/SELinux ( 7569): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7569):  
I/SELinux ( 7569):  
,I/SELinux ( 7569): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7569): >>>>> Normal User
,E/dalvikvm( 7569): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,D/elm:14132( 7554): ElmAgentService : onDestroy().
,E/SELinux ( 7569): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2413): Killing 6551:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7569): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7569): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7569): Added TimaKesytore provider
,D/dalvikvm( 2413): GC_EXPLICIT freed 832K, 75% free 25029K/97764K, paused 9ms+32ms, total 348ms
D/PackageManager( 2413): delete sourFile : 
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 2413): delete native library directory: 
D/PackageManager( 2413): return delete result to caller: 1117423568
,D/AndroidRuntime( 7542): Shutting down VM
D/PackageManager( 2413): returnCode: 1
,D/dalvikvm( 7542): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 4ms
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "sms"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7569): GC_CONCURRENT freed 2997K, 31% free 9569K/13808K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7569): WAIT_FOR_CONCURRENT_GC blocked 17ms
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "smsto"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/BackupManagerService( 2413): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2413): removePackageParticipantsLocked: uid=10633 #1
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mms"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2413):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2413):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2413):   Scheme: "mmsto"
I/PackageManager( 2413): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/ContextImpl( 2413): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2413): sendNotification(2) - 4
,I/SELinux ( 7584): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7584):  
I/ActivityManager( 2413): Killing 6445:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux ( 7584): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7584):  
I/SELinux ( 7584):  
,I/SELinux ( 7584): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7584): >>>>> Normal User
,E/dalvikvm( 7584): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7584): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7584): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7584): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7584): Added TimaKesytore provider,
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7584): GC_CONCURRENT freed 3001K, 31% free 9568K/13812K, paused 4ms+1ms, total 34ms
,D/dalvikvm( 7584): WAIT_FOR_CONCURRENT_GC blocked 29ms
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteDatabase( 7584): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 7584): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7584): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7584): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7584): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7584): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7584): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7584): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 7584): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 7584): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7584): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7584): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7584): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7584): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7584): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7584): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7584): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7584): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7584): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7584): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7584): Shutting down VM
W/dalvikvm( 7584): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7584): FATAL EXCEPTION: main
E/AndroidRuntime( 7584): Process: com.sec.android.app.mss, PID: 7584
E/AndroidRuntime( 7584): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7584): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7584): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7584): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7584): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7584): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7584): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7584): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7584): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7584): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7584): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7584): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7584): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7584): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7584): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7584): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7584): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7584): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 7584): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 7584): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7584): 	... 10 more
I/PowerManagerService( 2413): [PWL] Off : 225s ago
I/PCWCLIENTTRACE_PushUtil( 6610): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6610): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6610): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6610): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/Process ( 7584): Sending signal. PID: 7584 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SA      ( 5804): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
I/SA      ( 5804): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
I/ActivityManager( 2413): Process com.sec.android.app.mss (pid 7584) (adj 9) has died.
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ApplicationsProvider( 2996): Could not fetch usage stats
W/ApplicationsProvider( 2996): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2996): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2996): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2996): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2996): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2996): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2996): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2996): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2996): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2996): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2996): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SharedPreferencesImpl( 3381): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2413): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/CrashAnrDetector( 2413): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2413): clearDefaults: com.test.thalitest
,I/Icing.InternalIcingCorporaProvider( 6425): Updating corpora: A: com.test.thalitest, C: MAYBE
,E/SQLiteLog( 6425): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6425): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,W/AtomicFile( 2413): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,E/SQLiteLog( 6001): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6001): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
W/AppWidgetServiceImpl( 2413): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,E/AndroidRuntime( 6425): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6425): Process: com.google.android.googlequicksearchbox:search, PID: 6425
E/AndroidRuntime( 6425): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6425): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6425): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6425): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6425): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6425): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6425): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6425): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7606): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7606):  
E/AndroidRuntime( 6001): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6001): Process: com.sec.android.app.shealth, PID: 6001
E/AndroidRuntime( 6001): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6001): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6001): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6001): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6001): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6001): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6001): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6001): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6001): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6001): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6001): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6001): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6001): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6001): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6001): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6001): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6001): Sending signal. PID: 6001 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/Process ( 6425): Sending signal. PID: 6425 SIG: 9
,I/ActivityManager( 2413): Process com.sec.android.app.shealth (pid 6001) (adj 5) has died.
D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 12% free 9503K/10788K, paused 2ms+3ms, total 35ms
I/SELinux ( 7606): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7606):  
I/SELinux ( 7606):  
I/SELinux ( 7606): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7606): >>>>> Normal User
E/dalvikvm( 7606): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7606): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2413): Process com.google.android.googlequicksearchbox:search (pid 6425) (adj 5) has died.
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 2ms+3ms, total 25ms
,D/TimaKeyStoreProvider( 7606): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7606): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7606): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 3ms+3ms, total 27ms
,D/dalvikvm( 7606): GC_CONCURRENT freed 2998K, 31% free 9570K/13812K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7606): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/UserAnalysis.PlaceProvider( 7606): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7606): Create SecureDbHelper
,E/SQLiteDatabase( 7606): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7606): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7606): Opened privacy in read-only mode
,E/SQLiteDatabase( 7606): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7606): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7606): Opened privacy in read-only mode
E/SQLiteDatabase( 7606): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7606): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7606): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7606): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7606): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7606): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7606): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7606): 	at a,ndroid.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7606): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7606): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7606): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7606): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7606): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7606): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7606): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7606): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7606): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 7606): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6360): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6439):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2413):  in createShortcut() for packageName: com.test.thalitest userId0
,D/RCPManagerService( 2413): queryAllProviders():  providerCallBack is not register for 0
,D/CapabilityManagerService New( 6680): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
,D/CapabilityManagerService New( 6680): The package(com.test.thalitest) removed
,W/System.err( 2413): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
,E/SQLiteDatabase( 6360): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6360): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6360): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6360): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6360): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6360): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6360): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6360): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6360): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6360): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/System.err( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
,W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2413): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
,W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2413): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2413): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
,D/CustomFrequencyManagerService( 2413): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2413  tag : ACTIVITY_RESUME_BOOSTER@8
W/System.err( 6360): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 2413): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2413): 	... 8 more
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6360): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6360): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6360): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6360): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6360): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6360): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6360): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6360): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6360): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6360): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6360): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6360): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2413): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 6360): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2413): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2413): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2413): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2413): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2413): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2413): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6706): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6706): [onHandleIntent] ACTION_PACKAGE_REMOVED
,I/SELinux ( 7622): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7622):  
E/SQLiteDatabase( 6706): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6706): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6706): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6706): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6706): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6706): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6706): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6706): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6706): threadid=10: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 6706): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6706): Process: com.samsung.android.magazine.service, PID: 6706
E/AndroidRuntime( 6706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/AndroidRuntime( 6706): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6706): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6706): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6706): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6706): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6706): 	at android.os.Looper.loop(Looper.java:146),
E/AndroidRuntime( 6706): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2413): Can't write: system_app_crash,
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
I/Process ( 6706): Sending signal. PID: 6706 SIG: 9
,I/ActivityManager( 2413): Process com.samsung.android.magazine.service (pid 6706) (adj 5) has died.,
I/SA      ( 5804): [RC New] [v2liruge] api execute + 6509
,I/SA      ( 5804): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
E/SPPClientService( 5539): [b] __InitReply__
,I/System.out( 5804): AsyncTask #2 calls detatch()
,I/SA      ( 5804): [TPMU] getNetworkMcc : 
I/SELinux ( 7622): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7622):  
I/SELinux ( 7622):  
,I/SELinux ( 7622): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7622): >>>>> Normal User
,E/dalvikvm( 7622): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7622): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/SQLiteDatabase( 5539): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.d.l(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.e(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5539): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5539): [d] [getAllUserSN()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
I/SA      ( 5804): [SCU] saveMccToPreferece Start
I/SA      ( 5804): [SCU] RegionMCC : 260
,I/SA      ( 5804): [SSP] query invoked
,I/SA      ( 5804): [TPMU] GetMccFromDB : null
,I/SA      ( 5804): [SCU] getMccFromPreferece mcc = 260
,D/TimaKeyStoreProvider( 7622): in addTimaSignatureService
,I/SA      ( 5804): [SCU] saveMccToPreferece End
,I/SA      ( 5804): [RC New] executeRequest [v2liruge] end. 6542
,I/SA      ( 5804): [RC New] Execute end
I/SA      ( 5804): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5804): [OR] GetMyCountryZoneTask Success
,D/TimaKeyStoreProvider( 7622): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7622): Added TimaKesytore provider
,E/SQLiteDatabase( 5539): Failed to open database '/data/data/com.sec.spp.push/databases/log_data_db'.
E/SQLiteDatabase( 5539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.c.c.<init>(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.c.c.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.i(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.log.collector.PushClientLogCollectService.onHandleIntent(Unknown Source)
E/SQLiteDatabase( 5539): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 5539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5539): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5539): [[SPPLogCollecter]] null
,E/SQLiteDatabase( 5539): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.d.l(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.util.b.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.f.a.g.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.f.a.h.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5539): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5539): [d] [getAllUserSN()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 5539): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.d.m(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.f.a.g.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.f.a.h.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.i(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.d(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.e.a.c.handleMessage(Unknown Source)
E/SQLiteDatabase( 5539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5539): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SPPClientService( 5539): [d] [DeReg] not an error (code 0): Could not open the database in read/write mode.
,D/dalvikvm( 7622): GC_CONCURRENT freed 2996K, 31% free 9566K/13808K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7622): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/ContextImpl( 7622): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6732): onReceive intent data =  package:com.test.thalitest
E/SQLiteDatabase( 7622): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7622): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7622): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7622): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7622): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsPlatformStub( 6732): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7622): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7622): Process: com.android.keychain, PID: 7622
E/AndroidRuntime( 7622): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7622): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7622): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7622): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7622): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7622): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7622): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7622): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7622): Sending signal. PID: 7622 SIG: 9
,E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
W/System.err( 6771): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6771): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6771): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6771): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6771): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6771): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6771): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6771): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6771): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6771): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6771): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6771): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6771): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6771): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3443): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3443): Clearing selected account for com.test.thalitest
I/ActivityManager( 2413): Process com.android.keychain (pid 7622) (adj 5) has died.
,D/ChimeraCfgMgr( 3443): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3443): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 3443): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3443): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3443): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 3443): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteLog( 3443): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 3443): threadid=47: thread exiting with uncaught exception (group=0x4180ac08)
,E/DriveAsyncService( 3443): disk I/O error (code 3850)
E/DriveAsyncService( 3443): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3443): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3443): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3443): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3443): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3443): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3443): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3443): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3443): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3443): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3443): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 2853): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2853): Shutting down VM
,W/dalvikvm( 2853): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3443): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3443): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3443): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3443): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3443): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3443): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3443): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 3443): FATAL EXCEPTION: PlayGamesAsyncThread2
E/AndroidRuntime( 3443): Process: com.google.android.gms, PID: 3443
E/AndroidRuntime( 3443): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 3443): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/AndroidRuntime( 3443): 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
E/AndroidRuntime( 3443): 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
E/AndroidRuntime( 3443): 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
E/AndroidRuntime( 3443): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 3443): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 3443): 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3146)
E/AndroidRuntime( 3443): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperatio,n.java:26)
E/AndroidRuntime( 3443): 	at com.google.android.gms.games.service.operations.GamesOperationAdapter.execute(GamesOperationAdapter.java:23)
E/AndroidRuntime( 3443): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/AndroidRuntime( 3443): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/AndroidRuntime( 3443): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/AndroidRuntime( 3443): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 2853): FATAL EXCEPTION: main
E/AndroidRuntime( 2853): Process: com.google.process.gapps, PID: 2853
E/AndroidRuntime( 2853): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2853): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2853): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2853): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2853): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2853): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2853): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2853): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2853): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2853): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2853): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2853): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2853): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2853): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2853): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2853): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2853): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2853): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2853): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2853): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2853): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2853): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2853): 	... 10 more
E/SQLiteOpenHelper( 3443): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3443): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3443): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3443): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3443): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQ,LiteOpenHelper( 3443): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3443): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3443): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3443): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3443): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3443): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3443): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3443): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
W/SQLiteOpenHelper( 3443): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3443): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3443): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 3443): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3443): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3443): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3443): threadid=48: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3443): Sending signal. PID: 3443 SIG: 9
,I/Process ( 2853): Sending signal. PID: 2853 SIG: 9
,E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
E/SQLiteDatabase( 5539): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5539): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5539): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5539): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5539): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5539): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5539): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5539): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5539): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5539): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5539): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5539): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5539): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5539): 	at dalvik.system.NativeStart.main(Native Method)
E/SPPClientService( 5539): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/wri,te mode.
,E/SQLiteDatabase( 6402): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6402): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6402): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6402): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6402): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6402): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6402): [g] not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5627): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,E/SQLiteDatabase( 6402): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6402): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6402): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6402): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6402): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6402): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6402): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6402): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6402): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6402): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6402): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6402): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6402): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7651): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7651):  
I/ActivityManager( 2413): Process com.google.android.gms (pid 3443) (adj 5) has died.
,I/GAV2    ( 5627): Thread[main,5,main]: Unexpected disconnect.
I/ActivityManager( 2413): Process com.google.process.gapps (pid 2853) (adj 5) has died.
,I/SELinux ( 7651): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7651):  
I/SELinux ( 7651):  
,I/SELinux ( 7651): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7651): >>>>> Normal User
,E/dalvikvm( 7651): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7651): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7651): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7651): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7651): Added TimaKesytore provider
,D/dalvikvm( 7651): GC_CONCURRENT freed 3001K, 31% free 9572K/13816K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7651): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Documents( 7651): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7651): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7651): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7651): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7651): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7651): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7651): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7651): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7651): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7651): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7651): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7651): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7651): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7651): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7651): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7651): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7651): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7651): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7651): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7651): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7651): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7651): Shutting down VM
,W/dalvikvm( 7651): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7651): FATAL EXCEPTION: main
E/AndroidRuntime( 7651): Process: com.android.documentsui, PID: 7651
E/AndroidRuntime( 7651): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7651): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7651): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7651): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7651): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7651): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7651): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7651): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7651): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7651): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7651): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7651): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7651): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7651): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7651): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7651): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7651): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7651): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7651): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7651): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7651): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7651): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7651): 	... 10 more
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,I/SELinux ( 7669): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7669):  
,I/Process ( 7651): Sending signal. PID: 7651 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/ActivityManager( 2413): Process com.android.documentsui (pid 7651) (adj 9) has died.
,I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7669): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7669):  
I/SELinux ( 7669):  
,I/SELinux ( 7669): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7669): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7669): >>>>> Normal User
,E/dalvikvm( 7669): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
,E/SELinux ( 7669): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7665): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7669): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7669): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7669): Added TimaKesytore provider
,D/dalvikvm( 7665): GC_CONCURRENT freed 2998K, 31% free 9566K/13808K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/ExternalStorage( 7665): After updating volumes, found 1 active roots
,D/dalvikvm( 7669): GC_CONCURRENT freed 2946K, 31% free 9621K/13812K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7669): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 7669): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7669): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7669): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7669): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7669): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7669): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7669): install
,I/MultiDex( 7669): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7669): loading existing secondary dex files
,I/MultiDex( 7669): load found 3 secondary dex files
,I/MultiDex( 7669): install done
,I/SELinux ( 7691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7691):  
,I/SELinux ( 7691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7691):  
I/SELinux ( 7691):  
,I/SELinux ( 7691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7691): >>>>> Normal User
,E/dalvikvm( 7691): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7691): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7691): Added TimaKesytore provider
,D/dalvikvm( 7691): GC_CONCURRENT freed 2988K, 31% free 9580K/13812K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7691): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Icing.InternalIcingCorporaProvider( 7691): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7709): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7709):  
,I/SELinux ( 7713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7713):  
,D/LocationManagerService( 2413): getProviders()=[passive]
,I/SELinux ( 7709): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7709):  
I/SELinux ( 7709):  
,I/SELinux ( 7709): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7709): >>>>> Normal User
,E/dalvikvm( 7709): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7709): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7713):  
I/SELinux ( 7713):  
,I/SELinux ( 7713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7713): >>>>> Normal User
,E/dalvikvm( 7713): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,D/TimaKeyStoreProvider( 7709): in addTimaSignatureService
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7709): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7709): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7713): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7713): Added TimaKesytore provider
,D/dalvikvm( 7709): GC_CONCURRENT freed 3003K, 31% free 9568K/13816K, paused 3ms+3ms, total 24ms
,D/dalvikvm( 7709): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/dalvikvm( 7713): GC_CONCURRENT freed 2989K, 31% free 9582K/13816K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7713): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7713): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7713): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7713): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7713): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7713): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7713): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7713): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7713): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7713): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7713): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7713): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7713): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7713): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7713): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7713): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7713): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7713): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7713): Shutting down VM
,W/dalvikvm( 7713): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7713): FATAL EXCEPTION: main
E/AndroidRuntime( 7713): Process: com.google.process.gapps, PID: 7713
E/AndroidRuntime( 7713): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7713): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7713): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7713): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7713): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7713): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7713): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7713): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7713): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7713): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7713): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7713): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7713): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7713): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7713): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7713): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7713): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7713): 	... 12 more
,I/Process ( 7713): Sending signal. PID: 7713 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/ActivityManager( 2413): Process com.google.process.gapps (pid 7713) (adj 0) has died.
,W/ActivityManager( 2413): Service crashed 2 times, stopping: ServiceRecord{43263b88 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7741): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7741):  
,I/SELinux ( 7741): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7741):  
I/SELinux ( 7741):  
,I/SELinux ( 7741): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7741): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7741): >>>>> Normal User
,E/dalvikvm( 7741): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7741): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7741): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7741): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7741): Added TimaKesytore provider
,D/dalvikvm( 7741): GC_CONCURRENT freed 2993K, 31% free 9572K/13812K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7741): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7741): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7741): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7741): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7741): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7741): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7741): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7741): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7741): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7741): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7741): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7741): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7741): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7741): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7741): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7741): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7741): Shutting down VM
,W/dalvikvm( 7741): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7741): FATAL EXCEPTION: main
E/AndroidRuntime( 7741): Process: com.google.process.gapps, PID: 7741
E/AndroidRuntime( 7741): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7741): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7741): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7741): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7741): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7741): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7741): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7741): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7741): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7741): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7741): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7741): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7741): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7741): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7741): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7741): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7741): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7741): 	... 12 more
W/ActivityManager( 2413): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2413): Killing 7741:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /d,ata/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7691): Failed to find provider info for com.google.settings
E/ActivityThread( 7709): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7669): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7757): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7757):  
,I/SELinux ( 7757): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7757):  
I/SELinux ( 7757):  
,I/SELinux ( 7757): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7757): >>>>> Normal User
,E/dalvikvm( 7757): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7757): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7757): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7757): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7757): Added TimaKesytore provider
,D/dalvikvm( 7757): GC_CONCURRENT freed 2997K, 31% free 9572K/13816K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7757): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7757): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7757): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7757): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7757): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7757): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7757): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7757): Shutting down VM
,W/dalvikvm( 7757): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7757): FATAL EXCEPTION: main
E/AndroidRuntime( 7757): Process: com.google.process.gapps, PID: 7757
E/AndroidRuntime( 7757): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7757): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7757): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7757): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7757): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7757): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7757): 	... 12 more
,I/Process ( 7757): Sending signal. PID: 7757 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/ActivityManager( 2413): Process com.google.process.gapps (pid 7757) (adj 0) has died.
,I/SELinux ( 7772): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7772):  
,I/SELinux ( 7772): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7772):  
I/SELinux ( 7772):  
,I/SELinux ( 7772): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7772): >>>>> Normal User
,E/dalvikvm( 7772): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7772): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7772): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7772): Added TimaKesytore provider
,D/dalvikvm( 7772): GC_CONCURRENT freed 3001K, 31% free 9572K/13816K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7772): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7772): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7772): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7772): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7772): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7772): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7772): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7772): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7772): Shutting down VM
,W/dalvikvm( 7772): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7772): FATAL EXCEPTION: main
E/AndroidRuntime( 7772): Process: com.google.process.gapps, PID: 7772
E/AndroidRuntime( 7772): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7772): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7772): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7772): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7772): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7772): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7772): 	... 12 more
W/ActivityManager( 2413): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2413): Killing 7772:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7709): Failed to find provider info for com.google.android.gsf.gservices
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,E/ActivityThread( 7669): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7669): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7669): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7669): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7669): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7669): VFY: unable to resolve instance field 36
D/dalvikvm( 7669): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7669): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7669): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7669): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7669): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7669): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7669): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42280b18
D/dalvikvm( 7669): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42280b18
D/dalvikvm( 7669): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42280b18, skipping init
D/dalvikvm( 7669): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42280b18
D/dalvikvm( 7669): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42280b18
V/JNIHelp ( 7669): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7669): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42280b18
,D/dalvikvm( 7669): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42280b18
D/dalvikvm( 7669): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42280b18
,D/dalvikvm( 7669): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42280b18
,I/ProviderInstaller( 7669): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7787):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 44K, 12% free 9503K/10788K, paused 2ms+2ms, total 27ms
,I/SELinux ( 7787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7787):  
I/SELinux ( 7787):  
,I/SELinux ( 7787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7787): >>>>> Normal User
,E/dalvikvm( 7787): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 2ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7787): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7787): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7787): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 12% free 9503K/10788K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 7787): GC_CONCURRENT freed 2981K, 31% free 9579K/13808K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7787): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7787): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7787): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7787): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7787): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7787): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7787): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7787): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7787): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7787): Shutting down VM
,W/dalvikvm( 7787): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7787): FATAL EXCEPTION: main
E/AndroidRuntime( 7787): Process: com.google.process.gapps, PID: 7787
E/AndroidRuntime( 7787): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7787): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7787): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7787): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7787): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7787): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7787): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7787): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7787): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7787): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7787): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7787): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7787): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7787): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7787): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7787): 	... 12 more
,I/Process ( 7787): Sending signal. PID: 7787 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/ActivityManager( 2413): Process com.google.process.gapps (pid 7787) (adj 0) has died.
,I/SELinux ( 7802): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7802):  
,I/SELinux ( 7802): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7802):  
I/SELinux ( 7802):  
,I/SELinux ( 7802): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7802): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7802): >>>>> Normal User
,E/dalvikvm( 7802): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7802): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7802): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7802): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7802): Added TimaKesytore provider
,W/dalvikvm( 2996): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2996): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2996): Process: android.process.acore, PID: 2996
E/AndroidRuntime( 2996): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2996): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2996): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2996): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2996): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2996): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2996): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2996): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2996): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2996): Sending signal. PID: 2996 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/ActivityManager( 2413): Process android.process.acore (pid 2996) (adj -12) has died.
,I/SELinux ( 7815): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7815):  
D/dalvikvm( 7802): GC_CONCURRENT freed 3000K, 31% free 9569K/13816K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7802): WAIT_FOR_CONCURRENT_GC blocked 18ms,
,I/SELinux ( 7815): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7815):  
I/SELinux ( 7815):  
,I/SELinux ( 7815): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7815): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7815): >>>>> Normal User
,E/dalvikvm( 7815): >>>>> android.process.acore [ userId:0 | appId:10020 ],
,E/SELinux ( 7815): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,I/GservicesProvider( 7802): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7802): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7802): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7802): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/SQLiteDatabase( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7802): 	,at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7802): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7802): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7802): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7802): 	at java.lang.reflect.Method.invoke(Method.java:515),
E/SQLiteDatabase( 7802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7802): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7802): Shutting down VM
W/dalvikvm( 7802): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7802): FATAL EXCEPTION: main,
E/AndroidRuntime( 7802): Process: com.google.process.gapps, PID: 7802
E/AndroidRuntime( 7802): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7802): 	,at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7802): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7802): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7802): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7802): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7802): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7802): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7802): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7802): ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7802): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7802): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7802): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7802): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7802): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7802): 	,at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7802): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7802): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7802): 	... 12 more
D/TimaKeyStoreProvider( 7815): in addTimaSignatureService
W/ActivityManager( 2413): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2413): Killing 7802:com.google.process.gapps/u0a12 (adj 0): crash,
W/ActivityManager( 2413): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
D/TimaKeyStoreProvider( 7815): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7815): Added TimaKesytore provider,
E/ActivityThread( 7669): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2413): Can't write: system_app_crash,
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
,E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
W/NativeLibraryUtils( 7669): Failed to open lock file
W/NativeLibraryUtils( 7669): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7669): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7669): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7669): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7669): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7669): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7669): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7669): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7669): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7669): 	... 3 more
,I/dalvikvm( 7669): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
,W/dalvikvm( 7669): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7669): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7834): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7834):  
,D/dalvikvm( 7815): GC_CONCURRENT freed 2994K, 31% free 9577K/13816K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7815): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/SELinux ( 7834): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7834):  
I/SELinux ( 7834):  
,I/SELinux ( 7834): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7834): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7834): >>>>> Normal User
,E/dalvikvm( 7834): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7834): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7834): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7834): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7834): Added TimaKesytore provider,
,D/dalvikvm( 7834): GC_CONCURRENT freed 2998K, 31% free 9573K/13812K, paused 2ms+2ms, total 18ms,
,D/dalvikvm( 7834): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SQLiteDatabase( 7815): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7815): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7815): 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7815): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7815): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7815): 	at com.and,roid.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7815): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteOpenHelper( 7815): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7815): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7815): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7815): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7815): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7815): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7815): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7815): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7815): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7815): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7815): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
E/SQLiteLog( 7815): (14) unable to open database file
E/SQLiteDatabase( 7815): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7815): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7815): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7815): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 7815): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7815): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7815): Process: android.process.acore, PID: 7815
E/AndroidRuntime( 7815): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7815): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7815): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7815): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7815): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7815): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7815): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7815): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7815): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 7815): Sending signal. PID: 7815 SIG: 9
W/ActivityManager( 2413): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
I/ActivityManager( 2413): Process android.process.acore (pid 7815) (adj -12) has died.
,F/ActivityManager( 2413): Service ServiceRecord{46ecf268 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42cc7540 7815:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2413): Can't write: system_server_wtf
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop17.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2413): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2413): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2413): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2413): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2413): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2413): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 18 more
,I/SELinux ( 7852): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7852):  
,I/GservicesProvider( 7834): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7834): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7834): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7834): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7834): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7834): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7834): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7834): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7834): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7834): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7834): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7834): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7834): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7834): Shutting down VM
,W/dalvikvm( 7834): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7834): FATAL EXCEPTION: main
E/AndroidRuntime( 7834): Process: com.google.process.gapps, PID: 7834
E/AndroidRuntime( 7834): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7834): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7834): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7834): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7834): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7834): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7834): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7834): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7834): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7834): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7834): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7834): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7834): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7834): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7834): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7834): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7834): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7834): 	... 12 more
,I/Process ( 7834): Sending signal. PID: 7834 SIG: 9
E/DropBoxManagerService( 2413): Can't write: system_app_crash
E/DropBoxManagerService( 2413): java.io.FileNotFoundException: /data/system/dropbox/drop236.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2413): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2413): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2413): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2413): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2413): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2413): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2413): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2413): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2413): 	... 5 more
,I/SELinux ( 7852): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7852):  
I/SELinux ( 7852):  
,I/SELinux ( 7852): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7852): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7852): >>>>> Normal User
E/dalvikvm( 7852): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7852): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/ActivityManager( 2413): Process com.google.process.gapps (pid 7834) (adj 0) has died.
,I/SELinux ( 7866): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7866):  
,D/TimaKeyStoreProvider( 7852): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7852): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7852): Added TimaKesytore provider
,D/PreloadUpdateManagerStateMachine( 5956): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5956): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5956): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5956): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5956): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5956): exit::CHECK_TIMEOUT_FOR_UPDATE
D/PreloadUpdateManagerStateMachine( 5956): entry::IDLE
I/SELinux ( 7866): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7866):  
I/SELinux ( 7866):  
,I/SELinux ( 7866): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7866): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7866): >>>>> Normal User
,E/dalvikvm( 7866): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7866): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7866): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7866): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7866): Added TimaKesytore provider
D/dalvikvm( 7852): GC_CONCURRENT freed 2995K, 31% free 9577K/13816K, paused 3ms+2ms, total 20ms
,D/dalvikvm( 7852): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/CaptivePortalTracker( 2413): DelayedCaptiveCheckState{ when=-6ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2413): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2413): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/dalvikvm( 7866): GC_CONCURRENT freed 2988K, 31% free 9583K/13816K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7866): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/GservicesProvider( 7866): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7852): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7852): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7852): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteDatabase( 7866): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7866): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7866): 	at com.google.android.gsf.gser,vices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7866): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7866): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7866): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7866): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7866): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7866): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7866): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7866): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7866): Shutting down VM
W/dalvikvm( 7866): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/SQLiteOpenHelper( 7852): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7852): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7852): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7852): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7852): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7852): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7852): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7852): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7852): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7852): 	at android.os.HandlerThread.,run(HandlerThread.java:61)
E/SQLiteLog( 7852): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7852): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
E/SQLiteLog( 7852): (14) unable to open database file
E/SQLiteDatabase( 7852): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7852): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7852): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7852): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7852): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7852): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 7852): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7866): FATAL EXCEPTION: main
E/AndroidRuntime( 7866): Process: com.google.process.gapps, PID: 7866
E/AndroidRuntime( 7866): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7866): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7866): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7866): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7866): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7866): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7866): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7866): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7866): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7866): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7866): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7866): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7866): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7866): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7866): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7866): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7866): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7866): 	... 12 more

```
