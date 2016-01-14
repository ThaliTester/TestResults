#### Test 55613145c131883_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/SSRMv2:SIOP( 2411): SIOP:: AP = 320, Delta = 0
D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): stay LED for fully charged
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
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
E/memtrack( 7214): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7214): failed to load memtrack module: -2
D/dalvikvm( 7214): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7214): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2411): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.acquire()
I/SELinux ( 7226): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7226):  
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7214): Shutting down VM
D/dalvikvm( 7214): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7226): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7226):  
I/SELinux ( 7226):  
I/SELinux ( 7226): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7226): >>>>> Normal User
E/dalvikvm( 7226): >>>>> com.test.thalitest [ userId:0 | appId:10622 ]
E/SELinux ( 7226): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7226): in addTimaSignatureService
D/TimaKeyStoreProvider( 7226): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7226): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4162): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4162): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7226): GC_CONCURRENT freed 3005K, 32% free 9566K/13944K, paused 1ms+1ms, total 17ms
D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7226): Binding Chromium to the background looper Looper (main, tid 1) {422a81b8}
I/chromium( 7226): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7226): Initializing chromium process, renderers=0
W/chromium( 7226): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7226): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7226): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7226): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7226): Mali API Version : 401
,I/Mali    ( 7226): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7226): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7226): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7226): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7226): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7226): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7226): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2411): tr p:7226,o:f
,W/dalvikvm( 7226): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7226): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7226): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7226): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7226): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7226): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7226): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7226): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7226): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7226): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7226): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7226): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7226): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2411): semi p:7226,o:f
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7226): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7226): Enabling debug mode 0
,W/AwContents( 7226): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7226): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7226): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7226): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a0098
,D/dalvikvm( 7226): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422a0098
D/jxcore_app_log( 7226): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027614288
,D/JX-Cordova( 7226): jxcore cordova android initializing
,D/dalvikvm( 7226): GC_CONCURRENT freed 1277K, 19% free 11362K/14008K, paused 3ms+5ms, total 34ms
,D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/dalvikvm( 7226): GC_CONCURRENT freed 1947K, 19% free 14961K/18296K, paused 3ms+2ms, total 45ms
,D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7226): GC_FOR_ALLOC freed 5292K, 30% free 16236K/23160K, paused 50ms, total 50ms
,D/dalvikvm( 7226): GC_CONCURRENT freed 6708K, 32% free 17697K/25796K, paused 2ms+9ms, total 54ms
,D/dalvikvm( 7226): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 7226): GC_FOR_ALLOC freed 1124K, 32% free 17622K/25796K, paused 48ms, total 48ms
,I/dalvikvm-heap( 7226): Grow heap (frag case) to 22.061MB for 3688532-byte allocation
,D/dalvikvm( 7226): GC_FOR_ALLOC freed 2455K, 37% free 18769K/29400K, paused 41ms, total 41ms
,W/jxcore-log( 7226): Initializing JXcore engine
,W/jxcore-log( 7226): JXcore engine is ready
,W/jxcore-log( 7226): Starting JXcore engine
,W/jxcore-log( 7226): Platform android
W/jxcore-log( 7226): 
,W/jxcore-log( 7226): Process ARCH arm
W/jxcore-log( 7226): 
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/jxcore-log( 7226): JXcore Cordova bridge is ready!
I/jxcore-log( 7226): 
,W/jxcore-log( 7226): JXcore engine is started
,I/chromium( 7226): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7226): Toggling radios to true
I/jxcore-log( 7226): 
,D/BluetoothAdapter( 7226): enable(): BT is already enabled..!
,I/WifiManager( 7226): packageName : com.test.thalitest
,I/WifiManager( 7226): setWifiEnabled : true
,I/WifiService( 2411): setWifiEnabled: true pid=7226, uid=10622
,W/ActivityManager( 2411): Permission Denial: getCurrentUser() from pid=7226, uid=10622 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2411): Failed getting userId using ActivityManagerNative
W/WifiService( 2411): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7226, uid=10622 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2411): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2411): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2411): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2411): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2411): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2411): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2411): disconnect: pid=7226, uid=10622
I/jxcore-log( 7226): Radios toggled
I/jxcore-log( 7226): 
I/wpa_supplicant( 3974): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7226): My device name is: samsung-SM-G800F
I/jxcore-log( 7226): 
,I/wpa_supplicant( 3974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3974): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3974): First Scan Start
,W/Settings( 2411): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2411): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3974): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2411): InactiveState{ what=143375 }
D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling
D/ConnectivityService( 2411): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2411): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2411): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
E/ConnectivityService( 2411): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2411): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2411): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
I/wpa_supplicant( 3974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3974): Skip scan - already scanning
,D/WifiP2pService( 2411): InactiveState{ what=143375 }
,D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
D/ConnectivityService( 2411): Attempting to switch to mobile
,D/ConnectivityService( 2411): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 7274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7274):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2411): route cmd failed: 
W/NetworkManagementService( 2411): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2411): '
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2411): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2411): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2411): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2411): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2411): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2411): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1,
,E/WifiStateMachine( 2411): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2411): Error! unhandled message{ when=-86ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling,
I/SELinux ( 7274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7274):  
I/SELinux ( 7274):  
I/SELinux ( 7274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
V/RouteController( 1916): RTNETLINK answers: No such process
E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
E/dalvikvm( 7274): >>>>> Normal User
,E/dalvikvm( 7274): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ],
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2411): Error! unhandled message{ when=-1ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,D/NetUtils( 2411): android_net_utils_resetConnections in env=0x77cdc308 clazz=0x61d00001 iface=wlan0 mask=0x3,
,D/ConnectivityService( 2411): resetConnections(wlan0, 3),
D/TimaKeyStoreProvider( 7274): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7274): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7274): Added TimaKesytore provider,
,E/SPPClientService( 5529): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,V/NativeCrypto( 2857): Read error: ssl=0x7bbefd20: I/O error during system call, Connection timed out,
,E/SPPClientService( 5529): [e] exceptionCaught(). NET_TIMEOUT,
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
V/NetworkStats( 2411): updateIfacesLocked()
V/NetworkStats( 2411): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
V/NetworkStats( 2411): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
,D/dalvikvm( 2411): GC_EXPLICIT freed 27517K, 71% free 25729K/86168K, paused 9ms+21ms, total 339ms,
V/NetworkStats( 2411): performPollLocked() took 88ms
,V/NativeCrypto( 2857): SSL shutdown failed: ssl=0x7bbefd20: I/O error during system call, Broken pipe,
,E/SPPClientService( 5529): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.,
D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit,
D/ConnectivityService( 2411): handleInetConditionChange: no active default network - ignore
,E/SPPClientService( 5529): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5529): [b] ResponseMap empty,
,D/dalvikvm( 7274): GC_CONCURRENT freed 2992K, 32% free 9577K/13940K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 7274): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/System.out( 7274): Inside WakeupProvider,
,I/System.out( 7274): Inside onCreate() of WakeupTriggerProvide,
,I/VlingoApplication( 7274): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS,
D/VlingoApplication( 7274): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7274): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility,
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/DialogFlow( 7274): initQueue(),
I/ActivityManager( 2411): Killing 6156:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null,
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2831): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2831): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2411): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2411): updateDataUsageMap
,D/Tethering( 2411): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2411): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2411): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6636): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6636): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6636): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6636): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6636): noConnectivity : true
,I/DBG_DM  ( 4731): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7301):  
,I/wpa_supplicant( 3974): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3974): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3974): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7301):  
I/SELinux ( 7301):  
,I/SELinux ( 7301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7301): >>>>> Normal User
,E/dalvikvm( 7301): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7301): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7301): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7301): Added TimaKesytore provider
,D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3974): Associated with C0.AA.48
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3974): freq(2412) increment count 2
I/wpa_supplicant( 3974): meet head of list.
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2411): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/dalvikvm( 7301): GC_CONCURRENT freed 2989K, 32% free 9578K/13940K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7301): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3974): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3974): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2411): interfaceLinkStateChanged wlan0, true
D/Tethering( 2411): interfaceStatusChanged wlan0, true
D/WifiNative( 2411): callSECApiVoid - ID [50]
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2411): Killing 6228:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2411): InactiveState{ what=143375 }
,D/WifiP2pService( 2411): P2pEnabledState{ what=143375 }
,I/SELinux ( 7315): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7315):  
,I/SELinux ( 7315): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7315):  
I/SELinux ( 7315):  
,I/SELinux ( 7315): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7315): >>>>> Normal User
,E/dalvikvm( 7315): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7315): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7315): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7315): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7315): Added TimaKesytore provider
,D/dalvikvm( 7315): GC_CONCURRENT freed 2993K, 32% free 9576K/13944K, paused 5ms+2ms, total 29ms
,D/dalvikvm( 7315): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/dhcpcd  ( 7327): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7327): bssid match
,I/ActivityManager( 2411): Killing 6301:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7334): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7334):  
,I/SELinux ( 7334): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7334):  
I/SELinux ( 7334):  
,I/SELinux ( 7334): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7334): >>>>> Normal User
,E/dalvikvm( 7334): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7334): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7334): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7334): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7334): Added TimaKesytore provider
,D/dalvikvm( 7334): GC_CONCURRENT freed 3007K, 32% free 9556K/13936K, paused 3ms+2ms, total 21ms
,D/dalvikvm( 7334): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/KLMS-2.3.201 : ( 7334): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7334): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452774077887
,I/KLMS-2.3.201 : ( 7334): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2411): Killing 6325:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7346): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7346):  
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7346): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7346):  
I/SELinux ( 7346):  
,I/SELinux ( 7346): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7346): >>>>> Normal User
,E/dalvikvm( 7346): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7346): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7346): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7346): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7346): Added TimaKesytore provider
,D/dalvikvm( 7346): GC_CONCURRENT freed 3000K, 32% free 9566K/13936K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7346): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5792): [BDLM] already registered in spp
I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
I/SA      ( 5792): [SCU] == networkStateCheck == false
,I/SA      ( 5792): [OR] onReceive END
I/ActivityManager( 2411): Killing 6367:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SELinux ( 7358): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7358):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9503K/10916K, paused 2ms+3ms, total 30ms
,I/SELinux ( 7358): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7358):  
I/SELinux ( 7358):  
,I/SELinux ( 7358): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7358): >>>>> Normal User
,E/dalvikvm( 7358): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7358): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7358): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7358): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7358): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 2ms+3ms, total 25ms
,D/dalvikvm( 7358): GC_CONCURRENT freed 2998K, 32% free 9578K/13944K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7358): WAIT_FOR_CONCURRENT_GC blocked 13ms
,I/sCloudBackupApp( 7358): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7358): Other Intent
I/ActivityManager( 2411): Killing 5575:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
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
,D/dalvikvm( 7371): GC_CONCURRENT freed 2997K, 32% free 9575K/13944K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7371): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7371): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7371): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5327): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2411): Killing 6278:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5859): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5859): getCountryCode(): countryCode = PL
,D/Headlines( 5859): Breath.onCreate,
,D/Headlines( 5859): Breath timer started. interval : 30000,
,I/SELinux ( 7383): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7383):  
,D/Headlines( 5859): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0,
D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
,D/Headlines( 5859): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5859): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5859): requestUpdateNewsWelcomeCard !!! no welcome card,
V/AlarmManager( 2411): waitForAlarm result :8
,I/SELinux ( 7383): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7383):  
I/SELinux ( 7383):  
,I/SELinux ( 7383): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7383): >>>>> Normal User,
,E/dalvikvm( 7383): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ],
,E/SELinux ( 7383): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7383): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7383): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7383): Added TimaKesytore provider,
,D/dalvikvm( 7383): GC_CONCURRENT freed 2994K, 32% free 9572K/13936K, paused 2ms+1ms, total 34ms
,D/dalvikvm( 7383): WAIT_FOR_CONCURRENT_GC blocked 32ms
,V/WebViewChromium( 7383): Binding Chromium to the background looper Looper (main, tid 1) {422a52d0}
,I/chromium( 7383): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7383): Initializing chromium process, renderers=0
,W/chromium( 7383): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7383): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7383): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7383): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7383): Mali API Version : 401
,I/Mali    ( 7383): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD,
,E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,W/GAV2    ( 7383): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system,
,W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30,
W/ContextImpl( 7383): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 2411): InactiveState{ what=143375 },
,D/WifiP2pService( 2411): P2pEnabledState{ what=143375 },
,D/WifiStateMachine( 2411): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2411): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check,
,D/WifiStateMachine( 2411): CaptivePortalCheckState enter,
,I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling,
,D/WifiStateMachine( 2411): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
D/ConnectivityService( 2411): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2411): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,I/WifiTrafficPoller( 2411): evaluateTrafficStatsPolling,
D/ConnectivityService( 2411): ConnectivityChange for WIFI: CONNECTED/CONNECTED
,E/ConnectivityService( 2411): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2411): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/ConnectivityService( 2411): handleConnectivityChange: setting default proxy info ,
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,I/NSApplication( 7383): Starting up...
,V/NetworkStats( 2411): updateIfacesLocked()
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
V/NetworkStats( 2411): performPollLocked() took 30ms
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2411): currentTimeMillis() cache hit
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5129): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b2f40
,I/SELinux ( 7457): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7457):  
,I/SELinux ( 7457): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7457):  
I/SELinux ( 7457):  
,I/SELinux ( 7457): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7457): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7457): >>>>> Normal User
,E/dalvikvm( 7457): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7457): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7457): in addTimaSignatureService
D/TimaKeyStoreProvider( 7457): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7457): Added TimaKesytore provider
D/dalvikvm( 7457): GC_CONCURRENT freed 2973K, 32% free 9592K/13940K, paused 4ms+2ms, total 27ms
D/dalvikvm( 7457): WAIT_FOR_CONCURRENT_GC blocked 19ms
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
I/SELinux ( 7475): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7475):  
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
D/RCPManagerService( 2411): exchangeData() failure , invalid userId
I/ActivityManager( 2411): Killing 6295:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
W/ActivityManager( 2411): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
I/SELinux ( 7475): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7475):  
I/SELinux ( 7475):  
I/SELinux ( 7475): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7475): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7475): >>>>> Normal User
E/dalvikvm( 7475): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7475): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider( 7475): in addTimaSignatureService
D/TimaKeyStoreProvider( 7475): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7475): Added TimaKesytore provider
I/SELinux ( 7488): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7488):  
I/ActivityManager( 2411): Killing 5967:com.android.calendar/u0a144 (adj 15): empty #43
D/Tethering( 2411): Tethering got CONNECTIVITY_ACTION
D/Tethering( 2411): MasterInitialState.processMessage what=3
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
D/CaptivePortalTracker( 2411): NoActiveNetworkState{ when=-11ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7488): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7488):  
I/SELinux ( 7488):  
I/SELinux ( 7488): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7488): >>>>> Normal User
E/dalvikvm( 7488): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7488): [DEBUG] seapp_context_lookup: seinfoCategory = shared
D/TimaKeyStoreProvider( 7488): in addTimaSignatureService
I/DBG_DM  ( 4731): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
D/TimaKeyStoreProvider( 7488): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7488): Added TimaKesytore provider
D/dalvikvm( 7475): GC_CONCURRENT freed 3001K, 32% free 9566K/13936K, paused 10ms+1ms, total 33ms
D/dalvikvm( 7475): WAIT_FOR_CONCURRENT_GC blocked 20ms
D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection...
D/BadgeProvider( 7475): onCreate
D/BadgeProvider( 7475): DatabaseHelper
D/BadgeProvider( 7475): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/Launcher.Model( 2780): reloadBadges entered.
D/BadgeProvider( 7475): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7475): sendNotify, [notify] : null
D/BadgeProvider( 7475): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7475): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7475): update, [UpdateCount] : 1
D/dalvikvm( 7488): GC_CONCURRENT freed 3006K, 32% free 9566K/13944K, paused 2ms+1ms, total 29ms
D/dalvikvm( 7488): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): entry::SUCCESS
D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5944): exit::SUCCESS
D/InitializeManagerStateMachine( 5944): entry::IDLE
E/SPPClientService( 5529): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
E/SPPClientService( 5529): [SystemStateMoniter] Current Time : 286794
E/SPPClientService( 5529): [SystemStateMoniter] No Connect : true
E/SPPClientService( 5529): [[SystemStateMonitorService]] No Active Internet
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
D/Headlines( 5859): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5859): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
D/Headlines( 5859): Breath 1661 latestRequest time : 1452774078592 current time : 1452774080253
E/SPPClientService( 5529): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5529): [a] [ConnectionManager] Connection is already disconnected.
I/ActivityManager( 2411): Killing 6245:com.android.providers.calendar/u0a45 (adj 15): empty #43
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
E/SPPClientService( 5529): [[PushClientService]] <<--- deInitPushClientService  END  --->>
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2831): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2831): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
E/SPPClientService( 5529): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
D/NearbySettings( 2831): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2831): MountReceiver.onReceive - Keep current state
I/PCWCLIENTTRACE_PushUtil( 6636): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6636): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6636): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6636): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
I/SurfaceFlinger( 1921): id=21 createSurf (1x1),1 flag=4, Uoast
D/SSRMv2:SIOP( 2411): SIOP:: AP = 330, Delta = 10
D/PowerManagerService( 2411): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2411
D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): stay LED for fully charged
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
E/SPPClientService( 5529): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
E/SPPClientService( 5529): [a] [ConnectionManager] Connection is already disconnected.
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
E/SPPClientService( 5529): [g] getNetMCC return empty string
I/KLMS-2.3.201 : ( 7334): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
I/KLMS-2.3.201 : ( 7334): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452774080586
,I/KLMS-2.3.201 : ( 7334): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE,
,I/LocationTagReadyService( 3250): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3250): [Slink platform] The state of Slink geocode service is true
,I/GallerySearchProvider( 3378): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SO_AGENT( 7346): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/SELinux ( 7512): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7512):  
,I/SELinux ( 7512): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7512):  
I/SELinux ( 7512):  
,I/SELinux ( 7512): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7512): >>>>> Normal User
,E/dalvikvm( 7512): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7512): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7512): in addTimaSignatureService
I/SELinux ( 7524): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7524):  
D/TimaKeyStoreProvider( 7512): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7512): Added TimaKesytore provider
,I/SA      ( 5792): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,D/dalvikvm( 2725): GC_EXPLICIT freed 337K, 28% free 10037K/13928K, paused 6ms+6ms, total 93ms
,I/SELinux ( 7524): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7524):  
I/SELinux ( 7524):  
,I/SELinux ( 7524): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7524): >>>>> Normal User
,E/dalvikvm( 7524): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7524): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5792): [BDLM] already registered in spp
,D/TimaKeyStoreProvider( 7524): in addTimaSignatureService
I/SA      ( 5792): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5792): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [OR] == isSIMCardReady false ==
,I/SA      ( 5792): [SCU] == networkStateCheck == true
I/SA      ( 5792): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5792): isChinaCountryCode : false
,I/SA      ( 5792): [OR] == networkStateCheck true ==
,D/dalvikvm( 7512): GC_CONCURRENT freed 2985K, 32% free 9584K/13944K, paused 3ms+1ms, total 26ms
,D/dalvikvm( 7512): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/TimaKeyStoreProvider( 7524): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7524): Added TimaKesytore provider
,I/SA      ( 5792): [OR] GetMyCountryZoneTask
,I/SA      ( 5792): [OR] onReceive END
,I/SA      ( 5792): [SRS] prepareGetMyCountryZone
,I/SA      ( 5792): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5792): [SSP] query invoked
,I/SA      ( 5792): [TPMU] GetMccFromDB : null
I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [TPM] isNoProxy(default) : true
,I/SA      ( 5792): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2754): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7358): Other Intent
,D/dalvikvm( 7524): GC_CONCURRENT freed 3001K, 32% free 9571K/13944K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7524): WAIT_FOR_CONCURRENT_GC blocked 19ms
,V/KVNProvider( 7524): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7524): getFindoCursor query string : 
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/System.out( 7315): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/com.samsung.app( 7371): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5859): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5859): getCountryCode(): countryCode = PL
,D/Headlines( 5859): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5859): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5859): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5859): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5859): requestUpdateNewsWelcomeCard !!! no welcome card
,I/System.out( 7315): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7315): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.Environment( 5923): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5129): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5129): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b2f40
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/RCPManagerService( 2411): exchangeData() failure , invalid userId
,D/libgps  ( 2411): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection...
,D/hcjo    ( 5944): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5944): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5944): exit::IDLE
,D/InitializeManagerStateMachine( 5944): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5944): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5944): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5944): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5944): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5944): entry::SUCCESS
,D/hcjo    ( 5944): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5944): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5944): exit::SUCCESS
,D/InitializeManagerStateMachine( 5944): entry::IDLE
,D/dalvikvm( 2411): GC_EXPLICIT freed 2289K, 71% free 25365K/86168K, paused 9ms+21ms, total 249ms
,V/KVNProvider( 7524): getTagSearchCursor() tagSearchCursor count : 0
E/SPPClientService( 5529): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5529): [SystemStateMoniter] Current Time : 287829
,E/SPPClientService( 5529): [SystemStateMoniter] No Connect : false
,I/System.out( 7315): AsyncTask #1 calls detatch()
,W/System.err( 7315): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7315): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7315): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7315): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7315): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7315): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7315): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7315): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7315): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7315): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7315): Caused by: java.lang.NullPointerException
W/System.err( 7315): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7315): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7315): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7315): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7315): 	... 8 more
,I/ActivityManager( 2411): Killing 6143:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5529): GC_CONCURRENT freed 2000K, 26% free 10445K/13932K, paused 2ms+3ms, total 34ms
,D/dalvikvm( 5529): WAIT_FOR_CONCURRENT_GC blocked 21ms
D/PackageManager( 2411): [MSG] WRITE_PACKAGE_RESTRICTIONS
,E/Watchdog( 2411): !@Sync 9
,I/SA      ( 5792): [RC New] [v2liruge] api execute + 913
,I/SA      ( 5792): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5792): AsyncTask #2 calls detatch()
,I/SA      ( 5792): [TPMU] getNetworkMcc : 
,I/SA      ( 5792): [SCU] saveMccToPreferece Start
,I/SA      ( 5792): [SCU] RegionMCC : 260
,I/SA      ( 5792): [SSP] query invoked
I/SA      ( 5792): [TPMU] GetMccFromDB : null
,I/SA      ( 5792): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5792): [SCU] saveMccToPreferece End
I/SA      ( 5792): [RC New] executeRequest [v2liruge] end. 939
,I/SA      ( 5792): [RC New] Execute end
I/SA      ( 5792): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5792): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2411): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2411): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2411): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/WifiStateMachine( 2411): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,E/SPPClientService( 5529): [b] __InitReply__
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=21 Removed Uoast (-2/11)
I/ActivityManager( 2411): Killing 6179:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2411): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2411) eventTime = 290436
D/PowerManagerService( 2411): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2411 (0x0)
D/PowerManagerService( 2411): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2411, ws=WorkSource{1000}) (elapsedTime=3465)
,I/GAV2    ( 7383): Thread[GAThread,5,main]: No campaign data found.,
,W/WifiP2pStateTracker( 2411): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED,
D/ConnectivityService( 2411): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2411):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2411): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2411): updateSourceRoutes : no source routing conditions
,D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6636): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6636): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6636): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6636): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6636): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6636): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6636): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6636): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6636): [ensureRegistration] - No Samsung account
,I/PowerManagerService( 2411): [PWL] Off : 180s ago
,D/CaptivePortalTracker( 2411): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2411): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2411): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2411): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2411): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2411): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2411): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2411): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,I/jxcore-log( 7226): Test app app.js loaded
I/jxcore-log( 7226): 
,I/chromium( 7226): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/SSRMv2:SIOP( 2411): SIOP:: AP = 340, Delta = 10
,D/BatteryService( 2411): level:100, scale:100, status:5, health:2, present:true, voltage: 4370, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2411): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2411): stay LED for fully charged
,D/UiModeManager( 2411): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4000): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4000): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7226): --= Surplus to requirements =--
I/jxcore-log( 7226): 
I/jxcore-log( 7226): ****TEST TOOK:  ms ****
I/jxcore-log( 7226): 
,I/jxcore-log( 7226): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7226): 
,D/AndroidRuntime( 7563): 
D/AndroidRuntime( 7563): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7563): CheckJNI is OFF
,D/AndroidRuntime( 7563): setted country_code = Poland
,D/AndroidRuntime( 7563): setted countryiso_code = PL
D/AndroidRuntime( 7563): setted sales_code = PLS
D/AndroidRuntime( 7563): readGMSProperty: start
,D/AndroidRuntime( 7563): readGMSProperty: already setted!!
D/AndroidRuntime( 7563): readGMSProperty: end
,D/AndroidRuntime( 7563): addProductProperty: start
,D/dalvikvm( 7563): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7563): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7563): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7563): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7563): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,D/PreloadUpdateManagerStateMachine( 5944): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5944): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5944): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5944): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5944): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5944): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5944): entry::IDLE
,E/memtrack( 7563): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7563): failed to load memtrack module: -2
,D/dalvikvm( 7563): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7563): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2411): START PACKAGE DELETE: observer{1119707560}
D/PackageManager( 2411): pkg{<packageName>}
D/PackageManager( 2411): user{0}
,D/PackageManager( 2411): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2411): getApplicationUninstallationEnabled
,D/ApplicationPolicy( 2411): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2411): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2411): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2411): !@killApplicatoin: 10622, uninstall pkg
,I/ActivityManager( 2411): Killing 7226:com.test.thalitest/u0a622 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2411): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
,I/WindowState( 2411): WIN DEATH: Window{43bc3630 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
I/SurfaceFlinger( 1921): id=20 Removed NainActivit (-2/10)
D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2411): Skipping PackageSetting{42c73408 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2411): setPackageStoppedState - Execution time: 109 ms
D/PackageManager( 2411): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10622, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/PackageManager( 2411): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10622, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4731): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,E/SamsungIME( 2977): mOCRHelper is null
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/QuickConnect[1.1][2] ( 5129): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "sms"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7574): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7574):  
,I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4731): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/DBG_DM  ( 4731): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,W/GeofencerStateMachine( 2737): Ignoring removeGeofence because network location is disabled.
I/SELinux ( 7574): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7574):  
I/SELinux ( 7574):  
,I/SELinux ( 7574): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7574): >>>>> Normal User
,E/dalvikvm( 7574): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
E/SELinux ( 7574): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2411):   Scheme: "smsto"
,D/dalvikvm( 2960): GC_EXPLICIT freed 1466K, 29% free 10036K/13940K, paused 7ms+7ms, total 138ms
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4731): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/RegisteredServicesCache( 2759): empty dynamic service
,D/dalvikvm( 3440): GC_EXPLICIT freed 366K, 22% free 12423K/15760K, paused 17ms+9ms, total 178ms
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "mms"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2411): Reconfiguring input devices.  changes=0x00000010
,D/TimaKeyStoreProvider( 7574): in addTimaSignatureService
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "mmsto"
,I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider( 7574): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7574): Added TimaKesytore provider
,I/DBG_DM  ( 4731): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 6796): GC_EXPLICIT freed 158K, 30% free 9959K/14164K, paused 3ms+3ms, total 258ms
,D/dalvikvm( 2411): GC_EXPLICIT freed 2264K, 71% free 25047K/86168K, paused 9ms+23ms, total 279ms
,D/dalvikvm( 2411): WAIT_FOR_CONCURRENT_GC blocked 259ms
,D/dalvikvm( 6408): GC_EXPLICIT freed 2511K, 30% free 9886K/13944K, paused 11ms+5ms, total 302ms
,I/DBG_DM  ( 4731): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "sms"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4731): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,D/RCPManagerService( 2411): PackageReceiver onReceive()
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "smsto"
,I/HarmonyEASService( 2411): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/DBG_DM  ( 4731): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
D/dalvikvm( 2759): GC_CONCURRENT freed 2338K, 27% free 10257K/13960K, paused 7ms+2ms, total 88ms
I/DBG_DM  ( 4731): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4731): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
I/DBG_DM  ( 4731): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4731): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/PhoneStatusBar( 2581): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/Activity( 4731): setTransGradationMode to true
,D/StatusBarManagerService( 2411): semi p:4731,o:t
I/DBG_DM  ( 4731): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1921): id=22 createSurf (720x1280),2 flag=404, YUIInstallC
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "mms"
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-StatusBarManagerService( 2411): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2411): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2411): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2411): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2411): setHoveringSpenCustomIcon IconType is same.1
,D/EnterpriseDeviceManagerService( 2411): Package has changed for user 0
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2411): Got RemoteException sending setActive(false) notification to pid 7226 uid 10622
,I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "mmsto"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7574): GC_CONCURRENT freed 2993K, 32% free 9577K/13940K, paused 11ms+1ms, total 34ms
,D/dalvikvm( 7574): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/elm:14132( 7574): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7574): ELMEngine.ELMEngine( context ).
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/elm:14132( 7574): MDMBridge.setEnterpriseBridge()
D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2411): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2411): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/elm:14132( 7574): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/SELinux ( 7588): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7588):  
,D/elm:14132( 7574): ElmAgentService : onCreate()
,D/elm:14132( 7574): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7574): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7574): MDMBridge.getInstance()
,D/elm:14132( 7574): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7574): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7574): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,I/SELinux ( 7588): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7588):  
I/SELinux ( 7588):  
,I/SELinux ( 7588): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7574): ElmAgentService : onDestroy().
E/dalvikvm( 7588): >>>>> Normal User
,E/dalvikvm( 7588): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7588): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2411): Killing 6571:com.android.defcontainer/u0a6 (adj 15): empty #43
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7588): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7588): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7588): Added TimaKesytore provider
,D/BackupManagerService( 2411): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2411): removePackageParticipantsLocked: uid=10622 #1
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 2411): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2411): sendNotification(2) - 4
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7588): GC_CONCURRENT freed 2997K, 32% free 9569K/13940K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 7588): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2411): GC_EXPLICIT freed 1126K, 71% free 25096K/86168K, paused 29ms+27ms, total 498ms
,D/PackageManager( 2411): delete sourFile : 
I/SELinux ( 7604): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7604):  
,I/ActivityManager( 2411): Killing 6428:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/PackageManager( 2411): delete native library directory: 
,D/PackageManager( 2411): return delete result to caller: 1119707560
,D/PackageManager( 2411): returnCode: 1
,D/AndroidRuntime( 7563): Shutting down VM
,D/dalvikvm( 7563): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 3ms
I/SELinux ( 7604): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7604):  
I/SELinux ( 7604):  
,I/SELinux ( 7604): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7604): >>>>> Normal User
,E/dalvikvm( 7604): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7604): in addTimaSignatureService
,I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "sms",
,I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
D/TimaKeyStoreProvider( 7604): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7604): Added TimaKesytore provider
,I/PackageManager( 2411):   Action: "android.intent.action.SENDTO",
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2411):   Scheme: "smsto"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2411):   Scheme: "mms"
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2411):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2411):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2411):   Scheme: "mmsto",
I/PackageManager( 2411): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7604): GC_CONCURRENT freed 3000K, 32% free 9568K/13944K, paused 2ms+2ms, total 21ms,
,D/dalvikvm( 7604): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/PCWCLIENTTRACE_PushUtil( 6636): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6636): sales region : global,
I/PCWCLIENTTRACE_PushUtil( 6636): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6636): [onReceive] - android.intent.action.PACKAGE_REMOVED,
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
,I/SA      ( 5792): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ],
,I/SA      ( 5792): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2411): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Icing.InternalIcingCorporaProvider( 6408): Updating corpora: A: com.test.thalitest, C: MAYBE
,D/UsbSettingsManager( 2411): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 2411): onPackageRemoved : com.test.thalitest
,I/SELinux ( 7624): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7624):  
,I/SELinux ( 7624): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7624):  
I/SELinux ( 7624):  
,I/SELinux ( 7624): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7624): >>>>> Normal User
,E/dalvikvm( 7624): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7624): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/AtomicFile( 2411): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,W/AppWidgetServiceImpl( 2411): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 13% free 9503K/10916K, paused 10ms+3ms, total 51ms
D/TimaKeyStoreProvider( 7624): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7624): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7624): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 2ms+3ms, total 25ms
,E/SQLiteLog( 6408): (10) unixWrite() gets errno : 9
,E/SQLiteLog( 6408): (10) unixWrite() gets errno : 9
,W/dalvikvm( 6408): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6408): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6408): Process: com.google.android.googlequicksearchbox:search, PID: 6408
E/AndroidRuntime( 6408): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6408): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6408): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6408): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 6408): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 6408): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:248)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6408): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6408): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6408): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6408): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6408): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6408): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6408): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 3ms+4ms, total 27ms
I/Process ( 6408): Sending signal. PID: 6408 SIG: 9
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/ActivityManager( 2411): Process com.google.android.googlequicksearchbox:search (pid 6408) (adj 5) has died.
W/ApplicationsProvider( 2960): Could not fetch usage stats
W/ApplicationsProvider( 2960): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2960): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2960): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2960): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2960): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2960): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2960): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2960): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2960): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/dalvikvm( 7624): GC_CONCURRENT freed 2997K, 32% free 9577K/13944K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 7624): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/UserAnalysis.PlaceProvider( 7624): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7624): Create SecureDbHelper
,E/SQLiteDatabase( 7624): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7624): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7624): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7624): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7624): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7624): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7624): Opened privacy in read-only mode
E/SQLiteDatabase( 7624): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7624): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7624): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7624): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7624): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7624): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7624): Opened privacy in read-only mode
E/SQLiteDatabase( 7624): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7624): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7624): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7624): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7624): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7624): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7624): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7624): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7624): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7624): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7624): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7624): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7624): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7624): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7624): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7624): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7624): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7624): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7624): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7624): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7624): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7624): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7624): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6344): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6422):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2411):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2411): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteDatabase( 6344): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6344): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6344): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6344): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6344): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6344): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
D/CapabilityManagerService New( 6705): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6705): The package(com.test.thalitest) removed
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6344): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6344): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6344): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6344): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6344): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 2411): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6344): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6344): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6344): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6344): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6344): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2411): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2411): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2411): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2411): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6344): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2411): 	... 8 more
W/System.err( 6344): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6344): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6344): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2411): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2411): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2411): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2411): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2411): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2411): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2411): 	... 8 more
D/MagazineService::MagazineBroadcastReceiver( 6732): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest,
,I/MagazineService::MagazineService( 6732): [onHandleIntent] ACTION_PACKAGE_REMOVED,
,E/SQLiteDatabase( 6732): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.,
E/SQLiteDatabase( 6732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232),
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6732): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
,E/SQLiteDatabase( 6732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6732): ,	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6732): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6732): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6732): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
,E/SQLiteDatabase( 6732): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6732): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6732): threadid=10: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 6732): FATAL EXCEPTION: IntentService[MagazineService::MagazineService],
E/AndroidRuntime( 6732): Process: com.samsung.android.magazine.service, PID: 6732
E/AndroidRuntime( 6732): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232),
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859),
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6732): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6732): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6732): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/AndroidRuntime( 6732): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6732): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6732): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6732): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6732): ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6732): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6732): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6732): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 7640): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7640):  
,I/Process ( 6732): Sending signal. PID: 6732 SIG: 9,
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
,E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): ,	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): ,	... 5 more
,I/ActivityManager( 2411): Process com.samsung.android.magazine.service (pid 6732) (adj 5) has died.,
,I/SELinux ( 7640): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7640):  
I/SELinux ( 7640):  
,I/SELinux ( 7640): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7640): >>>>> Normal User
,E/dalvikvm( 7640): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7640): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7640): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7640): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7640): Added TimaKesytore provider
D/CustomFrequencyManagerService( 2411): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2411  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7640): GC_CONCURRENT freed 2996K, 32% free 9566K/13936K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7640): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ContextImpl( 7640): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6758): onReceive intent data =  package:com.test.thalitest
E/SQLiteDatabase( 7640): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7640): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7640): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7640): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7640): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsPlatformStub( 6758): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7640): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7640): Process: com.android.keychain, PID: 7640
E/AndroidRuntime( 7640): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7640): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7640): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7640): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7640): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7640): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7640): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7640): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7640): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7640): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7640): Sending signal. PID: 7640 SIG: 9
,W/System.err( 6796): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6796): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
,E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
W/System.err( 6796): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6796): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6796): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6796): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6796): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6796): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6796): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6796): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6796): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6796): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6796): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6796): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 2411): Process com.android.keychain (pid 7640) (adj 5) has died.
D/PackageBroadcastService( 3440): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 3440): Clearing selected account for com.test.thalitest
,E/SQLiteLog( 3440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/DriveAsyncService( 3440): disk I/O error (code 3850)
E/DriveAsyncService( 3440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3440): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3440): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3440): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3440): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3440): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3440): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3440): 	at java.lang.Thread.run(Thread.java:841)
,I/LocationSettingsChecker( 3440): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3440): Loading module com.google.android.gms.games from APK com.google.android.play.games,
,D/ChimeraModuleLdr( 3440): Module APK com.google.android.play.games already loaded,
,E/SQLiteLog( 3440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
D/ChimeraCfgMgr( 3440): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3440): Module APK com.google.android.play.games already loaded,
,E/ClearPendingStateOp( 3440): Runtime exception while performing operation
E/ClearPendingStateOp( 3440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3440): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3440): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3440): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteLog( 2857): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 2857): Shutting down VM
,W/dalvikvm( 2857): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3440): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3440): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3440): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3440): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3440): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3440): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3440): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,F/ClearPendingStateOp( 3440): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3440): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3440): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3440): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3440): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3440): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3440): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3440): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3440): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteOpenHelper( 3440): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3440): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3440): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3440): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3440): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3440): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3440): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/AndroidRuntime( 2857): FATAL EXCEPTION: main
E/AndroidRuntime( 2857): Process: com.google.process.gapps, PID: 2857
E/AndroidRuntime( 2857): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2857): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2857): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2857): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2857): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2857): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2857): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2857): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2857): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2857): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2857): 	... 10 more
W/SQLiteOpenHelper( 3440): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3440): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3440): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteDatabase( 3440): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3440): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3440): 	a,t android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3440): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3440): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3440): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3440): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3440): threadid=48: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteLog( 3440): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/AndroidRuntime( 3440): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 3440): Process: com.google.android.gms, PID: 3440
E/AndroidRuntime( 3440): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 3440): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3440): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 3440): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3440): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3440): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 3440): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 3440): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 3440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3440): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 3440): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3440): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3440): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3440): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3440): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3440): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3440): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
W/dalvikvm( 3440): threadid=50: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3440): Sending signal. PID: 3440 SIG: 9
,E/JavaBinder( 2411): !!! FAILED BINDER TRANSACTION !!!
,W/ActivityManager( 2411): Exception when starting service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks
W/ActivityManager( 2411): android.os.TransactionTooLargeException
W/ActivityManager( 2411): 	at android.os.BinderProxy.transact(Native Method)
W/ActivityManager( 2411): 	at android.app.ApplicationThreadProxy.scheduleCreateService(ApplicationThreadNative.java:892)
W/ActivityManager( 2411): 	at com.android.server.am.ActiveServices.realStartServiceLocked(ActiveServices.java:1485)
W/ActivityManager( 2411): 	at com.android.server.am.ActiveServices.bringUpServiceLocked(ActiveServices.java:1395)
W/ActivityManager( 2411): 	at com.android.server.am.ActiveServices.startServiceInnerLocked(ActiveServices.java:424)
W/ActivityManager( 2411): 	at com.android.server.am.ActiveServices.startServiceLocked(ActiveServices.java:411)
W/ActivityManager( 2411): 	at com.android.server.am.ActivityManagerService.startService(ActivityManagerService.java:15347)
W/ActivityManager( 2411): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:858)
W/ActivityManager( 2411): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2758)
W/ActivityManager( 2411): 	at android.os.Binder.execTransact(Binder.java:404)
W/ActivityManager( 2411): 	at dalvik.system.NativeStart.run(Native Method)
I/Process ( 2857): Sending signal. PID: 2857 SIG: 9
E/SQLiteDatabase( 5529): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5529): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5529): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5529): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5529): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5529): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5529): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5529): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5529): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5529): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5529): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5529): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5529): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5529): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5529): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5529): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5529): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLi,teDatabase( 5529): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5529): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
E/DropBoxManagerService( 2411): Can't write: system_app_wtf
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,E/SQLiteDatabase( 6384): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6384): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6384): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6384): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6384): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6384): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6384): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6384): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6384): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6384): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6384): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6384): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7668): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7668):  
,E/SQLiteDatabase( 6384): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6384): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6384): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6384): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6384): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6384): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6384): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6384): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6384): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6384): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6384): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6384): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6384): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6384): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6384): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager( 2411): Process com.google.process.gapps (pid 2857) (adj 5) has died.
,D/GAV2    ( 5616): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
I/ActivityManager( 2411): Process com.google.android.gms (pid 3440) (adj 0) has died.
,I/GAV2    ( 5616): Thread[main,5,main]: Unexpected disconnect.
I/SELinux ( 7668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7668):  
I/SELinux ( 7668):  
,I/SELinux ( 7668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7668): >>>>> Normal User
,E/dalvikvm( 7668): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7668): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7668): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7668): Added TimaKesytore provider
,D/dalvikvm( 7668): GC_CONCURRENT freed 3001K, 32% free 9572K/13944K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7668): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7668): Loading roots for com.android.externalstorage.documents,
,E/SQLiteDatabase( 7668): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7668): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7668): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7668): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7668): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7668): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7668): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7668): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
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
,D/AndroidRuntime( 7668): Shutting down VM
,W/dalvikvm( 7668): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7684): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7684):  
E/AndroidRuntime( 7668): FATAL EXCEPTION: main
E/AndroidRuntime( 7668): Process: com.android.documentsui, PID: 7668
E/AndroidRuntime( 7668): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7668): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7668): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7668): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
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
E/AndroidRuntime( 7668): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
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
,I/SELinux ( 7688): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7688):  
,I/ActivityManager( 2411): Killing 6607:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/Process ( 7668): Sending signal. PID: 7668 SIG: 9
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/SELinux ( 7684): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7684):  
I/SELinux ( 7684):  
,I/SELinux ( 7684): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7684): >>>>> Normal User
,E/dalvikvm( 7684): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7684): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/ActivityManager( 2411): Process com.android.documentsui (pid 7668) (adj 9) has died.
I/ActivityManager( 2411): Waited long enough for: ServiceRecord{449e7f40 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/TimaKeyStoreProvider( 7684): in addTimaSignatureService
I/SELinux ( 7688): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7688):  
I/SELinux ( 7688):  
,I/SELinux ( 7688): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7684): Cannot add TimaSignature Service, License check Failed
E/dalvikvm( 7688): >>>>> Normal User
,E/dalvikvm( 7688): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,D/ActivityThread( 7684): Added TimaKesytore provider
,E/SELinux ( 7688): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7688): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7688): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7688): Added TimaKesytore provider
,D/dalvikvm( 7684): GC_CONCURRENT freed 3008K, 32% free 9556K/13940K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7684): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/ExternalStorage( 7684): After updating volumes, found 1 active roots
,D/dalvikvm( 7688): GC_CONCURRENT freed 2946K, 31% free 9623K/13944K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7688): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/dalvikvm( 7688): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7688): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7688): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 7688): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7688): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 7688): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7688): install
,I/MultiDex( 7688): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7688): loading existing secondary dex files
,I/MultiDex( 7688): load found 3 secondary dex files
,I/MultiDex( 7688): install done
,I/SELinux ( 7710): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7710):  
,I/SELinux ( 7710): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7710):  
I/SELinux ( 7710):  
,I/SELinux ( 7710): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7710): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7710): >>>>> Normal User
,E/dalvikvm( 7710): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7710): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7716): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7716):  
,D/TimaKeyStoreProvider( 7710): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7710): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7710): Added TimaKesytore provider
,I/SELinux ( 7716): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7716):  
I/SELinux ( 7716):  
,I/SELinux ( 7716): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7716): >>>>> Normal User
,E/dalvikvm( 7716): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7716): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7716): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7716): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7716): Added TimaKesytore provider
,D/dalvikvm( 7710): GC_CONCURRENT freed 2982K, 32% free 9587K/13940K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7710): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/dalvikvm( 7716): GC_CONCURRENT freed 2985K, 32% free 9582K/13936K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7716): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Icing.InternalIcingCorporaProvider( 7710): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7740): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7740):  
,D/LocationManagerService( 2411): getProviders()=[passive]
,I/GservicesProvider( 7716): Gservices pushing to system: true; secure/global: true,
I/SELinux ( 7740): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7740):  
I/SELinux ( 7740):  
,I/SELinux ( 7740): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7740): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
E/dalvikvm( 7740): >>>>> Normal User
,E/dalvikvm( 7740): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ],
,E/SELinux ( 7740): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/SQLiteDatabase( 7716): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7716): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7716): 	at android.content.ContentPr,ovider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7716): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7716): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7716): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7716): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7716): Shutting down VM
,W/dalvikvm( 7716): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 7716): FATAL EXCEPTION: main,
E/AndroidRuntime( 7716): Process: com.google.process.gapps, PID: 7716
E/AndroidRuntime( 7716): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
,E/AndroidRuntime( 7716): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7716): 	,at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7716): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7716): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.main(ActivityThread.java:5694),
E/AndroidRuntime( 7716): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7716): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7716): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7716): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7716): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7716): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7716): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696),
E/AndroidRuntime( 7716): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7716): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7716): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7716): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7716): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7716): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7716): 	,at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7716): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7716): 	... 12 more
I/Process ( 7716): Sending signal. PID: 7716 SIG: 9
,E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,D/TimaKeyStoreProvider( 7740): in addTimaSignatureService
D/TimaKeyStoreProvider( 7740): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7740): Added TimaKesytore provider
,I/ActivityManager( 2411): Process com.google.process.gapps (pid 7716) (adj 0) has died.
W/ActivityManager( 2411): Service crashed 2 times, stopping: ServiceRecord{430b7d98 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7758): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7758):  
,I/SELinux ( 7758): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7758):  
I/SELinux ( 7758):  
,I/SELinux ( 7758): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7758): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
E/dalvikvm( 7758): >>>>> Normal User
,E/dalvikvm( 7758): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7758): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7758): in addTimaSignatureService,
D/dalvikvm( 7740): GC_CONCURRENT freed 2996K, 32% free 9571K/13940K, paused 3ms+1ms, total 22ms,
,D/dalvikvm( 7740): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaKeyStoreProvider( 7758): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7758): Added TimaKesytore provider
,D/dalvikvm( 7758): GC_CONCURRENT freed 2993K, 32% free 9572K/13940K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7758): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,I/GservicesProvider( 7758): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7758): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7758): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7758): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7758): 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7758): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
,E/SQLiteDatabase( 7758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7758): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7758): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7758): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7758): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562),
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368),
E/SQLiteDatabase( 7758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7758): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7758): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7758): 	at java.lang.reflect.Method.invokeNative(Native Method),
E/SQLiteDatabase( 7758): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7758): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7758): Shutting down VM,
,W/dalvikvm( 7758): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7758): FATAL EXCEPTION: main
E/AndroidRuntime( 7758): Process: com.google.process.gapps, PID: 7758
E/AndroidRuntime( 7758): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/AndroidRuntime( 7758): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7758): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7758): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7758): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7758): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368),
E/AndroidRuntime( 7758): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7758): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7758): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7758): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7758): ,	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7758): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7758): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7758): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7758): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
,E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7758): 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7758): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224),
E/AndroidRuntime( 7758): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7758): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
,E/AndroidRuntime( 7758): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7758): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7758): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7758): 	,at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7758): 	... 12 more
W/ActivityManager( 2411): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2411): Killing 7758:com.google.process.gapps/u0a12 (adj 0): crash,
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
,E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): ,	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null,
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7710): Failed to find provider info for com.google.settings,
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7740): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7776): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7776):  
,I/SELinux ( 7776): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7776):  
I/SELinux ( 7776):  
,I/SELinux ( 7776): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7776): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7776): >>>>> Normal User
,E/dalvikvm( 7776): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7776): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7776): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7776): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7776): Added TimaKesytore provider,
,D/dalvikvm( 7776): GC_CONCURRENT freed 2997K, 32% free 9572K/13940K, paused 2ms+2ms, total 18ms,
,D/dalvikvm( 7776): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7776): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7776): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7776): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7776): 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7776): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7776): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7776): ,	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7776): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7776): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7776): ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7776): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7776): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7776): ,	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7776): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7776): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7776): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7776): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7776): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7776): Shutting down VM
,W/dalvikvm( 7776): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 7776): FATAL EXCEPTION: main,
E/AndroidRuntime( 7776): Process: com.google.process.gapps, PID: 7776
E/AndroidRuntime( 7776): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7776): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7776): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7776): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
,E/AndroidRuntime( 7776): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7776): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7776): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7776): 	,at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7776): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7776): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7776): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7776): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7776): ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7776): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7776): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232),
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7776): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7776): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7776): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7776): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7776): ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7776): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7776): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7776): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7776): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294),
E/AndroidRuntime( 7776): 	... 12 more
,I/Process ( 7776): Sending signal. PID: 7776 SIG: 9,
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
I/ActivityManager( 2411): Process com.google.process.gapps (pid 7776) (adj 0) has died.
,I/SELinux ( 7791): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7791):  
,I/SELinux ( 7791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7791):  
I/SELinux ( 7791):  
,I/SELinux ( 7791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7791): >>>>> Normal User
,E/dalvikvm( 7791): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7791): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7791): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7791): Added TimaKesytore provider
,D/dalvikvm( 7791): GC_CONCURRENT freed 2994K, 32% free 9572K/13940K, paused 2ms+1ms, total 18ms,
,D/dalvikvm( 7791): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7791): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7791): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7791): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7791): ,	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591),
E/SQLiteDatabase( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7791): 	,at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7791): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7791): ,	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7791): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7791): Shutting down VM,
,W/dalvikvm( 7791): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7791): FATAL EXCEPTION: main
E/AndroidRuntime( 7791): Process: com.google.process.gapps, PID: 7791
E/AndroidRuntime( 7791): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7791): ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7791): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7791): 	at java.lang.reflect.Method.invokeNative(Native Method)
,E/AndroidRuntime( 7791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7791): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7791): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7791): 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7791): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7791): 	,at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7791): 	... 12 more
W/ActivityManager( 2411): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2411): Killing 7791:com.google.process.gapps/u0a12 (adj 0): crash,
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7740): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2411): Can't write: system_app_crash,
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218),
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): ,	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7688): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS,
,I/ActivityManager( 2411): Killing 5686:com.android.mms/u0a49 (adj 15): empty #43,
W/dalvikvm( 7688): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7688): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7688): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs,
W/dalvikvm( 7688): VFY: unable to resolve instance field 36
D/dalvikvm( 7688): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7688): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7688): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;,
D/dalvikvm( 7688): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7688): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7688): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7688): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422b4aa0
,D/dalvikvm( 7688): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422b4aa0
D/dalvikvm( 7688): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422b4aa0, skipping init
,D/dalvikvm( 7688): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422b4aa0
D/dalvikvm( 7688): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422b4aa0
,V/JNIHelp ( 7688): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...,
D/CountryDetector( 2411): No listener is left
,D/dalvikvm( 7688): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422b4aa0,
D/dalvikvm( 7688): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422b4aa0
D/dalvikvm( 7688): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422b4aa0
,D/dalvikvm( 7688): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422b4aa0,
,I/ProviderInstaller( 7688): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7806): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7806):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 13% free 9503K/10916K, paused 2ms+2ms, total 26ms
,I/SELinux ( 7806): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7806):  
I/SELinux ( 7806):  
I/SELinux ( 7806): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7806): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7806): >>>>> Normal User
E/dalvikvm( 7806): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7806): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 2ms+3ms, total 22ms
,D/TimaKeyStoreProvider( 7806): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7806): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7806): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 13% free 9503K/10916K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 7806): GC_CONCURRENT freed 2988K, 32% free 9582K/13944K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7806): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/GservicesProvider( 7806): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7806): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7806): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7806): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7806): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7806): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7806): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7806): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7806): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7806): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7806): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7806): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7806): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7806): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7806): Shutting down VM
,W/dalvikvm( 7806): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
D/AmoledAdjustTimer( 2411): prevTemp = 293, currTemp = 294, prevStep = 4, currStep = 4
,E/AndroidRuntime( 7806): FATAL EXCEPTION: main
E/AndroidRuntime( 7806): Process: com.google.process.gapps, PID: 7806
E/AndroidRuntime( 7806): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7806): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7806): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7806): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7806): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7806): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7806): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7806): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7806): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7806): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7806): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7806): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7806): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7806): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7806): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7806): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7806): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7806): 	... 12 more
,I/Process ( 7806): Sending signal. PID: 7806 SIG: 9
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/ActivityManager( 2411): Process com.google.process.gapps (pid 7806) (adj 0) has died.
,I/SELinux ( 7821): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7821):  
,I/SELinux ( 7821): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7821):  
I/SELinux ( 7821):  
,I/SELinux ( 7821): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7821): >>>>> Normal User
,E/dalvikvm( 7821): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7821): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7821): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7821): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7821): Added TimaKesytore provider
,D/dalvikvm( 7821): GC_CONCURRENT freed 2990K, 32% free 9579K/13940K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7821): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7821): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7821): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7821): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7821): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7821): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7821): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7821): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7821): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7821): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7821): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7821): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7821): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7821): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7821): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7821): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7821): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7821): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7821): Shutting down VM
,W/dalvikvm( 7821): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7821): FATAL EXCEPTION: main
E/AndroidRuntime( 7821): Process: com.google.process.gapps, PID: 7821
E/AndroidRuntime( 7821): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7821): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7821): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7821): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7821): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7821): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7821): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7821): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7821): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7821): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7821): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7821): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7821): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7821): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7821): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7821): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7821): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7821): 	... 12 more
W/ActivityManager( 2411): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2411): Killing 7821:com.google.process.gapps/u0a12 (adj 0): crash
,W/NativeLibraryUtils( 7688): Failed to open lock file
W/NativeLibraryUtils( 7688): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7688): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7688): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7688): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7688): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7688): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7688): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7688): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7688): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7688): 	... 3 more
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/dalvikvm( 7688): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7688): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7688): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7841): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7841):  
,I/ActivityManager( 2411): Waited long enough for: ServiceRecord{449e4580 u0 com.sec.spp.push/.PushClientService}
,I/SELinux ( 7841): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7841):  
I/SELinux ( 7841):  
,I/SELinux ( 7841): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7841): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7841): >>>>> Normal User
,E/dalvikvm( 7841): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7841): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7841): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7841): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7841): Added TimaKesytore provider
,D/dalvikvm( 7841): GC_CONCURRENT freed 2994K, 32% free 9579K/13944K, paused 1ms+1ms, total 17ms
,D/dalvikvm( 7841): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7841): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7841): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7841): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7841): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7841): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7841): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7841): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7841): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7841): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7841): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7841): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7841): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7841): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7841): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7841): Shutting down VM
,W/dalvikvm( 7841): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 7841): Sending signal. PID: 7841 SIG: 9
E/AndroidRuntime( 7841): FATAL EXCEPTION: main
E/AndroidRuntime( 7841): Process: com.google.process.gapps, PID: 7841
E/AndroidRuntime( 7841): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7841): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7841): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7841): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7841): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7841): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7841): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7841): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7841): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7841): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7841): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7841): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7841): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7841): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7841): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7841): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7841): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7841): 	... 12 more
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/ActivityManager( 2411): Process com.google.process.gapps (pid 7841) (adj 0) has died.
,I/SELinux ( 7856): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7856):  
,I/SELinux ( 7856): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7856):  
I/SELinux ( 7856):  
,I/SELinux ( 7856): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7856): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7856): >>>>> Normal User
,E/dalvikvm( 7856): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7856): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7856): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7856): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7856): Added TimaKesytore provider
,D/dalvikvm( 7856): GC_CONCURRENT freed 2998K, 32% free 9572K/13944K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7856): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7856): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7856): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7856): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7856): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7856): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7856): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7856): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7856): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7856): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7856): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7856): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7856): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7856): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7856): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7856): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7856): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7856): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7856): Shutting down VM
,W/dalvikvm( 7856): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7856): FATAL EXCEPTION: main
E/AndroidRuntime( 7856): Process: com.google.process.gapps, PID: 7856
E/AndroidRuntime( 7856): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7856): ,	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7856): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7856): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7856): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7856): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7856): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7856): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7856): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7856): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7856): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7856): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7856): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7856): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7856): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7856): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7856): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7856): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7856): 	... 12 more
,I/GAv4-SVC( 7688): Google Analytics 8.4.89 is starting up.,
W/ActivityManager( 2411): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2411): Killing 7856:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2411): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7688): Failed to find provider info for com.google.android.gsf.gservices,
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
,E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
,E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	,at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
,I/SELinux ( 7871): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7871):  
,I/SELinux ( 7871): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7871):  
I/SELinux ( 7871):  
,I/SELinux ( 7871): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7871): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7871): >>>>> Normal User
,E/dalvikvm( 7871): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7871): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7871): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7871): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7871): Added TimaKesytore provider
,D/dalvikvm( 7871): GC_CONCURRENT freed 2985K, 32% free 9583K/13940K, paused 2ms+1ms, total 17ms,
,D/dalvikvm( 7871): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,I/GservicesProvider( 7871): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7871): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7871): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338),
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7871): 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7871): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7871): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7871): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/SQLiteDatabase( 7871): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7871): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7871): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7871): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7871): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7871): 	,at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7871): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7871): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7871): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7871): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7871): 	,at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7871): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7871): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7871): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7871): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7871): 	,at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7871): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7871): Shutting down VM
,W/dalvikvm( 7871): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,E/AndroidRuntime( 7871): FATAL EXCEPTION: main,
E/AndroidRuntime( 7871): Process: com.google.process.gapps, PID: 7871
E/AndroidRuntime( 7871): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7871): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7871): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7871): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7871): ,	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7871): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7871): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7871): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7871): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/AndroidRuntime( 7871): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7871): 	at java.lang.reflect.Method.invoke(Method.java:515),
,E/AndroidRuntime( 7871): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7871): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7871): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7871): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7871): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7871): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7871): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7871): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7871): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7871): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7871): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7871): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7871): 	... 12 more
,I/Process ( 7871): Sending signal. PID: 7871 SIG: 9,
E/DropBoxManagerService( 2411): Can't write: system_app_crash
E/DropBoxManagerService( 2411): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
,E/DropBoxManagerService( 2411): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2411): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2411): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2411): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2411): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2411): 	,at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2411): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2411): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2411): 	... 5 more
I/ActivityManager( 2411): Process com.google.process.gapps (pid 7871) (adj 0) has died.,
,I/SELinux ( 7886): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7886):  
,I/SELinux ( 7886): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7886):  
I/SELinux ( 7886):  
,I/SELinux ( 7886): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7886): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
E/dalvikvm( 7886): >>>>> Normal User
,E/dalvikvm( 7886): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7886): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7886): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7886): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7886): Added TimaKesytore provider,
,D/dalvikvm( 7886): GC_CONCURRENT freed 2999K, 32% free 9572K/13944K, paused 2ms+1ms, total 19ms,
,D/dalvikvm( 7886): WAIT_FOR_CONCURRENT_GC blocked 16ms,

```
