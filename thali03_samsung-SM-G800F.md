#### Test 5497026186051be_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2397): stay LED for fully charged
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/UiModeManager( 2397): mCoverManager.getCoverState() : true
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4006): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime( 7241): 
D/AndroidRuntime( 7241): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7241): CheckJNI is OFF
D/AndroidRuntime( 7241): setted country_code = Poland
D/AndroidRuntime( 7241): setted countryiso_code = PL
D/AndroidRuntime( 7241): setted sales_code = PLS
D/AndroidRuntime( 7241): readGMSProperty: start
D/AndroidRuntime( 7241): readGMSProperty: already setted!!
D/AndroidRuntime( 7241): readGMSProperty: end
D/AndroidRuntime( 7241): addProductProperty: start
D/dalvikvm( 7241): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7241): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7241): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7241): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7241): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7241): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7241): failed to load memtrack module: -2
D/dalvikvm( 7241): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7241): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2397): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.acquire()
I/SELinux ( 7254): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7254):  
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7241): Shutting down VM
D/dalvikvm( 7241): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7254): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7254):  
I/SELinux ( 7254):  
I/SELinux ( 7254): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7254): >>>>> Normal User
E/dalvikvm( 7254): >>>>> com.test.thalitest [ userId:0 | appId:10607 ]
E/SELinux ( 7254): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7254): in addTimaSignatureService
D/TimaKeyStoreProvider( 7254): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7254): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4164): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4164): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1919): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1919): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7254): GC_CONCURRENT freed 2993K, 30% free 9565K/13664K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7254): Binding Chromium to the background looper Looper (main, tid 1) {426a8400}
I/chromium( 7254): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7254): Initializing chromium process, renderers=0
,W/chromium( 7254): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7254): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7254): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7254): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7254): Mali API Version : 401
,I/Mali    ( 7254): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7254): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7254): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7254): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7254): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7254): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7254): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2579): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2397): tr p:7254,o:f
,W/dalvikvm( 7254): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7254): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7254): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7254): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7254): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7254): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7254): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7254): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7254): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7254): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7254): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7254): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7254): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2397): semi p:7254,o:f
D/PhoneStatusBar( 2579): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1919): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7254): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7254): Enabling debug mode 0
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 7254): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7254): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7254): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7254): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426a91c8
,D/dalvikvm( 7254): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x426a91c8
D/jxcore_app_log( 7254): JniHelper::setJavaVM(0x41c38220), pthread_self() = 2027569912
,D/JX-Cordova( 7254): jxcore cordova android initializing
,D/dalvikvm( 7254): GC_CONCURRENT freed 1302K, 18% free 11336K/13736K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/dalvikvm( 7254): GC_CONCURRENT freed 1898K, 17% free 14951K/17968K, paused 2ms+2ms, total 40ms
,D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 310, Delta = 0
,D/dalvikvm( 7254): GC_FOR_ALLOC freed 5335K, 30% free 16239K/22904K, paused 50ms, total 50ms
,D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 7254): GC_CONCURRENT freed 6717K, 31% free 17693K/25532K, paused 1ms+9ms, total 56ms
,D/dalvikvm( 7254): WAIT_FOR_CONCURRENT_GC blocked 46ms
,D/dalvikvm( 7254): GC_FOR_ALLOC freed 1270K, 32% free 17464K/25532K, paused 51ms, total 51ms
,I/dalvikvm-heap( 7254): Grow heap (frag case) to 21.642MB for 3688532-byte allocation
,D/dalvikvm( 7254): GC_FOR_ALLOC freed 2403K, 36% free 18662K/29136K, paused 47ms, total 47ms
,W/jxcore-log( 7254): Initializing JXcore engine
,W/jxcore-log( 7254): JXcore engine is ready
,W/jxcore-log( 7254): Starting JXcore engine
,W/jxcore-log( 7254): Platform android
W/jxcore-log( 7254): 
,W/jxcore-log( 7254): Process ARCH arm
W/jxcore-log( 7254): 
,I/jxcore-log( 7254): JXcore Cordova bridge is ready!
I/jxcore-log( 7254): 
,W/jxcore-log( 7254): JXcore engine is started
,I/chromium( 7254): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7254): Toggling radios to true
I/jxcore-log( 7254): 
,D/BluetoothAdapter( 7254): enable(): BT is already enabled..!
,I/WifiManager( 7254): packageName : com.test.thalitest
,I/WifiManager( 7254): setWifiEnabled : true
,I/WifiService( 2397): setWifiEnabled: true pid=7254, uid=10607
W/ActivityManager( 2397): Permission Denial: getCurrentUser() from pid=7254, uid=10607 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2397): Failed getting userId using ActivityManagerNative
W/WifiService( 2397): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7254, uid=10607 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2397): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2397): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2397): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2397): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2397): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2397): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2397): disconnect: pid=7254, uid=10607
,I/jxcore-log( 7254): Radios toggled
I/jxcore-log( 7254): 
,I/wpa_supplicant( 3967): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7254): My device name is: samsung-SM-G800F
I/jxcore-log( 7254): 
,I/wpa_supplicant( 3967): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3967): First Scan Start
,W/Settings( 2397): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2397): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3967): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
I/wpa_supplicant( 3967): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3967): Skip scan - already scanning
D/ConnectivityService( 2397): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2397): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2397): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2397): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2397): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2397): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2397): InactiveState{ what=143375 }
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2397): Attempting to switch to mobile
,I/SELinux ( 7300): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7300):  
D/ConnectivityService( 2397): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-IconMerger( 2579): checkOverflow(336), More:false, Req:false Child:3
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1914): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2397): Error! unhandled message{ when=-47ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2397): Error! unhandled message{ when=-47ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1914): RTNETLINK answers: No such process
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1914): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2397): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/SELinux ( 7300): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7300):  
I/SELinux ( 7300):  
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,I/SELinux ( 7300): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7300): >>>>> Normal User
,E/dalvikvm( 7300): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7300): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,W/NetworkManagementService( 2397): route cmd failed: 
W/NetworkManagementService( 2397): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2397): '
W/NetworkManagementService( 2397): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2397): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2397): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2397): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2397): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2397): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2397): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2397): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2397): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2397): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2397): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2397): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2397): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1914): /system/bin/ip -4 route del default table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
,D/TimaKeyStoreProvider( 7300): in addTimaSignatureService
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7300): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7300): Added TimaKesytore provider
,D/NetUtils( 2397): android_net_utils_resetConnections in env=0x7ba51e30 clazz=0x62500001 iface=wlan0 mask=0x3
D/ConnectivityService( 2397): resetConnections(wlan0, 3)
,V/NativeCrypto( 2833): Read error: ssl=0x7bae9428: I/O error during system call, Connection timed out
,V/NativeCrypto( 2833): SSL shutdown failed: ssl=0x7bae9428: I/O error during system call, Broken pipe
,E/SPPClientService( 5587): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,E/SPPClientService( 5587): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5587): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5587): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5587): [b] ResponseMap empty
,D/dalvikvm( 7300): GC_CONCURRENT freed 2990K, 30% free 9579K/13668K, paused 7ms+2ms, total 34ms
,D/dalvikvm( 7300): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/System.out( 7300): Inside WakeupProvider
,I/System.out( 7300): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): updateIfacesLocked()
,V/NetworkStats( 2397): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
D/ConnectivityService( 2397): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2397): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/VlingoApplication( 7300): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7300): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7300): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): performPollLocked() took 19ms
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4748): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4748): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4748): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2397): Killing 6222:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/DialogFlow( 7300): initQueue()
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4748): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4748): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4748): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2397): updateDataUsageMap
,D/Tethering( 2397): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2397): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2397): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4778): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
I/PCWCLIENTTRACE_PushUtil( 6690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6690): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6690): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6690): noConnectivity : true
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7329): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7329):  
,I/SELinux ( 7329): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7329):  
I/SELinux ( 7329):  
,I/SELinux ( 7329): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7329): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7329): >>>>> Normal User
,E/dalvikvm( 7329): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7329): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7329): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7329): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7329): Added TimaKesytore provider
,D/dalvikvm( 7329): GC_CONCURRENT freed 3011K, 31% free 9556K/13672K, paused 1ms+1ms, total 18ms
,D/dalvikvm( 7329): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/wpa_supplicant( 3967): nl80211: Received scan results (7 BSSes)
,I/wpa_supplicant( 3967): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3967): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/ActivityManager( 2397): Killing 6291:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): Associated with C0.AA.48
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3967): freq(2412) increment count 2
,I/wpa_supplicant( 3967): meet head of list.
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2397): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3967): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3967): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3967): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2397): interfaceLinkStateChanged wlan0, true
D/Tethering( 2397): interfaceStatusChanged wlan0, true
,D/WifiNative( 2397): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiP2pService( 2397): InactiveState{ what=143375 }
,D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
,I/SELinux ( 7343): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7343):  
,D/dalvikvm( 1920): GC_EXPLICIT freed 43K, 11% free 9501K/10648K, paused 4ms+3ms, total 36ms
,I/SELinux ( 7343): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7343):  
I/SELinux ( 7343):  
,I/SELinux ( 7343): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7343): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7343): >>>>> Normal User
,E/dalvikvm( 7343): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7343): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9501K/10648K, paused 2ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 7343): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7343): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7343): Added TimaKesytore provider
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9501K/10648K, paused 3ms+4ms, total 30ms
,D/dalvikvm( 7343): GC_CONCURRENT freed 3005K, 31% free 9564K/13672K, paused 2ms+2ms, total 22ms
,D/dalvikvm( 7343): WAIT_FOR_CONCURRENT_GC blocked 19ms
,I/dhcpcd  ( 7355): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7355): bssid match
I/ActivityManager( 2397): Killing 6344:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7362): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7362):  
,I/SELinux ( 7362): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7362):  
I/SELinux ( 7362):  
,I/SELinux ( 7362): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7362): >>>>> Normal User
,E/dalvikvm( 7362): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7362): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7362): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7362): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7362): Added TimaKesytore provider
,D/dalvikvm( 7362): GC_CONCURRENT freed 2990K, 30% free 9575K/13668K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7362): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/KLMS-2.3.201 : ( 7362): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7362): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452511955722
,I/KLMS-2.3.201 : ( 7362): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2397): Killing 6366:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7393):  
,D/WifiP2pService( 2397): InactiveState{ what=143375 }
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
I/SELinux ( 7393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7393):  
I/SELinux ( 7393):  
I/SELinux ( 7393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection...
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7393): >>>>> Normal User
,E/dalvikvm( 7393): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,D/WifiP2pService( 2397): P2pEnabledState{ what=143375 }
E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/WifiStateMachine( 2397): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/TimaKeyStoreProvider( 7393): in addTimaSignatureService
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/TimaKeyStoreProvider( 7393): Cannot add TimaSignature Service, License check Failed
D/WifiStateMachine( 2397): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/ActivityThread( 7393): Added TimaKesytore provider
D/WifiStateMachine( 2397): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2397): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2397): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2397): evaluateTrafficStatsPolling
,D/ConnectivityService( 2397): ConnectivityChange for WIFI: CONNECTED/CONNECTED,
E/ConnectivityService( 2397): net.tcp.usercfg.wifi not found in system properties. Using defaults
,E/ConnectivityService( 2397): net.tcp.delack.wifi not found in system properties. Using defaults,
,D/STATUSBAR-NetworkController( 2579): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2579): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2579): refreshSignalCluster: data=-1 bt=false,
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/ConnectivityService( 2397): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1914): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
D/dalvikvm( 7393): GC_CONCURRENT freed 2994K, 30% free 9575K/13672K, paused 7ms+2ms, total 34ms
,D/dalvikvm( 7393): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
V/RouteController( 1914): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
D/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1914): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2397): updateIfacesLocked(),
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,V/NetworkStats( 2397): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
V/NetworkStats( 2397): performPollLocked() took 19ms
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2397): currentTimeMillis() cache hit
,I/SA      ( 5855): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5855): [BDLM] already registered in spp
,I/SA      ( 5855): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
I/SA      ( 5855): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5855): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5855): [OR] == isSIMCardReady false ==
I/SA      ( 5855): [SCU] == networkStateCheck == true
I/SA      ( 5855): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5855): isChinaCountryCode : false
,I/SA      ( 5855): [OR] == networkStateCheck true ==
,I/SA      ( 5855): [OR] GetMyCountryZoneTask
,I/SA      ( 5855): [OR] onReceive END
,I/SA      ( 5855): [SRS] prepareGetMyCountryZone
,I/SA      ( 5855): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5855): [SSP] query invoked
I/ActivityManager( 2397): Killing 6379:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SA      ( 5855): [TPMU] GetMccFromDB : null
,I/SA      ( 5855): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5855): [TPM] isNoProxy(default) : true
,I/SA      ( 5855): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SELinux ( 7426): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7426):  
,I/SELinux ( 7426): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7426):  
I/SELinux ( 7426):  
,I/SELinux ( 7426): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7426): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7426): >>>>> Normal User
,E/dalvikvm( 7426): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7426): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7426): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7426): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7426): Added TimaKesytore provider
,D/dalvikvm( 7426): GC_CONCURRENT freed 2991K, 30% free 9576K/13668K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7426): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/sCloudBackupApp( 7426): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7426): Other Intent
I/ActivityManager( 2397): Killing 6437:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SELinux ( 7439): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7439):  
,I/SELinux ( 7439): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7439):  
I/SELinux ( 7439):  
,I/SELinux ( 7439): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7439): >>>>> Normal User
,E/dalvikvm( 7439): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7439): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7439): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7439): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7439): Added TimaKesytore provider
,D/Tethering( 2397): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2397): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2397): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2579): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2579): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2579): updateDataNetType()
D/STATUSBAR-NetworkController( 2579): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4778): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/dalvikvm( 7439): GC_CONCURRENT freed 3002K, 31% free 9570K/13672K, paused 2ms+2ms, total 62ms
,D/dalvikvm( 7439): WAIT_FOR_CONCURRENT_GC blocked 57ms
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7439): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7439): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5385): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7439): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5385): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7439): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5385): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2397): Killing 5637:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/Headlines( 5918): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5918): getCountryCode(): countryCode = PL
,D/Headlines( 5918): Breath.onCreate
,D/Headlines( 5918): Breath timer started. interval : 30000
,I/SELinux ( 7452): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7452):  
,V/AlarmManager( 2397): waitForAlarm result :8
D/Headlines( 5918): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5918): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5918): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5918): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7452): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7452):  
I/SELinux ( 7452):  
,I/SELinux ( 7452): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7452): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7452): >>>>> Normal User
,E/dalvikvm( 7452): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7452): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,D/TimaKeyStoreProvider( 7452): in addTimaSignatureService
,E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/TimaKeyStoreProvider( 7452): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7452): Added TimaKesytore provider
,I/SA      ( 5855): [RC New] [v2liruge] api execute + 744
,I/SA      ( 5855): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5855): AsyncTask #2 calls detatch()
,I/SA      ( 5855): [TPMU] getNetworkMcc : 
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection...
,I/SA      ( 5855): [SCU] saveMccToPreferece Start
I/SA      ( 5855): [SCU] RegionMCC : 260
,I/SA      ( 5855): [SSP] query invoked
,I/SA      ( 5855): [TPMU] GetMccFromDB : null
I/SA      ( 5855): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5855): [SCU] saveMccToPreferece End
I/SA      ( 5855): [RC New] executeRequest [v2liruge] end. 780
,I/SA      ( 5855): [RC New] Execute end
I/SA      ( 5855): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5855): [OR] GetMyCountryZoneTask Success
,D/dalvikvm( 7452): GC_CONCURRENT freed 2999K, 30% free 9571K/13672K, paused 9ms+2ms, total 35ms
,D/dalvikvm( 7452): WAIT_FOR_CONCURRENT_GC blocked 21ms
,V/WebViewChromium( 7452): Binding Chromium to the background looper Looper (main, tid 1) {426a50c8}
,I/chromium( 7452): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7452): Initializing chromium process, renderers=0
,W/chromium( 7452): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7452): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7452): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7452): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7452): Mali API Version : 401
,I/Mali    ( 7452): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7452): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7452): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7452): Starting up...
,I/iu.Environment( 5986): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5187): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5187): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5187): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@426b2428
,I/SELinux ( 7490): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7490):  
,I/SELinux ( 7490): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7490):  
I/SELinux ( 7490):  
,I/SELinux ( 7490): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7490): >>>>> Normal User
,E/dalvikvm( 7490): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7490): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7490): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7490): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7490): Added TimaKesytore provider
,D/dalvikvm( 7490): GC_CONCURRENT freed 2985K, 30% free 9581K/13664K, paused 2ms+2ms, total 20ms
,D/dalvikvm( 7490): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,I/SELinux ( 7509): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7509):  
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
I/ActivityManager( 2397): Killing 6325:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7509): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7509):  
I/SELinux ( 7509):  
,I/SELinux ( 7509): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7509): >>>>> Normal User
,E/dalvikvm( 7509): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7509): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7519): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7519):  
,D/TimaKeyStoreProvider( 7509): in addTimaSignatureService
W/ActivityManager( 2397): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7509): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7509): Added TimaKesytore provider
,I/ActivityManager( 2397): Killing 6396:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7519): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7519):  
I/SELinux ( 7519):  
,I/SELinux ( 7519): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7519): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7519): >>>>> Normal User
,E/dalvikvm( 7519): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7519): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7519): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7519): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7519): Added TimaKesytore provider
,D/dalvikvm( 7509): GC_CONCURRENT freed 3013K, 31% free 9557K/13672K, paused 2ms+1ms, total 20ms
,D/dalvikvm( 7509): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/BadgeProvider( 7509): onCreate
,D/BadgeProvider( 7509): DatabaseHelper
,D/BadgeProvider( 7509): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7509): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 2785): reloadBadges entered.
D/BadgeProvider( 7509): sendNotify, [notify] : null
D/BadgeProvider( 7509): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7509): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7509): update, [UpdateCount] : 1
,D/dalvikvm( 7519): GC_CONCURRENT freed 2993K, 30% free 9575K/13672K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7519): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/libgps  ( 2397): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection...
,D/hcjo    ( 6008): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 6008): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 6008): exit::IDLE
,D/InitializeManagerStateMachine( 6008): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 6008): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6008): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6008): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6008): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6008): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6008): entry::SUCCESS
,D/hcjo    ( 6008): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6008): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6008): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6008): exit::SUCCESS
,D/InitializeManagerStateMachine( 6008): entry::IDLE
,E/SPPClientService( 5587): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5587): [SystemStateMoniter] Current Time : 276668
,E/SPPClientService( 5587): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5587): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4748): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4748): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4748): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5587): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5587): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 4748): MountReceiver.onReceive - Keep current state
I/ActivityManager( 2397): Killing 6036:com.android.calendar/u0a144 (adj 15): empty #43
,E/SPPClientService( 5587): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4748): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4748): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4748): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5587): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4376, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/dalvikvm( 2397): GC_EXPLICIT freed 3959K, 71% free 25486K/86184K, paused 7ms+53ms, total 231ms
D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
,D/NearbySettings( 4748): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true
,I/NearbySettings( 4748): MountReceiver.onReceive - Keep current state
,D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
I/SurfaceFlinger( 1919): id=20 createSurf (1x1),1 flag=4, Uoast
D/HeadsetStateMachine( 4006): Disconnected process message: 10
,D/PowerManagerService( 2397): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2397
,I/PCWCLIENTTRACE_PushUtil( 6690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6690): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6690): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/SPPClientService( 5587): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5587): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5587): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7362): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7362): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452511958570
,I/KLMS-2.3.201 : ( 7362): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3468): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3468): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7393): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3596): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7546): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7546):  
,I/SA      ( 5855): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5855): [BDLM] already registered in spp
,I/SA      ( 5855): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5855): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5855): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5855): [OR] == isSIMCardReady false ==
,I/SA      ( 5855): [SCU] == networkStateCheck == true
I/SA      ( 5855): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5855): isChinaCountryCode : false
I/SA      ( 5855): [OR] == networkStateCheck true ==
,I/SA      ( 5855): [OR] GetMyCountryZoneTask
I/SA      ( 5855): [OR] onReceive END
I/SELinux ( 7546): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7546):  
I/SELinux ( 7546):  
I/SELinux ( 7546): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7546): >>>>> Normal User
E/dalvikvm( 7546): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
E/SELinux ( 7546): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SA      ( 5855): [SRS] prepareGetMyCountryZone
I/SA      ( 5855): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5855): [SSP] query invoked
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,D/TimaKeyStoreProvider( 7546): in addTimaSignatureService
,I/SA      ( 5855): [TPMU] GetMccFromDB : null
,I/SA      ( 5855): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5855): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver( 7426): Other Intent
,D/TimaKeyStoreProvider( 7546): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5855): [RC New] Execute method=[GET] start
,D/ActivityThread( 7546): Added TimaKesytore provider
,I/SELinux ( 7562): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7562):  
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
I/SELinux ( 7562): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7562):  
I/SELinux ( 7562):  
,I/SELinux ( 7562): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7562): >>>>> Normal User
,E/dalvikvm( 7562): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7562): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/com.samsung.app( 7439): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 7562): in addTimaSignatureService
,D/dalvikvm( 7546): GC_CONCURRENT freed 2997K, 30% free 9572K/13668K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 7546): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/TimaKeyStoreProvider( 7562): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7562): Added TimaKesytore provider
D/Headlines( 5918): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5918): getCountryCode(): countryCode = PL
,D/Headlines( 5918): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5918): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5918): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5918): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5918): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5986): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5187): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5187): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5187): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@426b2428
,D/dalvikvm( 7562): GC_CONCURRENT freed 3006K, 31% free 9559K/13668K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7562): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/libgps  ( 2397): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2397): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2397): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,D/RCPManagerService( 2397): exchangeData() failure , invalid userId
,I/System.out( 7343): Thread-639(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,V/KVNProvider( 7562): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7562): getFindoCursor query string : 
,V/KVNProvider( 7562): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 6008): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 6008): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6008): exit::IDLE
,D/InitializeManagerStateMachine( 6008): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6008): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6008): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6008): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6008): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6008): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6008): entry::SUCCESS
,D/hcjo    ( 6008): AutoUpdateManager:INITCHECK:onInitializeSuccess
,I/System.out( 7343): Thread-639(ApacheHTTPLog):isShipBuild true
,I/System.out( 7343): Thread-639(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/hcjo    ( 6008): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6008): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6008): exit::SUCCESS
,D/InitializeManagerStateMachine( 6008): entry::IDLE
,E/SPPClientService( 5587): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5587): [SystemStateMoniter] Current Time : 277794
,E/SPPClientService( 5587): [SystemStateMoniter] No Connect : false
,D/Headlines( 5918): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5918): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5918): Breath 266 latestRequest time : 1452511958855 current time : 1452511959121
,E/WifiStateMachine( 2397): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/System.out( 7343): AsyncTask #1 calls detatch()
,I/SA      ( 5855): [RC New] [v2liruge] api execute + 514
,I/SA      ( 5855): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5855): AsyncTask #3 calls detatch()
,I/SA      ( 5855): [TPMU] getNetworkMcc : 
,I/SA      ( 5855): [SCU] saveMccToPreferece Start
,I/SA      ( 5855): [SCU] RegionMCC : 260
,I/SA      ( 5855): [SSP] query invoked
,W/System.err( 7343): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7343): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
I/SA      ( 5855): [TPMU] GetMccFromDB : null
I/SA      ( 5855): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5855): [SCU] saveMccToPreferece End
,I/SA      ( 5855): [RC New] executeRequest [v2liruge] end. 537
,I/SA      ( 5855): [RC New] Execute end
I/SA      ( 5855): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5855): [OR] GetMyCountryZoneTask Success
,W/System.err( 7343): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
,W/System.err( 7343): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7343): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7343): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7343): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7343): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7343): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7343): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7343): Caused by: java.lang.NullPointerException
,W/System.err( 7343): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7343): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7343): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7343): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7343): 	... 8 more
,I/ActivityManager( 2397): Killing 6207:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/dalvikvm( 5587): GC_CONCURRENT freed 2018K, 24% free 10439K/13652K, paused 9ms+3ms, total 56ms
,D/PackageManager( 2397): [MSG] WRITE_PACKAGE_RESTRICTIONS
,W/WifiP2pStateTracker( 2397): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2397): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2397):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2397): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2397): updateSourceRoutes : no source routing conditions
,E/SPPClientService( 5587): [b] __InitReply__
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 20
,I/SurfaceFlinger( 1919): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1919): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2397): Killing 6244:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2397): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2397) eventTime = 280308
D/PowerManagerService( 2397): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2397 (0x0)
D/PowerManagerService( 2397): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2397, ws=WorkSource{1000}) (elapsedTime=3261)
,D/AmoledAdjustTimer( 2397): prevTemp = 283, currTemp = 284, prevStep = 4, currStep = 4
,I/GAV2    ( 7452): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6690): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6690): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6690): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6690): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6690): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6690): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6690): [ensureRegistration] - No Samsung account
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2397): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2397): Checking http://216.58.209.78/generate_204
D/ConnectivityService( 2397): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2397): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2397): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2397): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2397): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2397): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7254): Test app app.js loaded
I/jxcore-log( 7254): 
,I/chromium( 7254): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7254): --= Surplus to requirements =--
I/jxcore-log( 7254): 
,I/jxcore-log( 7254): ****TEST TOOK:  ms ****
I/jxcore-log( 7254): 
,I/jxcore-log( 7254): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7254): 
,D/PreloadUpdateManagerStateMachine( 6008): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6008): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6008): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 6008): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6008): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT,
,D/PreloadUpdateManagerStateMachine( 6008): exit::CHECK_TIMEOUT_FOR_UPDATE,
,D/PreloadUpdateManagerStateMachine( 6008): entry::IDLE
,D/BatteryService( 2397): level:100, scale:100, status:5, health:2, present:true, voltage: 4390, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2397): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2397): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2579): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2397): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2579): handleBatteryUpdate
V/HeadsetService( 4006): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4006): Disconnected process message: 10,
D/STATUSBAR-PhoneStatusBar( 2579):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2579): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2579): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AndroidRuntime( 7592): 
D/AndroidRuntime( 7592): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<,
,D/AndroidRuntime( 7592): CheckJNI is OFF
,D/AndroidRuntime( 7592): setted country_code = Poland
,D/AndroidRuntime( 7592): setted countryiso_code = PL
D/AndroidRuntime( 7592): setted sales_code = PLS
D/AndroidRuntime( 7592): readGMSProperty: start
,D/AndroidRuntime( 7592): readGMSProperty: already setted!!
D/AndroidRuntime( 7592): readGMSProperty: end
,D/AndroidRuntime( 7592): addProductProperty: start,
,D/dalvikvm( 7592): Trying to load lib libjavacore.so 0x0,
,D/dalvikvm( 7592): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7592): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 7592): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7592): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init,
,E/memtrack( 7592): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7592): failed to load memtrack module: -2
,D/dalvikvm( 7592): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods,
,D/AndroidRuntime( 7592): Calling main entry com.android.commands.pm.Pm,
,D/PackageManager( 2397): START PACKAGE DELETE: observer{1121460224}
D/PackageManager( 2397): pkg{<packageName>},
D/PackageManager( 2397): user{0}
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled,
D/ApplicationPolicy( 2397): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2397): deletePackageX- pkg:com.test.thalitest, userId:0,
D/PackageManager( 2397): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2397): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2397): !@killApplicatoin: 10607, uninstall pkg,
,I/ActivityManager( 2397): Killing 7254:com.test.thalitest/u0a607 (adj 0): stop com.test.thalitest,
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@4,
,W/ActivityManager( 2397): mDVFSHelper.acquire(),
,I/SurfaceFlinger( 1919): id=19 Removed NainActivit (8/10),
,I/SurfaceFlinger( 1919): id=19 Removed NainActivit (-2/10),
,I/WindowState( 2397): WIN DEATH: Window{43445f98 u0 com.test.thalitest/com.test.thalitest.MainActivity},
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2397): Skipping PackageSetting{42f651d8 com.example.hello/10600} due to missing metadata,
,D/PackageManager( 2397): setPackageStoppedState - Execution time: 105 ms
D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10607, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6478): GC_EXPLICIT freed 2488K, 28% free 9883K/13668K, paused 3ms+4ms, total 49ms
,D/dalvikvm( 3309): GC_EXPLICIT freed 1747K, 20% free 12422K/15480K, paused 4ms+7ms, total 89ms
,D/dalvikvm( 6854): GC_EXPLICIT freed 159K, 29% free 9957K/13888K, paused 3ms+4ms, total 84ms
,D/dalvikvm( 2957): GC_EXPLICIT freed 1214K, 19% free 10033K/12348K, paused 7ms+5ms, total 78ms
D/PackageManager( 2397): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10607, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/PreloadUpdateManagerStateMachine( 6008): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6008): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6008): entry::CHECK_TIMEOUT_FOR_UPDATE
,I/DBG_DM  ( 4778): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4778): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29,
,I/InputReader( 2397): Reconfiguring input devices.  changes=0x00000010,
,E/SamsungIME( 2975): mOCRHelper is null,
,D/QuickConnect[1.1][2] ( 5187): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest,
,I/DBG_DM  ( 4778): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0,
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms",
,I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/SELinux ( 7604): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7604):  
,I/DBG_DM  ( 4778): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0,
,I/DBG_DM  ( 4778): [3.19.140541][Line:418][onResume] Postpone Count : 29,
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto",
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1920): GC_EXPLICIT freed 42K, 11% free 9501K/10648K, paused 2ms+3ms, total 31ms,
,E/Watchdog( 2397): !@Sync 9,
I/SELinux ( 7604): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7604):  
I/SELinux ( 7604):  
,I/SELinux ( 7604): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7604): >>>>> Normal User
,E/dalvikvm( 7604): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ],
,E/SELinux ( 7604): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9501K/10648K, paused 2ms+3ms, total 26ms
,I/DBG_DM  ( 4778): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
,W/GeofencerStateMachine( 2737): Ignoring removeGeofence because network location is disabled.
,D/RegisteredServicesCache( 2761): empty dynamic service
,D/hcjo    ( 6008): AutoUpdateTriggerManager:IDLE:notifyNextTime
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9501K/10648K, paused 3ms+3ms, total 26ms
,I/DBG_DM  ( 4778): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/TimaKeyStoreProvider( 7604): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7604): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7604): Added TimaKesytore provider
,D/PreloadUpdateManagerStateMachine( 6008): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,I/DBG_DM  ( 4778): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 2397): GC_EXPLICIT freed 2519K, 71% free 25123K/86184K, paused 11ms+19ms, total 292ms
,D/dalvikvm( 2397): WAIT_FOR_CONCURRENT_GC blocked 198ms
,D/PreloadUpdateManagerStateMachine( 6008): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6008): entry::IDLE
,I/DBG_DM  ( 4778): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4778): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4778): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4778): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4778): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4778): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4778): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4778): setTransGradationMode to true
,D/PhoneStatusBar( 2579): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,I/DBG_DM  ( 4778): [3.19.140541][Line:400][onPause] 
D/StatusBarManagerService( 2397): semi p:4778,o:t
,I/SurfaceFlinger( 1919): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms"
D/STATUSBAR-StatusBarManagerService( 2397): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/PointerIcon( 2397): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2397): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2397): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2397): setHoveringSpenCustomIcon IconType is same.1
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7604): GC_CONCURRENT freed 2997K, 30% free 9571K/13668K, paused 3ms+1ms, total 27ms
,D/dalvikvm( 7604): WAIT_FOR_CONCURRENT_GC blocked 14ms
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2397): PackageReceiver onReceive()
,D/elm:14132( 7604): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7604): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7604): MDMBridge.setEnterpriseBridge()
I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
,I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2397): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/dalvikvm( 2761): GC_CONCURRENT freed 2336K, 26% free 10254K/13688K, paused 9ms+2ms, total 86ms
,D/elm:14132( 7604): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7604): ElmAgentService : onCreate()
D/elm:14132( 7604): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7604): MainReceiver.listeningToPackageRemoved()
,I/SELinux ( 7617): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7617):  
,D/elm:14132( 7604): MDMBridge.getInstance()
,D/elm:14132( 7604): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7604): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7617): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7617):  
I/SELinux ( 7617):  
,I/SELinux ( 7617): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7617): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7617): >>>>> Normal User
,E/dalvikvm( 7617): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7617): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7604): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7604): ElmAgentService : onDestroy().
,I/ActivityManager( 2397): Killing 6635:com.android.defcontainer/u0a6 (adj 15): empty #43
D/TimaKeyStoreProvider( 7617): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7617): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7617): Added TimaKesytore provider
,D/dalvikvm( 7617): GC_CONCURRENT freed 2997K, 30% free 9571K/13668K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7617): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/InputMethodManagerService( 2397): Got RemoteException sending setActive(false) notification to pid 7254 uid 10607
,W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/EnterpriseDeviceManagerService( 2397): Package has changed for user 0
,D/dalvikvm( 2397): GC_EXPLICIT freed 862K, 71% free 25143K/86184K, paused 8ms+39ms, total 432ms
D/PackageManager( 2397): delete sourFile : 
,D/PackageManager( 2397): delete native library directory: 
,D/PackageManager( 2397): return delete result to caller: 1121460224
,D/AndroidRuntime( 7592): Shutting down VM
,D/PackageManager( 2397): returnCode: 1
D/dalvikvm( 7592): GC_CONCURRENT freed 96K, 14% free 667K/768K, paused 1ms+1ms, total 5ms
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "sms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2397): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2397): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/BackupManagerService( 2397): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2397): removePackageParticipantsLocked: uid=10607 #1
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7633): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7633):  
I/ActivityManager( 2397): Killing 6499:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "smsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ContextImpl( 2397): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
,D/STATUSBAR-StatusBarManagerService( 2397): sendNotification(2) - 4
I/SELinux ( 7633): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7633):  
I/SELinux ( 7633):  
I/SELinux ( 7633): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7633): >>>>> Normal User
E/dalvikvm( 7633): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux ( 7633): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mms"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7633): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7633): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7633): Added TimaKesytore provider
,I/PackageManager( 2397):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2397):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2397):   Scheme: "mmsto"
I/PackageManager( 2397): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7633): GC_CONCURRENT freed 2994K, 30% free 9567K/13664K, paused 5ms+2ms, total 49ms
,D/dalvikvm( 7633): WAIT_FOR_CONCURRENT_GC blocked 38ms
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime( 7633): Shutting down VM
,W/dalvikvm( 7633): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7633): FATAL EXCEPTION: main
E/AndroidRuntime( 7633): Process: com.sec.android.app.mss, PID: 7633
E/AndroidRuntime( 7633): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7633): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7633): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7633): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7633): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7633): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7633): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7633): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7633): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7633): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7633): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7633): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 7633): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 7633): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 7633): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 7633): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 7633): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 7633): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 7633): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 7633): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7633): 	... 10 more
,I/PCWCLIENTTRACE_PushUtil( 6690): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6690): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6690): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6690): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/Process ( 7633): Sending signal. PID: 7633 SIG: 9
,I/SA      ( 5855): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/ActivityManager( 2397): Process com.sec.android.app.mss (pid 7633) (adj 9) has died.
W/ApplicationsProvider( 2957): Could not fetch usage stats
W/ApplicationsProvider( 2957): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2957): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2957): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2957): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2957): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2957): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SA      ( 5855): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
E/SQLiteLog( 6051): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
W/dalvikvm( 6051): threadid=12: thread exiting with uncaught exception (group=0x41c4bc08)
,E/AndroidRuntime( 6051): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6051): Process: com.sec.android.app.shealth, PID: 6051
E/AndroidRuntime( 6051): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6051): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6051): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6051): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6051): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6051): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6051): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6051): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6051): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6051): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6051): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6051): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
E/SharedPreferencesImpl( 3596): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/Process ( 6051): Sending signal. PID: 6051 SIG: 9
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/Icing.InternalIcingCorporaProvider( 6478): Updating corpora: A: com.test.thalitest, C: MAYBE
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
E/SQLiteLog( 6478): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 6478): threadid=15: thread exiting with uncaught exception (group=0x41c4bc08)
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/AndroidRuntime( 6478): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6478): Process: com.google.android.googlequicksearchbox:search, PID: 6478
E/AndroidRuntime( 6478): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6478): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6478): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6478): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6478): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6478): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6478): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6478): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6478): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2397): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux ( 7656): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7656):  
I/ActivityManager( 2397): Process com.sec.android.app.shealth (pid 6051) (adj 5) has died.
I/Process ( 6478): Sending signal. PID: 6478 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/CrashAnrDetector( 2397): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2397): clearDefaults: com.test.thalitest
,W/AtomicFile( 2397): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
I/ActivityManager( 2397): Process com.google.android.googlequicksearchbox:search (pid 6478) (adj 5) has died.
W/AppWidgetServiceImpl( 2397): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
,I/SELinux ( 7656): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7656):  
I/SELinux ( 7656):  
,I/SELinux ( 7656): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7656): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7656): >>>>> Normal User
,E/dalvikvm( 7656): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7656): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7656): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7656): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7656): Added TimaKesytore provider
,D/dalvikvm( 7656): GC_CONCURRENT freed 2998K, 30% free 9569K/13668K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7656): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/UserAnalysis.PlaceProvider( 7656): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7656): Create SecureDbHelper
,E/SQLiteDatabase( 7656): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7656): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7656): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7656): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7656): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7656): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7656): Opened privacy in read-only mode
E/SQLiteDatabase( 7656): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7656): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7656): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7656): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7656): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7656): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7656): Opened privacy in read-only mode
E/SQLiteDatabase( 7656): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7656): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7656): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7656): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7656): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7656): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7656): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7656): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7656): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7656): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7656): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7656): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7656): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7656): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7656): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7656): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7656): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7656): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7656): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7656): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7656): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7656): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7656): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6410): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6493):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2397): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6760): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6760): The package(com.test.thalitest) removed
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
W/System.err( 2397): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2397): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2397): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2397): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2397): 	... 8 more
W/System.err( 2397): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2397): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2397): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2397): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2397): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2397): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2397): 	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6789): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6789): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 6789): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6789): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6789): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6789): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6789): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6789): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6789): threadid=10: thread exiting with uncaught exception (group=0x41c4bc08)
,I/SELinux ( 7671): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7671):  
,E/AndroidRuntime( 6789): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6789): Process: com.samsung.android.magazine.service, PID: 6789
E/AndroidRuntime( 6789): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6789): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6789): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6789): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6789): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6789): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6789): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6789): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6789): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6789): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6789): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6789): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6789): Sending signal. PID: 6789 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.samsung.android.magazine.service (pid 6789) (adj 5) has died.
,I/SELinux ( 7671): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7671):  
I/SELinux ( 7671):  
,I/SELinux ( 7671): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7671): >>>>> Normal User
,E/dalvikvm( 7671): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7671): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7671): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7671): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7671): Added TimaKesytore provider
,D/dalvikvm( 7671): GC_CONCURRENT freed 3008K, 31% free 9558K/13668K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7671): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ContextImpl( 7671): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7671): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7671): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7671): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7671): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7671): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7671): threadid=10: thread exiting with uncaught exception (group=0x41c4bc08)
,D/KidsModeInstallReceiver( 6816): onReceive intent data =  package:com.test.thalitest
,D/KidsPlatformStub( 6816): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7671): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7671): Process: com.android.keychain, PID: 7671
E/AndroidRuntime( 7671): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7671): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7671): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7671): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7671): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7671): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7671): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7671): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7671): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7671): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/Process ( 7671): Sending signal. PID: 7671 SIG: 9
,W/System.err( 6854): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6854): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6854): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6854): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6854): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6854): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
,W/System.err( 6854): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6854): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6854): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,W/System.err( 6854): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6854): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6854): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
,W/System.err( 6854): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6854): 	at dalvik.system.NativeStart.main(Native Method)
,I/ActivityManager( 2397): Process com.android.keychain (pid 7671) (adj 5) has died.
,D/PackageBroadcastService( 3309): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3309): Clearing selected account for com.test.thalitest
,E/SQLiteLog( 3309): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3309): Removing dialog suppression flag for package com.test.thalitest
D/ChimeraCfgMgr( 3309): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3309): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3309): disk I/O error (code 3850)
E/DriveAsyncService( 3309): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3309): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3309): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3309): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3309): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3309): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3309): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3309): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3309): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3309): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3309): 	at java.lang.Thread.run(Thread.java:841)
,D/ChimeraCfgMgr( 3309): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3309): Module APK com.google.android.play.games already loaded
,E/SQLiteDatabase( 3309): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3309): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3309): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3309): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3309): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3309): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 3309): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3309): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3309): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3309): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3309): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3309): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2833): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2833): Shutting down VM
,W/dalvikvm( 2833): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
,E/SQLiteLog( 3309): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/SQLiteOpenHelper( 3309): Opened metrics.db in read-only mode
,D/gH_CompatibleDatabase( 3309): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 3309): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/AndroidRuntime( 2833): FATAL EXCEPTION: main
E/AndroidRuntime( 2833): Process: com.google.process.gapps, PID: 2833
E/AndroidRuntime( 2833): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2833): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2833): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2833): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2833): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2833): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2833): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2833): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2833): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2833): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2833): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2833): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2833): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2833): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2833): 	... 10 more
E/SQLiteDatabase( 3309): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 33,09): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3309): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3309): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3309): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
D/gH_CompatibleDatabase( 3309): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3309): threadid=48: thread exiting with uncaught exception (group=0x41c4bc08)
E/PhenotypeInitializer( 3309): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3309): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3309): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3309): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3309): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3309): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3309): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3309): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3309): threadid=49: thread exiting with uncaught exception (group=0x41c4bc08)
,I/Process ( 3309): Sending signal. PID: 3309 SIG: 9
E/AndroidRuntime( 3309): FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
E/AndroidRuntime( 3309): Process: com.google.android.gms, PID: 3309
E/AndroidRuntime( 3309): android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
E/AndroidRuntime( 3309): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 3309): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 3309): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 3309): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 3309): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 3309): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:281)
E/AndroidRuntime( 3309): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/AndroidRuntime( 3309): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 3309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 3309): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 3309): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/Process ( 2833): Sending signal. PID: 2833 SIG: 9
,E/SQLiteDatabase( 5587): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5587): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5587): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5587): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5587): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5587): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5587): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5587): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5587): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5587): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5587): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5587): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5587): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5587): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5587): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5587): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5587): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5587): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5587): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
D/CustomFrequencyManagerService( 2397): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2397  tag : ACTIVITY_RESUME_BOOSTER@8
,E/SQLiteDatabase( 6454): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6454): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6454): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6454): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6454): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6454): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6454): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6454): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6454): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6454): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6454): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6454): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6454): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7697): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7697):  
D/GAV2    ( 5680): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5680): Thread[main,5,main]: Unexpected disconnect.
I/ActivityManager( 2397): Process com.google.process.gapps (pid 2833) (adj 5) has died.
,I/ActivityManager( 2397): Process com.google.android.gms (pid 3309) (adj 0) has died.
E/SQLiteDatabase( 6454): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6454): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6454): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6454): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6454): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6454): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6454): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6454): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6454): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6454): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6454): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6454): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6454): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6454): 	at dalvik.system.NativeStart.main(Native Method)
E/LNoti   ( 6454): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7697): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7697):  
I/SELinux ( 7697):  
,I/SELinux ( 7697): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7697): >>>>> Normal User
,E/dalvikvm( 7697): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7697): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7697): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7697): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7697): Added TimaKesytore provider
,D/SSRMv2:SIOP( 2397): SIOP:: AP = 330, Delta = 0
,D/dalvikvm( 7697): GC_CONCURRENT freed 3006K, 31% free 9560K/13668K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7697): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/Documents( 7697): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7697): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7697): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7697): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7697): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7697): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7697): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7697): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7697): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7697): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7697): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7697): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7697): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7697): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7697): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7697): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7697): Shutting down VM
,W/dalvikvm( 7697): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
,E/AndroidRuntime( 7697): FATAL EXCEPTION: main
E/AndroidRuntime( 7697): Process: com.android.documentsui, PID: 7697
E/AndroidRuntime( 7697): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7697): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7697): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7697): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7697): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7697): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7697): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7697): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7697): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7697): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7697): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7697): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7697): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7697): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7697): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7697): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7697): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7697): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7697): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7697): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7697): 	... 10 more
I/SELinux ( 7713): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7713):  
,I/SELinux ( 7717): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7717):  
,I/Process ( 7697): Sending signal. PID: 7697 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.android.documentsui (pid 7697) (adj 9) has died.
,I/SELinux ( 7713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7713):  
I/SELinux ( 7713):  
,I/SELinux ( 7713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7713): >>>>> Normal User
,E/dalvikvm( 7713): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7717): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7717):  
I/SELinux ( 7717):  
,I/SELinux ( 7717): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7717): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7717): >>>>> Normal User
E/dalvikvm( 7717): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,D/TimaKeyStoreProvider( 7713): in addTimaSignatureService
,E/SELinux ( 7717): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7713): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7713): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7717): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7717): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7717): Added TimaKesytore provider,
,D/dalvikvm( 7713): GC_CONCURRENT freed 3010K, 31% free 9558K/13668K, paused 2ms+2ms, total 18ms,
,D/dalvikvm( 7713): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,D/ExternalStorage( 7713): After updating volumes, found 1 active roots,
,D/dalvikvm( 7717): GC_CONCURRENT freed 2940K, 30% free 9622K/13664K, paused 1ms+1ms, total 18ms,
,D/dalvikvm( 7717): WAIT_FOR_CONCURRENT_GC blocked 16ms
,W/dalvikvm( 7717): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7717): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7717): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7717): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7717): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7717): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7717): install,
,I/MultiDex( 7717): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false),
,I/MultiDex( 7717): loading existing secondary dex files,
,I/MultiDex( 7717): load found 3 secondary dex files,
,I/MultiDex( 7717): install done,
,I/SELinux ( 7739): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7739):  
,I/SELinux ( 7739): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7739):  
I/SELinux ( 7739):  
I/SELinux ( 7739): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7739): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7739): >>>>> Normal User
,E/dalvikvm( 7739): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7739): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7739): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7739): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7739): Added TimaKesytore provider,
,I/SELinux ( 7753): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7753):  
,I/SELinux ( 7753): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7753):  
I/SELinux ( 7753):  
,I/SELinux ( 7753): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7753): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7753): >>>>> Normal User
,E/dalvikvm( 7753): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7753): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7753): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7753): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7753): Added TimaKesytore provider
,D/dalvikvm( 7739): GC_CONCURRENT freed 2987K, 30% free 9582K/13668K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7739): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/Icing.InternalIcingCorporaProvider( 7739): Updating corpora: A: com.test.thalitest, C: MAYBE
,D/dalvikvm( 7753): GC_CONCURRENT freed 2990K, 30% free 9580K/13672K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7753): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/SELinux ( 7769): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7769):  
,D/LocationManagerService( 2397): getProviders()=[passive]
,I/SELinux ( 7769): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7769):  
I/SELinux ( 7769):  
,I/SELinux ( 7769): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7769): >>>>> Normal User
,E/dalvikvm( 7769): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7769): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7769): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7769): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7769): Added TimaKesytore provider
,I/GservicesProvider( 7753): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7753): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7753): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7753): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7753): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7753): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7753): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7753): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7753): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7753): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7753): Shutting down VM
,W/dalvikvm( 7753): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
D/AmoledAdjustTimer( 2397): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,E/AndroidRuntime( 7753): FATAL EXCEPTION: main
E/AndroidRuntime( 7753): Process: com.google.process.gapps, PID: 7753
E/AndroidRuntime( 7753): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7753): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7753): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7753): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7753): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7753): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7753): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7753): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7753): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7753): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7753): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7753): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7753): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7753): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7753): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7753): 	... 12 more
,I/Process ( 7753): Sending signal. PID: 7753 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7753) (adj 0) has died.
,W/ActivityManager( 2397): Service crashed 2 times, stopping: ServiceRecord{434a3fb0 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7787): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7787):  
,D/dalvikvm( 7769): GC_CONCURRENT freed 3001K, 31% free 9566K/13668K, paused 4ms+2ms, total 20ms
,D/dalvikvm( 7769): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 1920): GC_EXPLICIT freed 44K, 11% free 9501K/10648K, paused 2ms+3ms, total 28ms
,I/SELinux ( 7787): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7787):  
I/SELinux ( 7787):  
,I/SELinux ( 7787): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7787): >>>>> Normal User
,E/dalvikvm( 7787): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7787): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9501K/10648K, paused 3ms+3ms, total 24ms
,D/TimaKeyStoreProvider( 7787): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7787): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7787): Added TimaKesytore provider
,D/dalvikvm( 1920): GC_EXPLICIT freed <1K, 11% free 9502K/10648K, paused 2ms+3ms, total 23ms
I/ActivityManager( 2397): Waited long enough for: ServiceRecord{435ba208 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/dalvikvm( 7787): GC_CONCURRENT freed 2987K, 30% free 9581K/13668K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7787): WAIT_FOR_CONCURRENT_GC blocked 16ms
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
,W/dalvikvm( 7787): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7787): FATAL EXCEPTION: main
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
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7787:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
E/ActivityThread( 7739): Failed to find provider info for com.google.settings
E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7717): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/SELinux ( 7805): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7805):  
,I/SELinux ( 7805): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7805):  
I/SELinux ( 7805):  
,I/SELinux ( 7805): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7805): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7805): >>>>> Normal User
,E/dalvikvm( 7805): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7805): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7805): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7805): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7805): Added TimaKesytore provider
,D/dalvikvm( 7805): GC_CONCURRENT freed 2990K, 30% free 9578K/13668K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7805): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/GservicesProvider( 7805): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7805): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7805): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7805): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7805): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7805): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7805): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7805): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7805): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7805): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7805): Shutting down VM
,W/dalvikvm( 7805): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
,E/AndroidRuntime( 7805): FATAL EXCEPTION: main
E/AndroidRuntime( 7805): Process: com.google.process.gapps, PID: 7805
E/AndroidRuntime( 7805): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7805): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7805): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7805): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7805): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7805): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7805): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7805): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7805): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7805): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7805): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7805): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7805): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7805): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7805): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7805): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7805): 	... 12 more
,I/Process ( 7805): Sending signal. PID: 7805 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7805) (adj 0) has died.
,I/SELinux ( 7820): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7820):  
,I/SELinux ( 7820): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7820):  
I/SELinux ( 7820):  
,I/SELinux ( 7820): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7820): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7820): >>>>> Normal User
,E/dalvikvm( 7820): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7820): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7820): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7820): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7820): Added TimaKesytore provider
,D/dalvikvm( 7820): GC_CONCURRENT freed 2994K, 30% free 9578K/13672K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7820): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7820): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7820): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7820): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7820): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7820): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7820): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7820): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7820): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7820): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7820): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7820): Shutting down VM
,W/dalvikvm( 7820): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7820): FATAL EXCEPTION: main
E/AndroidRuntime( 7820): Process: com.google.process.gapps, PID: 7820
E/AndroidRuntime( 7820): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7820): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7820): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7820): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7820): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7820): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7820): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7820): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7820): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7820): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7820): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7820): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7820): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7820): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7820): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7820): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7820): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7820): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7820:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7769): Failed to find provider info for com.google.android.gsf.gservices
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7717): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
D/dalvikvm( 7717): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7717): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7717): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7717): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7717): VFY: unable to resolve instance field 36
D/dalvikvm( 7717): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7717): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7717): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7717): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7717): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7717): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7717): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4269fe78
D/dalvikvm( 7717): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4269fe78
D/dalvikvm( 7717): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4269fe78, skipping init
D/dalvikvm( 7717): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4269fe78
D/dalvikvm( 7717): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4269fe78
V/JNIHelp ( 7717): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/dalvikvm( 7717): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4269fe78
,D/dalvikvm( 7717): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4269fe78
D/dalvikvm( 7717): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4269fe78
,D/dalvikvm( 7717): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4269fe78
,I/ProviderInstaller( 7717): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7835): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7835):  
,I/SELinux ( 7835): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7835):  
I/SELinux ( 7835):  
,I/SELinux ( 7835): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7835): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7835): >>>>> Normal User
,E/dalvikvm( 7835): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7835): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7835): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7835): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7835): Added TimaKesytore provider
,D/dalvikvm( 7835): GC_CONCURRENT freed 2991K, 30% free 9578K/13672K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7835): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/GservicesProvider( 7835): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7835): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7835): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7835): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7835): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7835): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7835): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7835): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7835): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7835): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7835): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7835): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7835): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7835): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7835): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7835): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7835): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7835): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7835): Shutting down VM
,W/dalvikvm( 7835): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
,I/Process ( 7835): Sending signal. PID: 7835 SIG: 9
E/AndroidRuntime( 7835): FATAL EXCEPTION: main
E/AndroidRuntime( 7835): Process: com.google.process.gapps, PID: 7835
E/AndroidRuntime( 7835): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7835): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7835): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7835): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7835): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7835): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7835): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7835): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7835): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7835): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7835): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7835): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7835): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7835): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7835): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7835): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7835): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7835): 	... 12 more
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<i,nit>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7835) (adj 0) has died.
,I/SELinux ( 7850): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7850):  
,I/SELinux ( 7850): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7850):  
I/SELinux ( 7850):  
,I/SELinux ( 7850): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7850): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7850): >>>>> Normal User
,E/dalvikvm( 7850): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7850): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7850): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7850): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7850): Added TimaKesytore provider
,D/dalvikvm( 7850): GC_CONCURRENT freed 3002K, 30% free 9571K/13672K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7850): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7850): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7850): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7850): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7850): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7850): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7850): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7850): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7850): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7850): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7850): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7850): Shutting down VM
,W/dalvikvm( 7850): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7850): FATAL EXCEPTION: main
E/AndroidRuntime( 7850): Process: com.google.process.gapps, PID: 7850
E/AndroidRuntime( 7850): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7850): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7850): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7850): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7850): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7850): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7850): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7850): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7850): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7850): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7850): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7850): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7850): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7850): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7850): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7850): 	... 12 more
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7850:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/ActivityThread( 7717): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
W/NativeLibraryUtils( 7717): Failed to open lock file
W/NativeLibraryUtils( 7717): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7717): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7717): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7717): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7717): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7717): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7717): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7717): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7717): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7717): 	... 3 more
,I/dalvikvm( 7717): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7717): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7717): VFY: replacing opcode 0x6e at 0x000d
,I/SELinux ( 7869): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7869):  
,W/dalvikvm( 2957): threadid=13: thread exiting with uncaught exception (group=0x41c4bc08)
,E/AndroidRuntime( 2957): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2957): Process: android.process.acore, PID: 2957
E/AndroidRuntime( 2957): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2957): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2957): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2957): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2957): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2957): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2957): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2957): Sending signal. PID: 2957 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/SELinux ( 7869): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7869):  
I/SELinux ( 7869):  
,I/SELinux ( 7869): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7869): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7869): >>>>> Normal User
,E/dalvikvm( 7869): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7869): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/ActivityManager( 2397): Process android.process.acore (pid 2957) (adj -12) has died.
D/TimaKeyStoreProvider( 7869): in addTimaSignatureService
D/TimaKeyStoreProvider( 7869): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7869): Added TimaKesytore provider
,I/SELinux ( 7882): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7882):  
,I/SELinux ( 7882): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7882):  
I/SELinux ( 7882):  
,I/SELinux ( 7882): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7882): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7882): >>>>> Normal User
,E/dalvikvm( 7882): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7882): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7882): in addTimaSignatureService
D/dalvikvm( 7869): GC_CONCURRENT freed 2982K, 30% free 9578K/13664K, paused 3ms+2ms, total 20ms,
,D/dalvikvm( 7869): WAIT_FOR_CONCURRENT_GC blocked 14ms,
,D/TimaKeyStoreProvider( 7882): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7882): Added TimaKesytore provider,
,D/dalvikvm( 7882): GC_CONCURRENT freed 2986K, 30% free 9575K/13664K, paused 1ms+1ms, total 17ms,
,D/dalvikvm( 7882): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7869): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7869): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7869): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7869): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7869): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7869): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7869): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7869): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7869): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7869): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7869): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7869): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7869): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7869): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7869): Shutting down VM
,W/dalvikvm( 7869): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
,E/AndroidRuntime( 7869): FATAL EXCEPTION: main
E/AndroidRuntime( 7869): Process: com.google.process.gapps, PID: 7869
E/AndroidRuntime( 7869): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7869): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7869): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7869): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7869): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7869): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7869): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7869): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7869): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7869): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7869): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7869): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7869): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7869): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7869): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7869): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7869): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7869): 	... 12 more
,I/Process ( 7869): Sending signal. PID: 7869 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/ActivityManager( 2397): Process com.google.process.gapps (pid 7869) (adj 0) has died.
,I/SELinux ( 7898): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7898):  
,I/SELinux ( 7898): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7898):  
I/SELinux ( 7898):  
,I/SELinux ( 7898): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7898): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7898): >>>>> Normal User
,E/dalvikvm( 7898): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7898): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7898): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7898): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7898): Added TimaKesytore provider
,E/SQLiteDatabase( 7882): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7882): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7882): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7882): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7882): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7882): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7882): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7882): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7882): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7882): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7882): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7882): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7882): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7882): (14) unable to open database file
E/SQLiteDatabase( 7882): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7882): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7882): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7882): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7882): threadid=13: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7882): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7882): Process: android.process.acore, PID: 7882
E/AndroidRuntime( 7882): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7882): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7882): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7882): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7882): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7882): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7882): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7882): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7882): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager( 2397): Waited long enough for: ServiceRecord{42724848 u0 com.sec.spp.push/.PushClientService}
W/ActivityManager( 2397): Process android.process.acore has crashed too many times: killing!
,I/Process ( 7882): Sending signal. PID: 7882 SIG: 9
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop235.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
I/ActivityManager( 2397): Process android.process.acore (pid 7882) (adj -12) has died.
F/ActivityManager( 2397): Service ServiceRecord{434de4a8 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{43391aa0 7882:android.process.acore/u0a20} not same as in map: null
E/DropBoxManagerService( 2397): Can't write: system_server_wtf
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop173.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2397): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2397): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2397): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2397): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2397): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2397): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuard,Os.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 18 more
D/dalvikvm( 7898): GC_CONCURRENT freed 2990K, 30% free 9577K/13668K, paused 2ms+2ms, total 18ms
D/dalvikvm( 7898): WAIT_FOR_CONCURRENT_GC blocked 15ms
I/SELinux ( 7914): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7914):  
,I/SELinux ( 7914): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7914):  
I/SELinux ( 7914):  
,I/SELinux ( 7914): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7914): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7914): >>>>> Normal User
,E/dalvikvm( 7914): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7914): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,I/GservicesProvider( 7898): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7898): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7898): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7898): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7898): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7898): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7898): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7898): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7898): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7898): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7898): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7898): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7898): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7898): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7898): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7898): Shutting down VM
,W/dalvikvm( 7898): threadid=1: thread exiting with uncaught exception (group=0x41c4bc08)
E/AndroidRuntime( 7898): FATAL EXCEPTION: main
E/AndroidRuntime( 7898): Process: com.google.process.gapps, PID: 7898
E/AndroidRuntime( 7898): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7898): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7898): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7898): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7898): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7898): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7898): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7898): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7898): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7898): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7898): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7898): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7898): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7898): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7898): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7898): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7898): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7898): 	... 12 more
,D/TimaKeyStoreProvider( 7914): in addTimaSignatureService
W/ActivityManager( 2397): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2397): Killing 7898:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2397): Can't write: system_app_crash
E/DropBoxManagerService( 2397): java.io.FileNotFoundException: /data/system/dropbox/drop237.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2397): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2397): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2397): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2397): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2397): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2397): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2397): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2397): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2397): 	... 5 more
,I/GAv4-SVC( 7717): Google Analytics 8.4.89 is starting up.
,D/TimaKeyStoreProvider( 7914): Cannot add TimaSignature Service, License check Failed
W/ActivityManager( 2397): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 7717): Failed to find provider info for com.google.android.gsf.gservices
D/ActivityThread( 7914): Added TimaKesytore provider
,I/SELinux ( 7929): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7929):  
,I/SELinux ( 7929): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7929):  
I/SELinux ( 7929):  
,I/SELinux ( 7929): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7929): >>>>> Normal User
,E/dalvikvm( 7929): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7929): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7914): GC_CONCURRENT freed 2987K, 30% free 9582K/13668K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7914): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/TimaKeyStoreProvider( 7929): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7929): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7929): Added TimaKesytore provider
,D/dalvikvm( 7929): GC_CONCURRENT freed 2991K, 30% free 9577K/13668K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7929): WAIT_FOR_CONCURRENT_GC blocked 10ms
,E/SQLiteDatabase( 7914): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7914): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7914): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7914): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7914): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7914): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7914): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7914): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7914): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7914): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7914): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 7914): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7914): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7914): (14) unable to open database file
,E/SQLiteDatabase( 7914): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7914): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7914): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7914): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7914): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7914): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7914): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7914): threadid=13: thread exiting with uncaught exception (group=0x41c4bc08)

```
