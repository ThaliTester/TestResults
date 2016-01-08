#### Test 549702618c0ebdb_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryService( 2419): stay LED for fully charged
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AndroidRuntime( 7100): 
D/AndroidRuntime( 7100): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7100): CheckJNI is OFF
D/AndroidRuntime( 7100): setted country_code = Poland
D/AndroidRuntime( 7100): setted countryiso_code = PL
D/AndroidRuntime( 7100): setted sales_code = PLS
D/AndroidRuntime( 7100): readGMSProperty: start
D/AndroidRuntime( 7100): readGMSProperty: already setted!!
D/AndroidRuntime( 7100): readGMSProperty: end
D/AndroidRuntime( 7100): addProductProperty: start
D/dalvikvm( 7100): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7100): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7100): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7100): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7100): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7100): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7100): failed to load memtrack module: -2
D/dalvikvm( 7100): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7100): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SELinux ( 7128): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7128):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7100): Shutting down VM
D/dalvikvm( 7100): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+1ms, total 3ms
I/SELinux ( 7128): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7128):  
I/SELinux ( 7128):  
I/SELinux ( 7128): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7128): >>>>> Normal User
E/dalvikvm( 7128): >>>>> com.test.thalitest [ userId:0 | appId:10596 ]
E/SELinux ( 7128): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7128): in addTimaSignatureService
D/TimaKeyStoreProvider( 7128): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7128): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4178): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4178): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7128): GC_CONCURRENT freed 3024K, 31% free 9551K/13732K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7128): Binding Chromium to the background looper Looper (main, tid 1) {42275220}
I/chromium( 7128): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7128): Initializing chromium process, renderers=0
W/chromium( 7128): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7128): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7128): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7128): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7128): Mali API Version : 401
,I/Mali    ( 7128): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7128): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7128): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7128): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7128): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7128): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7128): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2419): tr p:7128,o:f
,W/dalvikvm( 7128): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7128): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7128): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7128): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7128): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7128): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7128): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7128): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7128): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7128): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7128): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7128): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7128): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2419): semi p:7128,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7128): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7128): Enabling debug mode 0
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7128): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7128): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7128): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7128): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422719c8
,D/dalvikvm( 7128): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422719c8
D/jxcore_app_log( 7128): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027582264
,D/JX-Cordova( 7128): jxcore cordova android initializing
,D/dalvikvm( 7128): GC_CONCURRENT freed 1278K, 18% free 11348K/13780K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/PowerManagerService( 2419): [PWL] Off : 180s ago
,D/dalvikvm( 7128): GC_CONCURRENT freed 1897K, 17% free 14998K/18064K, paused 2ms+2ms, total 40ms,
D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 24ms,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10,
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8,
,D/dalvikvm( 7128): GC_FOR_ALLOC freed 5371K, 30% free 16238K/22992K, paused 41ms, total 42ms
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 7128): GC_CONCURRENT freed 6715K, 31% free 17692K/25584K, paused 2ms+9ms, total 57ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7128): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7128): GC_FOR_ALLOC freed 1260K, 32% free 17517K/25584K, paused 36ms, total 36ms
,I/dalvikvm-heap( 7128): Grow heap (frag case) to 21.750MB for 3688532-byte allocation
,D/dalvikvm( 7128): GC_FOR_ALLOC freed 36K, 28% free 21083K/29188K, paused 42ms, total 42ms
,W/jxcore-log( 7128): Initializing JXcore engine
,W/jxcore-log( 7128): JXcore engine is ready
,W/jxcore-log( 7128): Starting JXcore engine
,W/jxcore-log( 7128): Platform android
W/jxcore-log( 7128): 
,W/jxcore-log( 7128): Process ARCH arm
W/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/jxcore-log( 7128): JXcore Cordova bridge is ready!
I/jxcore-log( 7128): 
,W/jxcore-log( 7128): JXcore engine is started
,I/chromium( 7128): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7128): Toggling radios to true
I/jxcore-log( 7128): 
,D/BluetoothAdapter( 7128): enable(): BT is already enabled..!
,I/WifiManager( 7128): packageName : com.test.thalitest
,I/WifiManager( 7128): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7128, uid=10596
,W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7128, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7128, uid=10596 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2419): disconnect: pid=7128, uid=10596
I/jxcore-log( 7128): Radios toggled
I/jxcore-log( 7128): 
I/wpa_supplicant( 3964): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3964): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3964): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3964): First Scan Start
,W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3964): Scan requested (ret=0) - scan timeout 30 seconds
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3964): Skip scan - already scanning
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/ConnectivityService( 2419): Attempting to switch to mobile
,D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7175): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7175):  
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-83ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7175): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7175):  
I/SELinux ( 7175):  
E/WifiStateMachine( 2419): Error! unhandled message{ when=-82ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,I/SELinux ( 7175): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,E/SELinux ( 7175): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7175): >>>>> Normal User
,E/dalvikvm( 7175): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,W/NetworkManagementService( 2419): route cmd failed: 
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '36 route del src v6 2' failed with '400 36 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2419): '
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2419): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2419): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2419): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2419): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2419): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2419): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,E/SELinux ( 7175): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler },
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,D/TimaKeyStoreProvider( 7175): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7175): Cannot add TimaSignature Service, License check Failed,
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x77d497f0 clazz=0x62600001 iface=wlan0 mask=0x3,
,D/ConnectivityService( 2419): resetConnections(wlan0, 3),
D/ActivityThread( 7175): Added TimaKesytore provider
,V/NativeCrypto( 2849): Read error: ssl=0x7b9e6a50: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7b9e6a50: I/O error during system call, Broken pipe,
,E/SPPClientService( 5535): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,E/SPPClientService( 5535): [e] exceptionCaught(). NET_TIMEOUT,
,D/dalvikvm( 7175): GC_CONCURRENT freed 2993K, 31% free 9576K/13728K, paused 4ms+6ms, total 35ms,
,D/dalvikvm( 7175): WAIT_FOR_CONCURRENT_GC blocked 27ms
,E/SPPClientService( 5535): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5535): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5535): [b] ResponseMap empty
,I/System.out( 7175): Inside WakeupProvider
,I/System.out( 7175): Inside onCreate() of WakeupTriggerProvide
,D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): updateIfacesLocked()
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/VlingoApplication( 7175): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7175): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7175): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 29ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,D/DialogFlow( 7175): initQueue()
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2419): Killing 6171:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
I/PCWCLIENTTRACE_PushUtil( 6580): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6580): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6580): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6580): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6580): noConnectivity : true
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7204): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7204):  
,I/SELinux ( 7204): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7204):  
I/SELinux ( 7204):  
,I/SELinux ( 7204): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7204): >>>>> Normal User
,E/dalvikvm( 7204): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7204): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7204): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7204): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7204): Added TimaKesytore provider
,I/wpa_supplicant( 3964): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 3964): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3964): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/dalvikvm( 7204): GC_CONCURRENT freed 3007K, 31% free 9560K/13728K, paused 2ms+3ms, total 24ms
,D/dalvikvm( 7204): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/ActivityManager( 2419): Killing 6241:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
I/wpa_supplicant( 3964): Associated with C0.AA.48
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3964): freq(2412) increment count 2
,I/wpa_supplicant( 3964): meet head of list.
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3964): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3964): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/WifiNative( 2419): callSECApiVoid - ID [50]
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7218):  
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/SELinux ( 7218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7218):  
I/SELinux ( 7218):  
,I/SELinux ( 7218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7218): >>>>> Normal User
E/dalvikvm( 7218): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7218): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7218): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7218): Added TimaKesytore provider
,D/dalvikvm( 7218): GC_CONCURRENT freed 3001K, 31% free 9568K/13724K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2419): Killing 6310:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7230): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7230):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9505K/10708K, paused 2ms+4ms, total 37ms
,I/SELinux ( 7230): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7230):  
I/SELinux ( 7230):  
,I/SELinux ( 7230): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7230): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7230): >>>>> Normal User
E/dalvikvm( 7230): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7230): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+5ms, total 36ms
D/TimaKeyStoreProvider( 7230): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7230): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7230): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+6ms, total 41ms
,I/dhcpcd  ( 7234): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7234): bssid match
,D/dalvikvm( 7230): GC_CONCURRENT freed 2997K, 31% free 9575K/13728K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7230): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/KLMS-2.3.201 : ( 7230): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7230): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452267319618
,I/KLMS-2.3.201 : ( 7230): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2419): Killing 6345:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7249): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7249):  
,I/SELinux ( 7249): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7249):  
I/SELinux ( 7249):  
,I/SELinux ( 7249): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7249): >>>>> Normal User
,E/dalvikvm( 7249): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7249): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7249): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7249): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7249): Added TimaKesytore provider
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7249): GC_CONCURRENT freed 3014K, 31% free 9561K/13732K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7249): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/SO_AGENT( 7249): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7249): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5802): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5802): [BDLM] already registered in spp
I/SA      ( 5802): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5802): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [OR] == isSIMCardReady false ==
I/SA      ( 5802): [SCU] == networkStateCheck == false
,I/SA      ( 5802): [OR] onReceive END
I/ActivityManager( 2419): Killing 6382:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7261): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7261):  
,I/SELinux ( 7261): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7261):  
I/SELinux ( 7261):  
,I/SELinux ( 7261): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7261): >>>>> Normal User
,E/dalvikvm( 7261): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7261): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7261): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7261): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7261): Added TimaKesytore provider
,D/dalvikvm( 7261): GC_CONCURRENT freed 2994K, 31% free 9573K/13728K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7261): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/sCloudBackupApp( 7261): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7261): Other Intent
I/ActivityManager( 2419): Killing 5585:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7274):  
,I/SELinux ( 7274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7274):  
I/SELinux ( 7274):  
,I/SELinux ( 7274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7274): >>>>> Normal User
,E/dalvikvm( 7274): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7274): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7274): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7274): Added TimaKesytore provider
,D/dalvikvm( 7274): GC_CONCURRENT freed 2998K, 31% free 9573K/13728K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7274): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7274): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7274): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5339): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7274): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5339): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7274): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5339): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2419): Killing 6297:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5870): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5870): getCountryCode(): countryCode = PL
D/Headlines( 5870): Breath.onCreate
,D/Headlines( 5870): Breath timer started. interval : 30000
,I/SELinux ( 7286): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7286):  
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,V/AlarmManager( 2419): waitForAlarm result :8
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5870): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5870): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5870): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7286): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7286):  
I/SELinux ( 7286):  
,I/SELinux ( 7286): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7286): >>>>> Normal User
,E/dalvikvm( 7286): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7286): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7286): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7286): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7286): Added TimaKesytore provider
,D/dalvikvm( 7286): GC_CONCURRENT freed 2995K, 31% free 9575K/13728K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7286): WAIT_FOR_CONCURRENT_GC blocked 14ms
,V/WebViewChromium( 7286): Binding Chromium to the background looper Looper (main, tid 1) {422721c0}
,I/chromium( 7286): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7286): Initializing chromium process, renderers=0
,W/chromium( 7286): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7286): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7286): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7286): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7286): Mali API Version : 401
,I/Mali    ( 7286): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7286): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7286): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2419): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/NSApplication( 7286): Starting up...
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/iu.Environment( 5934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,D/QuickConnect[1.1][2] ( 5140): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5140): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5140): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42281d68
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/SELinux ( 7355): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7355):  
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,I/SELinux ( 7355): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7355):  
I/SELinux ( 7355):  
,I/SELinux ( 7355): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7355): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7355): >>>>> Normal User
,E/dalvikvm( 7355): >>>>> com.android.email [ userId:0 | appId:10157 ]
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,E/SELinux ( 7355): [DEBUG] seapp_context_lookup: seinfoCategory = platform
V/NetworkStats( 2419): performPollLocked() took 28ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/TimaKeyStoreProvider( 7355): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7355): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7355): Added TimaKesytore provider
,D/dalvikvm( 7355): GC_CONCURRENT freed 2988K, 31% free 9588K/13732K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7355): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/SELinux ( 7379): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7379):  
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/ActivityManager( 2419): Killing 6323:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7379): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7379):  
I/SELinux ( 7379):  
,I/SELinux ( 7379): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7379): >>>>> Normal User
,E/dalvikvm( 7379): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7379): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7379): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7379): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7379): Added TimaKesytore provider
,I/SELinux ( 7391): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7391):  
,I/ActivityManager( 2419): Killing 5986:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7391): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7391):  
I/SELinux ( 7391):  
,I/SELinux ( 7391): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7391): >>>>> Normal User
E/dalvikvm( 7391): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7391): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7391): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7391): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7391): Added TimaKesytore provider
D/dalvikvm( 7379): GC_CONCURRENT freed 3009K, 31% free 9561K/13728K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7379): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-9ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
I/DBG_DM  ( 4760): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/BadgeProvider( 7379): onCreate
,D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
,D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,D/BadgeProvider( 7379): DatabaseHelper
,D/BadgeProvider( 7379): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2771): reloadBadges entered.
D/BadgeProvider( 7379): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7379): sendNotify, [notify] : null
D/BadgeProvider( 7379): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7379): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7379): update, [UpdateCount] : 1
,D/dalvikvm( 7391): GC_CONCURRENT freed 3007K, 31% free 9568K/13732K, paused 4ms+1ms, total 37ms
,D/dalvikvm( 7391): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/hcjo    ( 5955): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5955): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 5955): exit::IDLE
,D/InitializeManagerStateMachine( 5955): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5955): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5955): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5955): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5955): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): entry::SUCCESS
,D/hcjo    ( 5955): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5955): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
D/InitializeManagerStateMachine( 5955): exit::SUCCESS
,D/InitializeManagerStateMachine( 5955): entry::IDLE
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,E/SPPClientService( 5535): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5535): [SystemStateMoniter] Current Time : 256917
,E/SPPClientService( 5535): [SystemStateMoniter] No Connect : true,
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null,
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED,
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state,
,E/SPPClientService( 5535): [[SystemStateMonitorService]] No Active Internet,
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5870): Breath 1715 latestRequest time : 1452267320360 current time : 1452267322075
E/SPPClientService( 5535): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5535): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5535): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5535): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state,
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast,
,I/PCWCLIENTTRACE_PushUtil( 6580): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6580): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6580): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6580): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE,
,E/SPPClientService( 5535): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false,
D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,E/SPPClientService( 5535): [a] [ConnectionManager] Connection is already disconnected.,
,E/SPPClientService( 5535): [g] getNetMCC return empty string,
,I/KLMS-2.3.201 : ( 7230): KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,D/dalvikvm( 2419): GC_EXPLICIT freed 4110K, 74% free 25560K/95632K, paused 11ms+19ms, total 212ms,
,I/KLMS-2.3.201 : ( 7230): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452267322527,
,I/KLMS-2.3.201 : ( 7230): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false,
,D/SO_AGENT( 7249): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3370): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3370): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3370): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3370): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7249): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3514): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7419): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7419):  
,I/SELinux ( 7419): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7419):  
I/SELinux ( 7419):  
,I/SELinux ( 7419): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7419): >>>>> Normal User
,E/dalvikvm( 7419): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7419): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7431): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7431):  
,D/TimaKeyStoreProvider( 7419): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7419): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7419): Added TimaKesytore provider
,I/SELinux ( 7431): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7431):  
I/SELinux ( 7431):  
,I/SELinux ( 7431): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7431): >>>>> Normal User
,E/dalvikvm( 7431): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7431): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7431): in addTimaSignatureService
,D/dalvikvm( 7419): GC_CONCURRENT freed 2993K, 31% free 9576K/13724K, paused 2ms+2ms, total 21ms
,D/dalvikvm( 7419): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/TimaKeyStoreProvider( 7431): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7431): Added TimaKesytore provider
,I/System.out( 7218): Thread-636(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7218): Thread-636(ApacheHTTPLog):isShipBuild true
,I/System.out( 7218): Thread-636(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 7431): GC_CONCURRENT freed 3002K, 31% free 9570K/13728K, paused 6ms+6ms, total 34ms
,D/dalvikvm( 7431): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/SA      ( 5802): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5802): [BDLM] already registered in spp
,I/SA      ( 5802): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5802): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [OR] == isSIMCardReady false ==
,I/SA      ( 5802): [SCU] == networkStateCheck == true
I/SA      ( 5802): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5802): isChinaCountryCode : false
,I/SA      ( 5802): [OR] == networkStateCheck true ==
,V/KVNProvider( 7431): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7431): getFindoCursor query string : 
,I/SA      ( 5802): [OR] GetMyCountryZoneTask
,I/SA      ( 5802): [OR] onReceive END
,I/SA      ( 5802): [SRS] prepareGetMyCountryZone
,I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [SSP] query invoked
,V/KVNProvider( 7431): getTagSearchCursor() tagSearchCursor count : 0
,I/SA      ( 5802): [TPMU] GetMccFromDB : null
I/SA      ( 5802): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5802): [TPM] isNoProxy(default) : true
,I/SA      ( 5802): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 7261): Other Intent
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7274): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5870): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5870): getCountryCode(): countryCode = PL
D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5870): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5870): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5870): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5870): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/System.out( 7218): AsyncTask #1 calls detatch()
,D/QuickConnect[1.1][2] ( 5140): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5140): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5140): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42281d68
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,W/System.err( 7218): com.sec.android.fota.osp.http.RestClientException
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
W/System.err( 7218): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
,W/System.err( 7218): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7218): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7218): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7218): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7218): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7218): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7218): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7218): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7218): Caused by: java.lang.NullPointerException
W/System.err( 7218): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7218): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7218): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7218): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
W/System.err( 7218): 	... 8 more
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/hcjo    ( 5955): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5955): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5955): exit::IDLE
,D/InitializeManagerStateMachine( 5955): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5955): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5955): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5955): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5955): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5955): entry::SUCCESS
,D/hcjo    ( 5955): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5955): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5955): exit::SUCCESS
,D/InitializeManagerStateMachine( 5955): entry::IDLE
,I/ActivityManager( 2419): Killing 6260:com.android.providers.calendar/u0a45 (adj 15): empty #43
,E/SPPClientService( 5535): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5535): [SystemStateMoniter] Current Time : 258017
,E/SPPClientService( 5535): [SystemStateMoniter] No Connect : false
,E/Watchdog( 2419): !@Sync 8
,D/dalvikvm( 5535): GC_CONCURRENT freed 2002K, 24% free 10438K/13708K, paused 5ms+4ms, total 59ms,
,I/SA      ( 5802): [RC New] [v2liruge] api execute + 761,
,I/SA      ( 5802): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 5802): AsyncTask #2 calls detatch(),
,I/SA      ( 5802): [TPMU] getNetworkMcc : ,
,I/SA      ( 5802): [SCU] saveMccToPreferece Start,
I/SA      ( 5802): [SCU] RegionMCC : 260
,I/SA      ( 5802): [SSP] query invoked,
I/SA      ( 5802): [TPMU] GetMccFromDB : null
I/SA      ( 5802): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5802): [SCU] saveMccToPreferece End
,I/SA      ( 5802): [RC New] executeRequest [v2liruge] end. 789
I/SA      ( 5802): [RC New] Execute end
,I/SA      ( 5802): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5802): [OR] GetMyCountryZoneTask Success
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/ActivityManager( 2419): Killing 6156:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
D/dalvikvm( 5934): GC_CONCURRENT freed 526K, 6% free 26872K/28556K, paused 4ms+9ms, total 60ms
D/dalvikvm( 5934): WAIT_FOR_CONCURRENT_GC blocked 35ms
E/SPPClientService( 5535): [b] __InitReply__
E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/ActivityManager( 2419): Killing 6193:com.google.android.music:main/u0a125 (adj 15): empty #43
I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 260599
D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3465)
,I/GAV2    ( 7286): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6580): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6580): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6580): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6580): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6580): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6580): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6580): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6580): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6580): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4362, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/PreloadUpdateManagerStateMachine( 5955): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5955): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5955): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5955): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5955): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5955): entry::IDLE
,I/jxcore-log( 7128): Test app app.js loaded
I/jxcore-log( 7128): 
,I/chromium( 7128): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PreloadUpdateManagerStateMachine( 5955): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5955): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5955): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5955): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5955): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5955): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 5955): entry::IDLE,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 291, prevStep = 4, currStep = 4,
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{438aebf0 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{4331f990 u0 com.sec.spp.push/.PushClientService},
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4,
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/jxcore-log( 7128): TAP version 13,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
,I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # multiplex can send data
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5870): Breath 29064 latestRequest time : 1452267322952 current time : 1452267352016
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 9
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0
,I/jxcore-log( 7128): ok 1 String should be length:200
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # basic,
I/jxcore-log( 7128): 
,I/PowerManagerService( 2419): [PWL] Off : 225s ago,
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED,
D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 2 sane,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # another,
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 3 sane,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7128): # successfully create a new pkcs12 file and return hash value,
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4,
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000,
,I/TLC_TIMA_PKM_initialize( 2419): initializing...,
I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196,
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1,
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208,
I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called,
,I/TZ: mc_tlc_communication( 2419): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2419): Opening the session,
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :8
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5870): Breath 57433 latestRequest time : 1452267322952 current time : 1452267380385,
,I/jxcore-log( 7128): ok 4 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 5 null,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 6 (unnamed assert),
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 7 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 8 should not throw,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 7813,
,I/jxcore-log( 7128): # successfully read a previous pkcs12 file and return hash value,
I/jxcore-log( 7128): 
,E/Watchdog( 2419): !@Sync 10,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10,
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 9 (unnamed assert),
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 10 (unnamed assert),
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 11 should not throw,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 12 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 13 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # failed to extract public key because of corrupt pkcs12 file,
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 14 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # failed to get mobile documents path,
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 15 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,I/jxcore-log( 7128): # #init should register the peerAvailabilityChanged event,
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2419): [PWL] Off : 275s ago,
,I/jxcore-log( 7128): ok 16 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 17 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 18 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # #init should register the networkChanged event,
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4375, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2419): !@Sync 11,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4,
,I/jxcore-log( 7128): ok 19 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :4,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7998): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7998):  
,I/SELinux ( 7998): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7998):  
I/SELinux ( 7998):  
,I/SELinux ( 7998): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 7998): >>>>> Normal User
,E/dalvikvm( 7998): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7998): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7998): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7998): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7998): Added TimaKesytore provider
,D/dalvikvm( 7998): GC_CONCURRENT freed 3000K, 31% free 9568K/13728K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7998): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5870): Breath 96956 latestRequest time : 1452267322952 current time : 1452267419908,
,I/ActivityManager( 2419): Killing 6524:com.android.defcontainer/u0a6 (adj 15): empty #43,
,V/AlarmManager( 2419): waitForAlarm result :8,
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7128): # #startBroadcasting should throw on null device name,
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true,
,D/BatteryService( 2419): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate,
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4001): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # teardown,
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/jxcore-log( 7128): ok 20 should throw,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup,
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 12
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): ok 21 should throw
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # #startBroadcasting should throw on non-number port
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): ok 22 should throw
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/jxcore-log( 7128): # #startBroadcasting should throw on NaN port
I/jxcore-log( 7128): 
,D/Headlines( 5870): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5870): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5870): Breath 135289 latestRequest time : 1452267322952 current time : 1452267458241
,D/Headlines( 5870): stop 
,I/SELinux ( 8214): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8214):  
,D/Headlines( 5870): Breath.onDestroy : 
I/ActivityManager( 2419): Killing 6444:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 12% free 9505K/10708K, paused 7ms+4ms, total 62ms
,I/SELinux ( 8214): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8214):  
I/SELinux ( 8214):  
,I/SELinux ( 8214): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8214): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8214): >>>>> Normal User
,E/dalvikvm( 8214): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8214): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8214): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+4ms, total 35ms
,D/TimaKeyStoreProvider( 8214): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8214): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 12% free 9505K/10708K, paused 3ms+4ms, total 33ms
,D/dalvikvm( 8214): GC_CONCURRENT freed 2997K, 31% free 9576K/13732K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 8214): WAIT_FOR_CONCURRENT_GC blocked 28ms
,E/SPPClientService( 8214): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8214): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8214): PushLog.txt file is not deleted.
D/SPPClientService( 8214): PushLog.txt file is not deleted.
,D/SPPClientService( 8214): ============PushLog. stop!
,I/ActivityManager( 2419): Killing 6553:com.samsung.groupcast/u0a15 (adj 15): empty #43
,E/SPPClientService( 5535): [b] __PingReply__
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 23 should throw
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # #startBroadcasting should throw on negative port
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 24 should throw
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,I/PowerManagerService( 2419): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7128): # #startBroadcasting should throw on too large port
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): ok 25 should throw
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 13
,I/jxcore-log( 7128): ok 26 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 27 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 28 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7128): ok 29 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 30 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 31 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7128): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 32 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 33 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,E/Watchdog( 2419): !@Sync 14
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 34 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 35 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 36 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 37 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 38 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 390s ago
,I/jxcore-log( 7128): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 15
,I/jxcore-log( 7128): ok 39 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 40 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # should call Mobile("Disconnect") without an error
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/jxcore-log( 7128): ok 41 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 42 should be equal,
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 43 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): ok 44 should be equal
I/jxcore-log( 7128): 
,I/jxcore-log( 7128): # setup
I/jxcore-log( 7128): 
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7128): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 7128): 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,I/jxcore-log( 7128): # teardown
I/jxcore-log( 7128): 
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/dalvikvm( 7128): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
,W/dalvikvm( 7128): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7128): VFY: replacing opcode 0x6e at 0x0002
,D/AndroidRuntime( 7128): Shutting down VM
,W/dalvikvm( 7128): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7128): FATAL EXCEPTION: main
E/AndroidRuntime( 7128): Process: com.test.thalitest, PID: 7128
E/AndroidRuntime( 7128): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7128): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7128): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7128): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:93)
E/AndroidRuntime( 7128): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/AndroidRuntime( 7128): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7128): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7128): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7128): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7128): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7128): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7128): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7128): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7128): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7128): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7128): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7128): 	at dalvik.system.NativeStart.main(Native Method)
,W/ActivityManager( 2419):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
,D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/ActivityManager( 2419): Killing 6567:com.android.musicfx/u0a24 (adj 15): empty #43
,D/CrashAnrDetector( 2419): processName: com.test.thalitest
,D/CrashAnrDetector( 2419): broadcastEvent : com.test.thalitest data_app_crash
,I/Process ( 7128): Sending signal. PID: 7128 SIG: 9
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2419): mDVFSHelper.acquire()
,I/DBG_DM  ( 4760): [3.19.140541][Line:408][onResume] 
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1920): id=19 Removed NainActivit (-2/10)
I/ActivityManager( 2419): Process com.test.thalitest (pid 7128) (adj 9) has died.
I/WindowState( 2419): WIN DEATH: Window{42ea38f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/DBG_DM  ( 4760): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
,I/DBG_DM  ( 4760): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:418][onResume] Postpone Count : 28
,I/DBG_DM  ( 4760): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,I/DBG_DM  ( 4760): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2419): sendNotification(2) - 4
,I/DBG_DM  ( 4760): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 28
,I/DBG_DM  ( 4760): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4760): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
D/checkbox( 4760): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4760): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4760): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
D/Activity( 4760): setTransGradationMode to true
,D/PhoneStatusBar( 2580): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4760): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2419): semi p:4760,o:t
,I/SurfaceFlinger( 1920): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7128 uid 10596
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
,D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/ActivityManager( 2419): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,E/Watchdog( 2419): !@Sync 16
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2419): [PWL] Off : 455s ago
,E/Watchdog( 2419): !@Sync 17
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2419): GC_CONCURRENT freed 4300K, 74% free 25269K/95632K, paused 8ms+19ms, total 213ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 203ms
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 18
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 19
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 525s ago
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 20
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2419): !@Sync 21
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9146
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9151
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9161
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9164
,W/ProcessCpuTracker( 2419): Skipping unknown process pid 9167
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
,D/Sensors ( 2419): LightSensor setDelay = 200000000
D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
I/PowerManagerService( 2419): [PWL] Off : 600s ago
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/GAV2    ( 5629): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5629): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2419): !@Sync 22
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 23
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 24
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 680s ago
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 25
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2890K, 30% free 9728K/13776K, paused 5ms+3ms, total 66ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 26
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 27
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 765s ago
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 28
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 29
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 30
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 31
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 4064K, 74% free 25052K/95632K, paused 19ms+16ms, total 226ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 32
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 33
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2419): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 34
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 35
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 36
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 37
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 38
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 39
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 40
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4,
,E/Watchdog( 2419): !@Sync 41
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 42
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
,D/Sensors ( 2419): LightSensor enable = 1
,D/Sensors ( 2419): LightSensor enableSensor = 1
,D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  ,
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5535): [b] __PingReply__
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 43
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2419): [PWL] Off : 1265s ago
,E/Watchdog( 2419): !@Sync 44
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 45
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 46
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3789K, 74% free 25072K/95280K, paused 21ms+19ms, total 260ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 47
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 48
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 49
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4075): GC_CONCURRENT freed 2048K, 30% free 9725K/13776K, paused 12ms+2ms, total 44ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 50
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 51
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 52
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5535): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,I/EventLogService( 3566): Aggregate from 1452266747141 (log), 1452266747141 (data)
,D/dalvikvm( 3566): GC_CONCURRENT freed 2177K, 21% free 12677K/16008K, paused 7ms+9ms, total 103ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/SPPClientService( 5535): [b] __PingReply__
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 53
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 54
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 55
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1625s ago
,E/Watchdog( 2419): !@Sync 56
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 57
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2771): GC_CONCURRENT freed 7389K, 36% free 18952K/29236K, paused 14ms+8ms, total 87ms
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 58
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 59
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2419): GC_CONCURRENT freed 3762K, 74% free 25129K/95280K, paused 18ms+19ms, total 255ms
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2419): !@Sync 60
,I/PowerManagerService( 2419): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 61
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2419): Prepared write state in 44ms
,I/ProcessStatsService( 2419): Prepared write state in 43ms
,I/ProcessStatsService( 2419): Pruning old procstats: /data/system/procstats/state-2016-01-07-20-24-00.bin
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 62
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :4
,V/NetworkStats( 2419): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/AlarmManager( 2419): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): performPollLocked() took 57ms
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/SELinux (12060): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12060):  
,I/SELinux (12060): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12060):  
I/SELinux (12060):  
,I/SELinux (12060): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (12060): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(12060): >>>>> Normal User
,E/dalvikvm(12060): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (12060): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(12060): in addTimaSignatureService
,D/TimaKeyStoreProvider(12060): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(12060): Added TimaKesytore provider
,D/dalvikvm(12060): GC_CONCURRENT freed 3015K, 31% free 9562K/13732K, paused 3ms+2ms, total 27ms
,D/dalvikvm(12060): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/@ WidgetProvider(12060): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(12060): onUpdate called for widgetId : 0
,D/@ WidgetProvider(12060): Widget random data : 9
,D/@ WidgetProvider(12060): onUpdate called for widgetId : 5
,D/@ WidgetProvider(12060): Widget random data : 8
,E/dalvikvm(12060): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(12060): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12060): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12060): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12060): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12060): VFY: replacing opcode 0x22 at 0x0038
,E/dalvikvm(12060): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(12060): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12060): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(12060): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(12060): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(12060): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(12060): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
,D/dalvikvm(12060): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(12060): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(12060): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,D/LightsService( 2419): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2419): getReportingMode :: sensor.mType = 5
D/Sensors ( 2419): LightSensor setDelay = 200000000
D/Sensors ( 2419): LightSensor setSensorDelay = 200000000
D/Sensors ( 2419): Light sensor flush: not enabled 0
D/Sensors ( 2419): LightSensor enable = 1
D/Sensors ( 2419): LightSensor enableSensor = 1
D/SensorManager( 2419): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2849): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(12060): Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(12060): Thread-675(ApacheHTTPLog):isShipBuild true
,I/System.out(12060): Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2419): LightSensor enable = 0
,D/Sensors ( 2419): LightSensor enableSensor = 0
,D/SensorManager( 2419): unregisterListener ::   
D/LightsService( 2419): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2419): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/System.out(12060): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(12060): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(12060): Max ALLOWED memory (MB): 128
V/ImageManager(12060): Max SHOULD USE memory (MB): 128
,V/ImageManager(12060): Max Image Cache memory (MB): 32
,D/skia    (12060): getTotalSize : Do not get file length
,D/@ WidgetProvider(12060): Building widget : 5
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 63
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2419): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2419): <AppSync3 Whitelist>
,V/AlarmManager( 2419): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 64
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2419): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2419): !@Sync 65
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
I/ActivityManager( 2419): Killing 6440:com.sec.knox.bridge/1000 (adj 15): empty for 1823s
,I/ActivityManager( 2419): Killing 4865:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1823s
,I/ActivityManager( 2419): Killing 6424:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1823s
,I/ActivityManager( 2419): Killing 6400:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1833s
,I/ActivityManager( 2419): Killing 6741:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1833s
,I/ActivityManager( 2419): Killing 6727:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6715:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6703:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6690:com.samsung.helphub/1000 (adj 15): empty for 1834s
,I/ActivityManager( 2419): Killing 6677:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6664:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6651:com.sec.android.service.cm/u0a82 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6359:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1835s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2419): Killing 5693:com.android.mms/u0a49 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6625:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1835s
,I/ActivityManager( 2419): Killing 6001:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1836s
,I/ActivityManager( 2419): Killing 6593:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1836s
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/CountryDetector( 2419): No listener is left
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 66
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2419): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 67
,V/AlarmManager( 2419): waitForAlarm result :8
,V/AlarmManager( 2419): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2419): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 274, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2419): !@Sync 68
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2419): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2419): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2419): mCoverManager.getCoverState() : true
,V/HeadsetService( 4001): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4001): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1800000ms)
```
