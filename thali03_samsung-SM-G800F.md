#### Test 55902202f27eba5_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7112): 
D/AndroidRuntime( 7112): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7112): CheckJNI is OFF
D/AndroidRuntime( 7112): setted country_code = Poland
D/AndroidRuntime( 7112): setted countryiso_code = PL
D/AndroidRuntime( 7112): setted sales_code = PLS
D/AndroidRuntime( 7112): readGMSProperty: start
D/AndroidRuntime( 7112): readGMSProperty: already setted!!
D/AndroidRuntime( 7112): readGMSProperty: end
D/AndroidRuntime( 7112): addProductProperty: start
D/dalvikvm( 7112): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7112): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7112): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7112): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7112): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7112): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7112): failed to load memtrack module: -2
D/dalvikvm( 7112): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7112): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SELinux ( 7140): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7140):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7112): Shutting down VM
D/dalvikvm( 7112): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 3ms
I/SELinux ( 7140): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7140):  
I/SELinux ( 7140):  
I/SELinux ( 7140): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7140): >>>>> Normal User
E/dalvikvm( 7140): >>>>> com.test.thalitest [ userId:0 | appId:10620 ]
E/SELinux ( 7140): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7140): in addTimaSignatureService
D/TimaKeyStoreProvider( 7140): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7140): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4171): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4171): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1921): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7140): GC_CONCURRENT freed 3010K, 32% free 9561K/13968K, paused 1ms+2ms, total 18ms
D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7140): Binding Chromium to the background looper Looper (main, tid 1) {422af2f0}
I/chromium( 7140): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7140): Initializing chromium process, renderers=0
W/chromium( 7140): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7140): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7140): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7140): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7140): Mali API Version : 401
,I/Mali    ( 7140): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7140): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7140): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
,D/dalvikvm( 7140): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7140): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7140): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7140): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2584): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:7140,o:f
,W/dalvikvm( 7140): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7140): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7140): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7140): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7140): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7140): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7140): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7140): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7140): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7140): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7140): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7140): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7140): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2584): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): semi p:7140,o:f
,I/SurfaceFlinger( 1921): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7140): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7140): Enabling debug mode 0
,W/AwContents( 7140): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 7140): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7140): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7140): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422b0078
,D/dalvikvm( 7140): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x422b0078
D/jxcore_app_log( 7140): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027606944
,D/JX-Cordova( 7140): jxcore cordova android initializing
,D/dalvikvm( 7140): GC_CONCURRENT freed 1283K, 20% free 11350K/14024K, paused 2ms+3ms, total 22ms
,D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7140): GC_CONCURRENT freed 1939K, 19% free 14954K/18304K, paused 3ms+2ms, total 41ms
,D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4381, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/dalvikvm( 7140): GC_FOR_ALLOC freed 5291K, 30% free 16231K/23168K, paused 53ms, total 53ms
,D/dalvikvm( 7140): GC_CONCURRENT freed 6711K, 32% free 17691K/25816K, paused 1ms+10ms, total 56ms
,D/dalvikvm( 7140): WAIT_FOR_CONCURRENT_GC blocked 43ms
,D/dalvikvm( 7140): GC_FOR_ALLOC freed 1188K, 33% free 17549K/25816K, paused 49ms, total 49ms
,I/dalvikvm-heap( 7140): Grow heap (frag case) to 22.012MB for 3688532-byte allocation
,D/dalvikvm( 7140): GC_FOR_ALLOC freed 2458K, 37% free 18693K/29420K, paused 43ms, total 43ms
,W/jxcore-log( 7140): Initializing JXcore engine
,W/jxcore-log( 7140): JXcore engine is ready
,W/jxcore-log( 7140): Starting JXcore engine
,W/jxcore-log( 7140): Platform android
W/jxcore-log( 7140): 
,W/jxcore-log( 7140): Process ARCH arm
W/jxcore-log( 7140): 
,I/jxcore-log( 7140): JXcore Cordova bridge is ready!
I/jxcore-log( 7140): 
,W/jxcore-log( 7140): JXcore engine is started
,I/chromium( 7140): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7140): Toggling radios to true
I/jxcore-log( 7140): 
,D/BluetoothAdapter( 7140): enable(): BT is already enabled..!
,I/WifiManager( 7140): packageName : com.test.thalitest
,I/WifiManager( 7140): setWifiEnabled : true
,I/WifiService( 2422): setWifiEnabled: true pid=7140, uid=10620
W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=7140, uid=10620 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7140, uid=10620 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2422): disconnect: pid=7140, uid=10620
,I/jxcore-log( 7140): Radios toggled
I/jxcore-log( 7140): 
,I/wpa_supplicant( 3970): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7140): My device name is: samsung-SM-G800F
I/jxcore-log( 7140): 
,I/wpa_supplicant( 3970): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3970): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3970): First Scan Start
,W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3970): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
I/wpa_supplicant( 3970): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3970): Skip scan - already scanning
D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2422): Attempting to switch to mobile
,D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2584): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7189): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7189):  
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-72ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-72ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2422): Error! unhandled message{ when=-12ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
I/SELinux ( 7189): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7189):  
I/SELinux ( 7189):  
,I/SELinux ( 7189): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7189): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7189): >>>>> Normal User
,E/dalvikvm( 7189): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7189): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
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
,D/TimaKeyStoreProvider( 7189): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7189): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/ActivityThread( 7189): Added TimaKesytore provider
,D/NetUtils( 2422): android_net_utils_resetConnections in env=0x78265b38 clazz=0x61c00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
,V/NativeCrypto( 2852): Read error: ssl=0x7bac2820: I/O error during system call, Connection timed out
,V/NativeCrypto( 2852): SSL shutdown failed: ssl=0x7bac2820: I/O error during system call, Broken pipe
,D/dalvikvm( 7189): GC_CONCURRENT freed 2989K, 32% free 9575K/13960K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7189): WAIT_FOR_CONCURRENT_GC blocked 18ms
,E/SPPClientService( 5554): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,I/System.out( 7189): Inside WakeupProvider
,I/System.out( 7189): Inside onCreate() of WakeupTriggerProvide
,E/SPPClientService( 5554): [e] exceptionCaught(). NET_TIMEOUT
,E/SPPClientService( 5554): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5554): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5554): [b] ResponseMap empty
,D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): updateIfacesLocked()
V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/VlingoApplication( 7189): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/VlingoApplication( 7189): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7189): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 20ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,D/DialogFlow( 7189): initQueue()
,V/NearbySettings( 2826): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2826): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2826): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2422): Killing 6181:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2826): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2826): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2826): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2422): updateDataUsageMap
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2584): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2584): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2584): updateDataNetType()
D/STATUSBAR-NetworkController( 2584): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6592): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6592): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6592): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6592): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6592): noConnectivity : true
,I/DBG_DM  ( 4750): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7218): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7218):  
,I/SELinux ( 7218): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7218):  
I/SELinux ( 7218):  
,I/SELinux ( 7218): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7218): >>>>> Normal User
,E/dalvikvm( 7218): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7218): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7218): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7218): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7218): Added TimaKesytore provider
,I/wpa_supplicant( 3970): nl80211: Received scan results (6 BSSes)
,I/wpa_supplicant( 3970): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3970): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7218): GC_CONCURRENT freed 2993K, 32% free 9570K/13960K, paused 3ms+2ms, total 32ms
,D/dalvikvm( 7218): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3970): Associated with C0.AA.48
I/wpa_supplicant( 3970): freq(2412) increment count 2
,I/wpa_supplicant( 3970): meet head of list.
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3970): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3970): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3970): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/WifiNative( 2422): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2422): Killing 6270:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,I/SELinux ( 7232): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7232):  
,I/SELinux ( 7232): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7232):  
I/SELinux ( 7232):  
,I/SELinux ( 7232): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7232): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7232): >>>>> Normal User
,E/dalvikvm( 7232): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7232): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7232): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7232): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7232): Added TimaKesytore provider
,D/dalvikvm( 7232): GC_CONCURRENT freed 2997K, 32% free 9567K/13960K, paused 3ms+2ms, total 23ms
,D/dalvikvm( 7232): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 10
D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,I/dhcpcd  ( 7244): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7244): bssid match
,I/ActivityManager( 2422): Killing 6328:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7251): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7251):  
,I/SELinux ( 7251): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7251):  
I/SELinux ( 7251):  
,I/SELinux ( 7251): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7251): >>>>> Normal User
,E/dalvikvm( 7251): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7251): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7251): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7251): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7251): Added TimaKesytore provider
,D/dalvikvm( 7251): GC_CONCURRENT freed 3000K, 32% free 9567K/13960K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7251): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/KLMS-2.3.201 : ( 7251): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7251): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452699560230
,I/KLMS-2.3.201 : ( 7251): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,I/ActivityManager( 2422): Killing 6348:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7263): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7263):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 14% free 9504K/10944K, paused 3ms+3ms, total 37ms
I/SELinux ( 7263): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7263):  
I/SELinux ( 7263):  
,I/SELinux ( 7263): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7263): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7263): >>>>> Normal User
,E/dalvikvm( 7263): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7263): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7263): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9505K/10944K, paused 3ms+4ms, total 33ms
,D/TimaKeyStoreProvider( 7263): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7263): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9505K/10944K, paused 3ms+4ms, total 32ms
,D/dalvikvm( 7263): GC_CONCURRENT freed 2997K, 32% free 9574K/13964K, paused 3ms+1ms, total 22ms
,D/dalvikvm( 7263): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/SO_AGENT( 7263): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7263): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5816): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5816): [BDLM] already registered in spp
I/SA      ( 5816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5816): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5816): [OR] == isSIMCardReady false ==
I/SA      ( 5816): [SCU] == networkStateCheck == false
,I/SA      ( 5816): [OR] onReceive END
I/ActivityManager( 2422): Killing 6395:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled
,I/SELinux ( 7275): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7275):  
,I/SELinux ( 7275): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7275):  
I/SELinux ( 7275):  
,I/SELinux ( 7275): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7275): >>>>> Normal User
,E/dalvikvm( 7275): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7275): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7275): in addTimaSignatureService
D/TimaKeyStoreProvider( 7275): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7275): Added TimaKesytore provider
,D/dalvikvm( 7275): GC_CONCURRENT freed 2990K, 32% free 9572K/13960K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7275): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/sCloudBackupApp( 7275): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7275): Other Intent
I/ActivityManager( 2422): Killing 5599:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7288): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7288):  
,I/SELinux ( 7288): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7288):  
I/SELinux ( 7288):  
,I/SELinux ( 7288): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7288): >>>>> Normal User
,E/dalvikvm( 7288): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7288): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7288): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7288): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7288): Added TimaKesytore provider
,D/dalvikvm( 7288): GC_CONCURRENT freed 2994K, 32% free 9573K/13960K, paused 4ms+1ms, total 24ms
,D/dalvikvm( 7288): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
D/com.samsung.app( 7288): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
D/com.samsung.app( 7288): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
D/com.samsung.app( 7288): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7288): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5351): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7288): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5351): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7288): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5351): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2422): Killing 6304:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5864): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5864): getCountryCode(): countryCode = PL
,D/Headlines( 5864): Breath.onCreate
,D/Headlines( 5864): Breath timer started. interval : 30000
,I/SELinux ( 7301): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7301):  
,D/Headlines( 5864): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5864): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5864): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5864): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2422): waitForAlarm result :8
,I/SELinux ( 7301): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7301):  
I/SELinux ( 7301):  
,I/SELinux ( 7301): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7301): >>>>> Normal User
,E/dalvikvm( 7301): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7301): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7301): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7301): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7301): Added TimaKesytore provider
,D/dalvikvm( 7301): GC_CONCURRENT freed 2991K, 32% free 9581K/13968K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7301): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,V/WebViewChromium( 7301): Binding Chromium to the background looper Looper (main, tid 1) {422ac3d8}
,I/chromium( 7301): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7301): Initializing chromium process, renderers=0
,W/chromium( 7301): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7301): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7301): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7301): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7301): Mali API Version : 401
,I/Mali    ( 7301): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7301): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7301): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2422): VerifyingLinkState enter,
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
,D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check,
,D/WifiStateMachine( 2422): CaptivePortalCheckState enter,
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling,
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE,
D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2584): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
D/STATUSBAR-NetworkController( 2584): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2584): refreshSignalCluster: data=-1 bt=false,
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info ,
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3,
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1,
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1915): RTNETLINK answers: No such file or directory,
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
,V/RouteController( 1915): RTNETLINK answers: No such process,
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1,
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2422): updateIfacesLocked(),
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,V/NetworkStats( 2422): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
V/NetworkStats( 2422): performPollLocked() took 21ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit,
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/NSApplication( 7301): Starting up...
,I/iu.Environment( 5947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5152): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5152): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5152): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422ba2b0
,I/SELinux ( 7375): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7375):  
,I/SELinux ( 7375): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7375):  
I/SELinux ( 7375):  
,I/SELinux ( 7375): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7375): >>>>> Normal User
,E/dalvikvm( 7375): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7375): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7375): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7375): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7375): Added TimaKesytore provider
,D/dalvikvm( 7375): GC_CONCURRENT freed 2984K, 32% free 9587K/13964K, paused 1ms+2ms, total 18ms
,D/dalvikvm( 7375): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/SELinux ( 7393): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7393):  
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7393): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7393):  
I/SELinux ( 7393):  
,I/SELinux ( 7393): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7393): >>>>> Normal User
,E/dalvikvm( 7393): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,E/SELinux ( 7393): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2422): Killing 5997:com.android.calendar/u0a144 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7393): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7393): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7393): Added TimaKesytore provider
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2584): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2584): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2584): updateDataNetType()
D/STATUSBAR-NetworkController( 2584): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,I/SELinux ( 7406): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7406):  
,I/ActivityManager( 2422): Killing 6232:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7406): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7406):  
I/SELinux ( 7406):  
,I/SELinux ( 7406): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7406): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7406): >>>>> Normal User
,E/dalvikvm( 7406): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7406): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,D/TimaKeyStoreProvider( 7406): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7406): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7406): Added TimaKesytore provider
,D/dalvikvm( 7393): GC_CONCURRENT freed 2999K, 32% free 9574K/13968K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7393): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/BadgeProvider( 7393): onCreate
,D/BadgeProvider( 7393): DatabaseHelper
,D/BadgeProvider( 7393): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/Launcher.Model( 2777): reloadBadges entered.
,D/BadgeProvider( 7393): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7393): sendNotify, [notify] : null
,D/BadgeProvider( 7393): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7393): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7393): update, [UpdateCount] : 1
,D/dalvikvm( 7406): GC_CONCURRENT freed 3003K, 32% free 9568K/13968K, paused 4ms+1ms, total 27ms
,D/dalvikvm( 7406): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/hcjo    ( 5969): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5969): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5969): exit::IDLE
,D/InitializeManagerStateMachine( 5969): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5969): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5969): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5969): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5969): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5969): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5969): entry::SUCCESS
,D/hcjo    ( 5969): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5969): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5969): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5969): exit::SUCCESS
,D/InitializeManagerStateMachine( 5969): entry::IDLE
,E/SPPClientService( 5554): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5554): [SystemStateMoniter] Current Time : 274025
,E/SPPClientService( 5554): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5554): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2826): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2826): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2826): MountReceiver.onReceive - Keep current state
,D/Headlines( 5864): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5864): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5864): Breath 1523 latestRequest time : 1452699561110 current time : 1452699562633
I/ActivityManager( 2422): Killing 6167:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,E/SPPClientService( 5554): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5554): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2826): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5554): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2826): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2826): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2826): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5554): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/SurfaceFlinger( 1921): id=20 createSurf (1x1),1 flag=4, Uoast
,D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,D/NearbySettings( 2826): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2826): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5554): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/PCWCLIENTTRACE_PushUtil( 6592): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6592): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6592): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6592): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5554): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5554): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7251): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7251): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452699563012
,I/KLMS-2.3.201 : ( 7251): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7263): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3440): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7263): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
D/GalaxyFinderApplication( 3440): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3440): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3440): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7430): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7430):  
,I/GallerySearchProvider( 3569): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7430): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7430):  
I/SELinux ( 7430):  
,I/SELinux ( 7430): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7430): >>>>> Normal User
,E/dalvikvm( 7430): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7430): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7430): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7430): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7430): Added TimaKesytore provider
,D/dalvikvm( 7430): GC_CONCURRENT freed 2996K, 32% free 9579K/13968K, paused 5ms+1ms, total 23ms
,D/dalvikvm( 7430): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 2422): GC_EXPLICIT freed 4176K, 74% free 25476K/95224K, paused 17ms+22ms, total 234ms
,I/System.out( 7232): Thread-633(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables,
,I/SELinux ( 7444): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7444):  
,I/System.out( 7232): Thread-633(ApacheHTTPLog):isShipBuild true,
,I/System.out( 7232): Thread-633(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
I/SA      ( 5816): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5816): [BDLM] already registered in spp,
I/SA      ( 5816): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5816): [OR] == ACTION_CONNECTIVITY_CHANGE ==,
I/SA      ( 5816): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5816): [OR] == isSIMCardReady false ==,
D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
I/SA      ( 5816): [SCU] == networkStateCheck == true,
I/SA      ( 5816): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5816): isChinaCountryCode : false
,I/SA      ( 5816): [OR] == networkStateCheck true ==,
I/SA      ( 5816): [OR] GetMyCountryZoneTask
,I/SA      ( 5816): [OR] onReceive END,
,I/SA      ( 5816): [SRS] prepareGetMyCountryZone,
I/SA      ( 5816): [TPMU]  strSIMState ,	:SIM_STATE_UNKNOWN
,I/SA      ( 5816): [SSP] query invoked
I/SELinux ( 7444): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7444):  ,
I/SELinux ( 7444):  
I/SELinux ( 7444): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7444): >>>>> Normal User
,E/dalvikvm( 7444): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 7444): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
D/PhoneNumberLocatorBootCompletedReceiver( 2756): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2756): Phone number locator feature is dsiabled,
,I/SCloudBackupReceiver( 7275): Other Intent,
,I/SA      ( 5816): [TPMU] GetMccFromDB : null,
I/SA      ( 5816): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5816): [TPM] isNoProxy(default) : true
,I/SA      ( 5816): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/TimaKeyStoreProvider( 7444): in addTimaSignatureService
,D/com.samsung.app( 7288): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 7444): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7444): Added TimaKesytore provider
D/Headlines( 5864): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5864): getCountryCode(): countryCode = PL
D/Headlines( 5864): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5864): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5864): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5864): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5864): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5947): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5152): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5152): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5152): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422ba2b0
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/dalvikvm( 7444): GC_CONCURRENT freed 2992K, 32% free 9576K/13960K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7444): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/hcjo    ( 5969): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5969): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5969): exit::IDLE
,D/InitializeManagerStateMachine( 5969): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5969): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5969): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5969): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5969): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5969): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5969): entry::SUCCESS
,D/hcjo    ( 5969): AutoUpdateManager:INITCHECK:onInitializeSuccess
,V/KVNProvider( 7444): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
D/hcjo    ( 5969): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 5969): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,V/KVNProvider( 7444): getFindoCursor query string : 
D/InitializeManagerStateMachine( 5969): exit::SUCCESS
,D/InitializeManagerStateMachine( 5969): entry::IDLE
,I/System.out( 7232): AsyncTask #1 calls detatch()
,V/KVNProvider( 7444): getTagSearchCursor() tagSearchCursor count : 0
,E/SPPClientService( 5554): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5554): [SystemStateMoniter] Current Time : 275123
,E/SPPClientService( 5554): [SystemStateMoniter] No Connect : false
,W/System.err( 7232): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7232): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7232): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7232): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7232): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7232): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7232): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7232): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7232): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7232): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7232): Caused by: java.lang.NullPointerException
,W/System.err( 7232): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7232): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7232): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7232): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7232): 	... 8 more
,I/ActivityManager( 2422): Killing 6344:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 5554): GC_CONCURRENT freed 1968K, 26% free 10440K/13940K, paused 8ms+3ms, total 59ms
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 5816): [RC New] [v2liruge] api execute + 717
,I/SA      ( 5816): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5816): AsyncTask #2 calls detatch()
,I/SA      ( 5816): [TPMU] getNetworkMcc : 
,I/SA      ( 5816): [SCU] saveMccToPreferece Start
I/SA      ( 5816): [SCU] RegionMCC : 260
,I/SA      ( 5816): [SSP] query invoked
I/SA      ( 5816): [TPMU] GetMccFromDB : null
,I/SA      ( 5816): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 5816): [SCU] saveMccToPreferece End
I/SA      ( 5816): [RC New] executeRequest [v2liruge] end. 740
,I/SA      ( 5816): [RC New] Execute end
I/SA      ( 5816): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5816): [OR] GetMyCountryZoneTask Success
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/SPPClientService( 5554): [b] __InitReply__
,E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4382, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
,V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4007): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1921): id=20 Removed Uoast (-2/11)
I/ActivityManager( 2422): Killing 6203:com.google.android.music:main/u0a125 (adj 15): empty #43
D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 277712
D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0)
D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3472)
,I/GAV2    ( 7301): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6592): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6592): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6592): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6592): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6592): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6592): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6592): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6592): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6592): [ensureRegistration] - No Samsung account
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 290, prevStep = 4, currStep = 4
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7140): Test app app.js loaded
I/jxcore-log( 7140): 
,I/Choreographer( 7140): Skipped 865 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7140): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/PreloadUpdateManagerStateMachine( 5969): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5969): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5969): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5969): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5969): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5969): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5969): entry::IDLE
,I/jxcore-log( 7140): --= Surplus to requirements =--
I/jxcore-log( 7140): 
I/jxcore-log( 7140): ****TEST TOOK:  ms ****
I/jxcore-log( 7140): 
,I/jxcore-log( 7140): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7140): 
,D/AndroidRuntime( 7478): 
D/AndroidRuntime( 7478): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7478): CheckJNI is OFF
D/AndroidRuntime( 7478): setted country_code = Poland
,D/AndroidRuntime( 7478): setted countryiso_code = PL
D/AndroidRuntime( 7478): setted sales_code = PLS
D/AndroidRuntime( 7478): readGMSProperty: start
D/AndroidRuntime( 7478): readGMSProperty: already setted!!
D/AndroidRuntime( 7478): readGMSProperty: end
,D/AndroidRuntime( 7478): addProductProperty: start
,D/dalvikvm( 7478): Trying to load lib libjavacore.so 0x0
D/PreloadUpdateManagerStateMachine( 5969): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5969): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5969): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5969): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5969): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/dalvikvm( 7478): Added shared lib libjavacore.so 0x0
D/PreloadUpdateManagerStateMachine( 5969): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5969): entry::IDLE
,D/dalvikvm( 7478): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7478): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7478): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7478): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7478): failed to load memtrack module: -2
,D/dalvikvm( 7478): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7478): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2422): START PACKAGE DELETE: observer{1112684760}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
,D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2422): !@killApplicatoin: 10620, uninstall pkg
,I/ActivityManager( 2422): Killing 7140:com.test.thalitest/u0a620 (adj 0): stop com.test.thalitest
,D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2422): mDVFSHelper.acquire()
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (8/10)
,I/SurfaceFlinger( 1921): id=19 Removed NainActivit (-2/10)
,I/WindowState( 2422): WIN DEATH: Window{42fb10e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,W/PackageSettings( 2422): Skipping PackageSetting{42a00c70 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2422): setPackageStoppedState - Execution time: 114 ms
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10620, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10620, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/DBG_DM  ( 4750): [3.19.140541][Line:408][onResume] 
,I/DBG_DM  ( 4750): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,E/SamsungIME( 3006): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5152): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2981): GC_EXPLICIT freed 1213K, 21% free 10036K/12644K, paused 7ms+9ms, total 86ms
,I/DBG_DM  ( 4750): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:418][onResume] Postpone Count : 29
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 7489): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7489):  
I/FPMS_FingerprintManagerService( 2604): onReceive: android.intent.action.PACKAGE_REMOVED
,D/dalvikvm( 6752): GC_EXPLICIT freed 151K, 30% free 9961K/14180K, paused 19ms+11ms, total 131ms
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 7489): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7489):  
I/SELinux ( 7489):  
,I/SELinux ( 7489): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7489): >>>>> Normal User
E/dalvikvm( 7489): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RegisteredServicesCache( 2761): empty dynamic service
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
,I/DBG_DM  ( 4750): [3.19.140541][Line:5196][xdbGetDownloadPostponeStatus] Download Postpone status : 0
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7489): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7489): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7489): Added TimaKesytore provider
,D/dalvikvm( 6436): GC_EXPLICIT freed 2511K, 30% free 9888K/13968K, paused 5ms+5ms, total 233ms
,I/DBG_DM  ( 4750): [3.19.140541][Line:330][xuiSetNotification] NotificationID : 4 / Notification IndicatorState : 7
,D/dalvikvm( 2422): GC_EXPLICIT freed 2308K, 74% free 25097K/95224K, paused 12ms+23ms, total 266ms
,D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 242ms
,W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
,I/DBG_DM  ( 4750): [3.19.140541][Line:5092][xdbGetPriority] Get Priority : 0
,D/dalvikvm( 3284): GC_EXPLICIT freed 1739K, 22% free 12420K/15776K, paused 16ms+15ms, total 317ms
,I/DBG_DM  ( 4750): [3.19.140541][Line:5133][xdbGetPostponeCount] Get Postpone Count : 29
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/DBG_DM  ( 4750): [3.19.140541][Line:5012][xdbGetPostponeForce] Get Force status : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:5155][xdbGetPostponeMaxCount] Get Postpone Max Count : 0
,I/DBG_DM  ( 4750): [3.19.140541][Line:504][xuiCheckForceInstall] Check Force Install : false
,D/checkbox( 4750): setChecked(1) checked=false, mCheckBoxAnimationEnabled=false, mIsAttached=true
,I/DBG_DM  ( 4750): [3.19.140541][Line:757][xdmGetDeviceEncryptState] 
,I/DBG_DM  ( 4750): [3.19.140541][Line:804][xdmGetDeviceEncryptState] InternalEncrypted : [false], SDEncrypted : [false]
,D/Activity( 4750): setTransGradationMode to true
,D/StatusBarManagerService( 2422): semi p:4750,o:t
D/PhoneStatusBar( 2584): setSemiTransparentMode=true, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
I/DBG_DM  ( 4750): [3.19.140541][Line:400][onPause] 
,I/SurfaceFlinger( 1921): id=21 createSurf (720x1280),2 flag=404, YUIInstallC
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
,I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 7489): GC_CONCURRENT freed 3004K, 32% free 9571K/13968K, paused 12ms+6ms, total 36ms
D/dalvikvm( 7489): WAIT_FOR_CONCURRENT_GC blocked 16ms
,D/elm:14132( 7489): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/dalvikvm( 2761): GC_CONCURRENT freed 1210K, 29% free 10614K/14856K, paused 12ms+3ms, total 109ms
,D/dalvikvm( 2761): WAIT_FOR_CONCURRENT_GC blocked 86ms
,D/elm:14132( 7489): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7489): MDMBridge.setEnterpriseBridge()
D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/elm:14132( 7489): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7489): ElmAgentService : onCreate()
,D/elm:14132( 7489): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,D/elm:14132( 7489): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7489): MDMBridge.getInstance()
,D/elm:14132( 7489): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7489): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7505): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7505):  
,D/elm:14132( 7489): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/RCPManagerService( 2422): PackageReceiver onReceive()
,D/elm:14132( 7489): ElmAgentService : onDestroy().
,I/HarmonyEASService( 2422): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/SELinux ( 7505): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7505):  
I/SELinux ( 7505):  
,I/SELinux ( 7505): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2422): Killing 6535:com.android.defcontainer/u0a6 (adj 15): empty #43
E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7505): >>>>> Normal User
E/dalvikvm( 7505): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux ( 7505): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7505): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7505): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7505): Added TimaKesytore provider
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 7140 uid 10620
,D/EnterpriseDeviceManagerService( 2422): Package has changed for user 0
,D/dalvikvm( 7505): GC_CONCURRENT freed 3001K, 32% free 9570K/13968K, paused 4ms+2ms, total 23ms
,D/dalvikvm( 7505): WAIT_FOR_CONCURRENT_GC blocked 19ms
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2422): GC_EXPLICIT freed 1020K, 74% free 25161K/95224K, paused 14ms+31ms, total 498ms
D/PackageManager( 2422): delete sourFile : 
,I/SELinux ( 7523): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7523):  
,I/ActivityManager( 2422): Killing 6464:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 14% free 9504K/10944K, paused 2ms+3ms, total 33ms
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/BackupManagerService( 2422): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2422): removePackageParticipantsLocked: uid=10620 #1
,I/SELinux ( 7523): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7523):  
I/SELinux ( 7523):  
,I/SELinux ( 7523): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7523): >>>>> Normal User
,E/dalvikvm( 7523): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7523): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.StatusBarManagerService.sendNotification:987 com.android.server.StatusBarManagerService.updateNotification:696 com.android.server.NotificationManagerService$7.run:2149 android.os.Handler.handleCallback:733 
D/STATUSBAR-StatusBarManagerService( 2422): sendNotification(2) - 4
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10944K, paused 3ms+3ms, total 26ms,
,D/TimaKeyStoreProvider( 7523): in addTimaSignatureService,
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10944K, paused 2ms+3ms, total 29ms
,D/TimaKeyStoreProvider( 7523): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7523): Added TimaKesytore provider
,D/PackageManager( 2422): delete native library directory: 
,D/PackageManager( 2422): return delete result to caller: 1112684760
,D/PackageManager( 2422): returnCode: 1
D/AndroidRuntime( 7478): Shutting down VM
,D/dalvikvm( 7478): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 3ms
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7523): GC_CONCURRENT freed 2998K, 32% free 9576K/13968K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7523): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6592): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6592): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6592): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6592): [onReceive] - android.intent.action.PACKAGE_REMOVED
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SA      ( 5816): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5816): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ApplicationsProvider( 2981): Could not fetch usage stats
W/ApplicationsProvider( 2981): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2981): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2981): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2981): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2981): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2981): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2981): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2981): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2981): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2981): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2981): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2981): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Icing.InternalIcingCorporaProvider( 6436): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7541): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7541):  
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 7541): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7541):  
I/SELinux ( 7541):  
,I/SELinux ( 7541): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/dalvikvm( 7541): >>>>> Normal User
,E/dalvikvm( 7541): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ],
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SELinux ( 7541): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7541): in addTimaSignatureService,
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
D/TimaKeyStoreProvider( 7541): Cannot add TimaSignature Service, License check Failed
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ActivityThread( 7541): Added TimaKesytore provider,
,D/UsbSettingsManager( 2422): clearDefaults: com.test.thalitest,
I/CrashAnrDetector( 2422): onPackageRemoved : com.test.thalitest
,W/AtomicFile( 2422): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
,E/SQLiteLog( 6436): (10) unixWrite() gets errno : 9
E/SQLiteLog( 6436): (10) unixWrite() gets errno : 9
,W/AppWidgetServiceImpl( 2422): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
W/dalvikvm( 6436): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 6436): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6436): Process: com.google.android.googlequicksearchbox:search, PID: 6436
E/AndroidRuntime( 6436): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
E/AndroidRuntime( 6436): 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:524)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:248)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6436): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6436): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6436): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6436): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6436): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6436): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6436): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 6436): Sending signal. PID: 6436 SIG: 9
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4366, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/dalvikvm( 7541): GC_CONCURRENT freed 2990K, 32% free 9582K/13968K, paused 6ms+1ms, total 39ms
D/KeyguardUpdateMonitor( 2584): received broadcast android.intent.action.BATTERY_CHANGED
D/dalvikvm( 7541): WAIT_FOR_CONCURRENT_GC blocked 26ms
D/KeyguardUpdateMonitor( 2584): handleBatteryUpdate
V/HeadsetService( 4007): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4007): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2584):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,I/ActivityManager( 2422): Process com.google.android.googlequicksearchbox:search (pid 6436) (adj 5) has died.
,D/STATUSBAR-IconMerger( 2584): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2584): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/UserAnalysis.PlaceProvider( 7541): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7541): Create SecureDbHelper
,E/SQLiteDatabase( 7541): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7541): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7541): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7541): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7541): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7541): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7541): Opened privacy in read-only mode
D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
E/SQLiteDatabase( 7541): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7541): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7541): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7541): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7541): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7541): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7541): Opened privacy in read-only mode
E/SQLiteDatabase( 7541): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7541): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7541): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7541): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7541): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7541): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7541): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7541): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7541): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7541): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7541): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7541): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7541): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7541): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7541): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7541): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7541): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7541): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7541): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7541): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7541): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7541): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7541): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6371): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
,D/RCPManager( 6451):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2422):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2422): queryAllProviders():  providerCallBack is not register for 0
E/SQLiteDatabase( 6371): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6371): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6371): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6371): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6371): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6371): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6371): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
D/CapabilityManagerService New( 6662): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6662): The package(com.test.thalitest) removed
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6371): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6371): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6371): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6371): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6371): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 2422): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6371): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6371): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6371): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6371): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6371): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
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
W/System.err( 6371): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2422): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2422): 	... 8 more
W/System.err( 6371): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6371): 	at android.os.HandlerThread.run(HandlerThread.java:61)
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
,D/MagazineService::MagazineBroadcastReceiver( 6688): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6688): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 6688): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6688): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6688): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6688): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6688): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6688): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6688): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6688): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6688): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6688): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7556): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7556):  
,E/AndroidRuntime( 6688): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6688): Process: com.samsung.android.magazine.service, PID: 6688
E/AndroidRuntime( 6688): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6688): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6688): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6688): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6688): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6688): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6688): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6688): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6688): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6688): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6688): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6688): Sending signal. PID: 6688 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2422): Process com.samsung.android.magazine.service (pid 6688) (adj 5) has died.
,I/SELinux ( 7556): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7556):  
I/SELinux ( 7556):  
,I/SELinux ( 7556): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7556): >>>>> Normal User
,E/dalvikvm( 7556): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7556): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7556): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7556): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7556): Added TimaKesytore provider
,D/dalvikvm( 7556): GC_CONCURRENT freed 3000K, 32% free 9568K/13964K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7556): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/ContextImpl( 7556): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,E/SQLiteDatabase( 7556): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7556): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7556): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7556): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7556): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7556): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 7556): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsModeInstallReceiver( 6714): onReceive intent data =  package:com.test.thalitest
,E/AndroidRuntime( 7556): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7556): Process: com.android.keychain, PID: 7556
E/AndroidRuntime( 7556): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7556): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7556): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7556): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7556): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7556): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7556): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7556): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7556): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7556): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/KidsPlatformStub( 6714): Package not found : com.sec.android.app.kidshome
,E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
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
I/Process ( 7556): Sending signal. PID: 7556 SIG: 9
,W/System.err( 6752): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6752): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6752): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6752): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6752): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6752): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6752): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6752): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6752): 	at java.lang.reflect.Method.invokeNative(Native Method)
,W/System.err( 6752): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6752): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6752): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6752): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3284): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3284): Clearing selected account for com.test.thalitest
I/ActivityManager( 2422): Process com.android.keychain (pid 7556) (adj 5) has died.
,I/LocationSettingsChecker( 3284): Removing dialog suppression flag for package com.test.thalitest
,E/SQLiteLog( 3284): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3284): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3284): disk I/O error (code 3850)
E/DriveAsyncService( 3284): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3284): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3284): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3284): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3284): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3284): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3284): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3284): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3284): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3284): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3284): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3284): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3284): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3284): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3284): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 2852): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2852): Shutting down VM
,W/dalvikvm( 2852): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/SQLiteDatabase( 3284): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3284): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3284): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3284): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3284): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3284): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3284): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3284): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/PhenotypeInitializer( 3284): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3284): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3284): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3284): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3284): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 3284): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3284): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 3284): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,E/SQLiteOpenHelper( 3284): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3284): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3284): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3284): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3284): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3284): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3284): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3284): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3284): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3284): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3284): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3284): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3284): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/AndroidRuntime( 2852): FATAL EXCEPTION: main
E/AndroidRuntime( 2852): Process: com.google.process.gapps, PID: 2852
E/AndroidRuntime( 2852): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2852): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2852): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2852): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2852): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2852): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2852): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2852): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2852): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRunt,ime( 2852): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2852): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2852): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2852): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2852): 	... 10 more
,E/ClearPendingStateOp( 3284): Runtime exception while performing operation
E/ClearPendingStateOp( 3284): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3284): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3284): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3284): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3284): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3284): 	at java.lang.Thread.run(Thread.java:841)
,F/ClearPendingStateOp( 3284): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3284): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3284): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3284): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3284): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3284): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
F/ClearPendingStateOp( 3284): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3284): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3284): 	at java.lang.Thread.run(Thread.java:841)
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
E/SQLiteLog( 3284): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3284): threadid=50: thread exiting with uncaught exception (group=0x4180ac08)
W/SQLiteOpenHelper( 3284): Opened metrics.db in read-only mode
D/gH_CompatibleDatabase( 3284): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/gH_CompatibleDatabase( 3284): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
E/SQLiteLog( 3284): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3284): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3284): threadid=51: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3284): Sending signal. PID: 3284 SIG: 9
I/Process ( 2852): Sending signal. PID: 2852 SIG: 9
,E/SQLiteDatabase( 5554): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5554): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5554): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5554): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5554): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5554): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5554): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5554): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5554): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5554): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5554): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5554): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5554): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5554): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5554): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5554): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5554): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5554): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5554): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 6412): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6412): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6412): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6412): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6412): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6412): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6412): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6412): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6412): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6412): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6412): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6412): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7583): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7583):  
I/ActivityManager( 2422): Process com.google.process.gapps (pid 2852) (adj 5) has died.
I/ActivityManager( 2422): Process com.google.android.gms (pid 3284) (adj 0) has died.
,E/SQLiteDatabase( 6412): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6412): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6412): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6412): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6412): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6412): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6412): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6412): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6412): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6412): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6412): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6412): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6412): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6412): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6412): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,D/GAV2    ( 5643): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5643): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7583): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7583):  
I/SELinux ( 7583):  
,I/SELinux ( 7583): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7583): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7583): >>>>> Normal User
,E/dalvikvm( 7583): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7583): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7583): in addTimaSignatureService
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{46fc5ab8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
D/TimaKeyStoreProvider( 7583): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7583): Added TimaKesytore provider
,D/dalvikvm( 7583): GC_CONCURRENT freed 3008K, 32% free 9560K/13960K, paused 2ms+1ms, total 17ms
,D/dalvikvm( 7583): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Documents( 7583): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7583): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7583): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7583): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7583): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7583): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7583): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7583): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7583): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7583): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7583): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7583): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7583): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7583): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7583): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7583): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7583): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7583): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7583): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7583): Shutting down VM
,W/dalvikvm( 7583): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7599):  
,E/AndroidRuntime( 7583): FATAL EXCEPTION: main
E/AndroidRuntime( 7583): Process: com.android.documentsui, PID: 7583
E/AndroidRuntime( 7583): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7583): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7583): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7583): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7583): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7583): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7583): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7583): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7583): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7583): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7583): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7583): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7583): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7583): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7583): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7583): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7583): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7583): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7583): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7583): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7583): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7583): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7583): 	... 10 more
,I/SELinux ( 7603): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7603):  
I/ActivityManager( 2422): Killing 6565:com.samsung.groupcast/u0a15 (adj 15): empty #43
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
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
,I/Process ( 7583): Sending signal. PID: 7583 SIG: 9
,I/ActivityManager( 2422): Process com.android.documentsui (pid 7583) (adj 9) has died.
I/SELinux ( 7599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7599):  
I/SELinux ( 7599):  
I/SELinux ( 7599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7599): >>>>> Normal User
E/dalvikvm( 7599): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/SELinux ( 7603): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7603):  
I/SELinux ( 7603):  
,I/SELinux ( 7603): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7603): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7603): >>>>> Normal User
,E/dalvikvm( 7603): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7603): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7599): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7603): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7603): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7603): Added TimaKesytore provider
,D/dalvikvm( 7599): GC_CONCURRENT freed 3002K, 32% free 9568K/13968K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 7599): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/dalvikvm( 7603): GC_CONCURRENT freed 2943K, 32% free 9624K/13964K, paused 2ms+1ms, total 23ms
,D/dalvikvm( 7603): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/ExternalStorage( 7599): After updating volumes, found 1 active roots
,W/dalvikvm( 7603): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7603): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7603): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
,W/dalvikvm( 7603): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7603): VFY: replacing opcode 0x6e at 0x00cd
,I/MultiDex( 7603): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7603): install
,I/MultiDex( 7603): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7603): loading existing secondary dex files
,I/MultiDex( 7603): load found 3 secondary dex files
,I/MultiDex( 7603): install done
,I/SELinux ( 7626): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7626):  
,I/SELinux ( 7631): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7631):  
,I/SELinux ( 7626): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7626):  
I/SELinux ( 7626):  
,I/SELinux ( 7626): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7626): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7626): >>>>> Normal User
,E/dalvikvm( 7626): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7626): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7626): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7626): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7626): Added TimaKesytore provider
I/SELinux ( 7631): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7631):  
I/SELinux ( 7631):  
,I/SELinux ( 7631): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7631): >>>>> Normal User
,E/dalvikvm( 7631): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7631): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7631): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7631): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7631): Added TimaKesytore provider
,D/dalvikvm( 7626): GC_CONCURRENT freed 2992K, 32% free 9582K/13968K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7626): WAIT_FOR_CONCURRENT_GC blocked 16ms
D/dalvikvm( 7631): GC_CONCURRENT freed 2989K, 32% free 9583K/13964K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7631): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/Watchdog( 2422): !@Sync 9
,I/Icing.InternalIcingCorporaProvider( 7626): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/GservicesProvider( 7631): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7631): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7631): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7631): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7631): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7631): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7631): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7631): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7631): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7631): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7631): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7631): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7631): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7631): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7631): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7631): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7631): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7631): Shutting down VM
,W/dalvikvm( 7631): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/SELinux ( 7657): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7657):  
E/AndroidRuntime( 7631): FATAL EXCEPTION: main
E/AndroidRuntime( 7631): Process: com.google.process.gapps, PID: 7631
E/AndroidRuntime( 7631): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7631): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7631): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7631): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7631): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7631): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7631): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7631): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7631): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7631): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7631): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7631): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7631): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7631): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7631): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7631): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7631): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7631): 	... 12 more
,D/LocationManagerService( 2422): getProviders()=[passive]
,I/Process ( 7631): Sending signal. PID: 7631 SIG: 9
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
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7631) (adj 0) has died.
,W/ActivityManager( 2422): Service crashed 2 times, stopping: ServiceRecord{43209448 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7665): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7665):  
,I/SELinux ( 7657): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7657):  
I/SELinux ( 7657):  
,I/SELinux ( 7657): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7657): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7657): >>>>> Normal User
,E/dalvikvm( 7657): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7657): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7657): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7657): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7657): Added TimaKesytore provider
I/SELinux ( 7665): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7665):  
I/SELinux ( 7665):  
,I/SELinux ( 7665): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7665): >>>>> Normal User
,E/dalvikvm( 7665): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7665): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7665): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7665): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7665): Added TimaKesytore provider
,D/dalvikvm( 7657): GC_CONCURRENT freed 2993K, 32% free 9569K/13960K, paused 4ms+1ms, total 21ms
,D/dalvikvm( 7657): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 7665): GC_CONCURRENT freed 2997K, 32% free 9573K/13964K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7665): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/GservicesProvider( 7665): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7665): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7665): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7665): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7665): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7665): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7665): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7665): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7665): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7665): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7665): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7665): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7665): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7665): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7665): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7665): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7665): Shutting down VM
,W/dalvikvm( 7665): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7665): FATAL EXCEPTION: main
E/AndroidRuntime( 7665): Process: com.google.process.gapps, PID: 7665
E/AndroidRuntime( 7665): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7665): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7665): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7665): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7665): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7665): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7665): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7665): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7665): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7665): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7665): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7665): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7665): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7665): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7665): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7665): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7665:com.google.process.gapps/u0a12 (adj 0): crash
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /d,ata/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
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
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7657): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7626): Failed to find provider info for com.google.settings
,I/SELinux ( 7691): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7691):  
,I/SELinux ( 7691): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7691):  
I/SELinux ( 7691):  
,I/SELinux ( 7691): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7691): >>>>> Normal User
,E/dalvikvm( 7691): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7691): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7691): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7691): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7691): Added TimaKesytore provider
,D/dalvikvm( 7691): GC_CONCURRENT freed 3001K, 32% free 9574K/13968K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7691): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7691): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7691): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7691): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7691): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7691): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7691): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7691): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7691): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7691): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7691): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7691): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7691): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7691): Shutting down VM
,W/dalvikvm( 7691): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7691): FATAL EXCEPTION: main
E/AndroidRuntime( 7691): Process: com.google.process.gapps, PID: 7691
E/AndroidRuntime( 7691): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7691): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7691): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7691): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7691): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7691): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7691): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7691): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7691): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7691): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7691): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7691): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7691): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7691): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7691): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7691): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7691): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7691): 	... 12 more
,I/Process ( 7691): Sending signal. PID: 7691 SIG: 9
E/DropBoxManagerService( 2422): Can't write: system_app_crash
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
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7691) (adj 0) has died.
,I/SELinux ( 7706): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7706):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 44K, 14% free 9504K/10944K, paused 2ms+3ms, total 30ms
,I/SELinux ( 7706): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7706):  
I/SELinux ( 7706):  
,I/SELinux ( 7706): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7706): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7706): >>>>> Normal User
,E/dalvikvm( 7706): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7706): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7706): in addTimaSignatureService
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9504K/10944K, paused 2ms+2ms, total 25ms
,D/TimaKeyStoreProvider( 7706): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7706): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 14% free 9505K/10944K, paused 2ms+3ms, total 23ms
,D/dalvikvm( 7706): GC_CONCURRENT freed 2987K, 32% free 9584K/13964K, paused 3ms+1ms, total 18ms
,D/dalvikvm( 7706): WAIT_FOR_CONCURRENT_GC blocked 15ms
,I/GservicesProvider( 7706): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7706): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7706): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7706): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7706): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7706): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7706): Shutting down VM
,W/dalvikvm( 7706): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7706): FATAL EXCEPTION: main
E/AndroidRuntime( 7706): Process: com.google.process.gapps, PID: 7706
E/AndroidRuntime( 7706): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7706): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7706): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7706): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7706): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7706): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7706): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7706): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7706): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7706): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7706): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7706): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7706): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7706): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7706): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7706): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7706:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7657): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices
,E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
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
D/dalvikvm( 7603): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7603): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7603): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7603): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7603): VFY: unable to resolve instance field 36
D/dalvikvm( 7603): VFY: replacing opcode 0x54 at 0x005f
,D/dalvikvm( 7603): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
,I/ActivityManager( 2422): Killing 5706:com.android.mms/u0a49 (adj 15): empty #43
W/dalvikvm( 7603): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7603): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7603): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7603): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
D/dalvikvm( 7603): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d440
D/dalvikvm( 7603): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d440
D/dalvikvm( 7603): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d440, skipping init
D/dalvikvm( 7603): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d440
D/dalvikvm( 7603): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d440
V/JNIHelp ( 7603): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/CountryDetector( 2422): No listener is left
,D/dalvikvm( 7603): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x4230d440
,D/dalvikvm( 7603): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x4230d440
D/dalvikvm( 7603): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x4230d440
,D/dalvikvm( 7603): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4230d440
,I/ProviderInstaller( 7603): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7721): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7721):  
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
,D/dalvikvm( 7721): GC_CONCURRENT freed 2990K, 32% free 9581K/13968K, paused 4ms+2ms, total 20ms
,D/dalvikvm( 7721): WAIT_FOR_CONCURRENT_GC blocked 12ms
,I/GservicesProvider( 7721): Gservices pushing to system: true; secure/global: true
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{43eec558 u0 com.sec.spp.push/.PushClientService}
E/SQLiteDatabase( 7721): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
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
,W/dalvikvm( 7721): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7721): FATAL EXCEPTION: main
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
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7721) (adj 0) has died.
,I/SELinux ( 7736): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7736):  
,I/SELinux ( 7736): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7736):  
I/SELinux ( 7736):  
,I/SELinux ( 7736): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7736): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7736): >>>>> Normal User
,E/dalvikvm( 7736): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7736): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7736): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7736): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7736): Added TimaKesytore provider
,D/dalvikvm( 7736): GC_FOR_ALLOC freed 3011K, 32% free 9563K/13968K, paused 16ms, total 16ms
,D/dalvikvm( 7736): GC_CONCURRENT freed 213K, 17% free 9582K/11440K, paused 1ms+2ms, total 14ms
,I/GservicesProvider( 7736): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7736): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7736): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7736): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7736): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7736): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7736): Shutting down VM
,W/dalvikvm( 7736): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 7736): FATAL EXCEPTION: main
E/AndroidRuntime( 7736): Process: com.google.process.gapps, PID: 7736
E/AndroidRuntime( 7736): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7736): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7736): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7736): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7736): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7736): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7736): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7736): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7736): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7736): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7736): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7736): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7736): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7736): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7736): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7736:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
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
,E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices
W/NativeLibraryUtils( 7603): Failed to open lock file
W/NativeLibraryUtils( 7603): java.io.FileNotFoundException: /data/data/com.google.android.gms/cache/.lib.lock: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7603): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/NativeLibraryUtils( 7603): 	at java.io.RandomAccessFile.<init>(RandomAccessFile.java:118)
W/NativeLibraryUtils( 7603): 	at com.google.android.gms.common.util.ay.b(SourceFile:325)
W/NativeLibraryUtils( 7603): 	at com.google.android.gms.common.app.b.run(SourceFile:209)
W/NativeLibraryUtils( 7603): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/NativeLibraryUtils( 7603): 	at libcore.io.Posix.open(Native Method)
W/NativeLibraryUtils( 7603): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/NativeLibraryUtils( 7603): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/NativeLibraryUtils( 7603): 	... 3 more
,I/dalvikvm( 7603): Could not find method android.os.UserHandle.isOwner, referenced from method com.google.android.gms.icing.service.w.a
W/dalvikvm( 7603): VFY: unable to resolve virtual method 1199: Landroid/os/UserHandle;.isOwner ()Z
,D/dalvikvm( 7603): VFY: replacing opcode 0x6e at 0x002b
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
,D/dalvikvm( 7757): GC_CONCURRENT freed 2998K, 32% free 9574K/13968K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7757): WAIT_FOR_CONCURRENT_GC blocked 15ms,
,I/GservicesProvider( 7757): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7757): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7757): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7757): ,	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7757): ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
,E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7757): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7757): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
,E/SQLiteDatabase( 7757): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7757): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7757): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7757): Shutting down VM,
,W/dalvikvm( 7757): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
,I/Process ( 7757): Sending signal. PID: 7757 SIG: 9,
E/AndroidRuntime( 7757): FATAL EXCEPTION: main
E/AndroidRuntime( 7757): Process: com.google.process.gapps, PID: 7757
E/AndroidRuntime( 7757): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7757): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7757): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7757): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7757): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7757): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7757): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291),
E/AndroidRuntime( 7757): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7757): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7757): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
,E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7757): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7757): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7757): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7757): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7757): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7757): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294),
E/AndroidRuntime( 7757): 	... 12 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7757) (adj 0) has died.,
,I/SELinux ( 7772): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7772):  
,I/SELinux ( 7772): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7772):  
I/SELinux ( 7772):  
,I/SELinux ( 7772): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7772): >>>>> Normal User
,E/dalvikvm( 7772): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ],
,E/SELinux ( 7772): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted,
,D/TimaKeyStoreProvider( 7772): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7772): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7772): Added TimaKesytore provider
,D/dalvikvm( 7772): GC_CONCURRENT freed 2978K, 32% free 9591K/13964K, paused 4ms+2ms, total 19ms,
,D/dalvikvm( 7772): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,I/GservicesProvider( 7772): Gservices pushing to system: true; secure/global: true,
E/SQLiteDatabase( 7772): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.,
E/SQLiteDatabase( 7772): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7772): 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
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
E/SQLiteDatabase( 7772): 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
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
,W/dalvikvm( 7772): threadid=1: thread exiting with uncaught exception (group=0x4180ac08),
E/AndroidRuntime( 7772): FATAL EXCEPTION: main
E/AndroidRuntime( 7772): Process: com.google.process.gapps, PID: 7772
E/AndroidRuntime( 7772): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7772): ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7772): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7772): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7772): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7772): ,	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7772): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7772): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7772): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7772): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512),
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7772): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7772): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7772): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164),
E/AndroidRuntime( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7772): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7772): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7772): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7772): 	... 12 more
W/ActivityManager( 2422): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2422): Killing 7772:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2422): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2422): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2422): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2422): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272),
E/DropBoxManagerService( 2422): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2422): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2422): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2422): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2422): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2422): 	... 5 more
E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices,
I/dalvikvm( 7603): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.nb.a
W/dalvikvm( 7603): VFY: unable to resolve virtual method 424: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7603): VFY: replacing opcode 0x6e at 0x000d,
E/ActivityThread( 7603): Failed to find provider info for com.google.android.gsf.gservices
,D/dalvikvm( 7603): Trying to load lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4230d440
,D/dalvikvm( 7603): Added shared lib /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4230d440
,D/dalvikvm( 7603): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libAppDataSearch.so 0x4230d440, skipping init
,I/dalvikvm( 7603): Could not find method android.app.AlarmManager.setExactAndAllowWhileIdle, referenced from method com.google.android.gms.common.stats.b.a
W/dalvikvm( 7603): VFY: unable to resolve virtual method 69: Landroid/app/AlarmManager;.setExactAndAllowWhileIdle (IJLandroid/app/PendingIntent;)V
,D/dalvikvm( 7603): VFY: replacing opcode 0x6e at 0x0010
,I/SELinux ( 7791): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7791):  
,I/SELinux ( 7791): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7791):  
I/SELinux ( 7791):  
,I/SELinux ( 7791): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7791): >>>>> Normal User
,E/dalvikvm( 7791): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7791): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/TimaKeyStoreProvider( 7791): in addTimaSignatureService
D/TimaKeyStoreProvider( 7791): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7791): Added TimaKesytore provider
,D/dalvikvm( 7791): GC_CONCURRENT freed 2982K, 32% free 9581K/13960K, paused 2ms+2ms, total 18ms
,D/dalvikvm( 7791): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/GservicesProvider( 7791): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7791): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7791): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7791): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7791): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7791): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7791): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7791): Shutting down VM
,W/dalvikvm( 7791): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,I/Process ( 7791): Sending signal. PID: 7791 SIG: 9
E/AndroidRuntime( 7791): FATAL EXCEPTION: main
E/AndroidRuntime( 7791): Process: com.google.process.gapps, PID: 7791
E/AndroidRuntime( 7791): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7791): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7791): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7791): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7791): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7791): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7791): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7791): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7791): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7791): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7791): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7791): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7791): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7791): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7791): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7791): 	... 12 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop233.tmp: open failed: EROFS (Read-only file system)
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
,I/ActivityManager( 2422): Process com.google.process.gapps (pid 7791) (adj 0) has died.
,I/SELinux ( 7807): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7807):  
,I/SELinux ( 7807): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7807):  
I/SELinux ( 7807):  
,I/SELinux ( 7807): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7807): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7807): >>>>> Normal User
,E/dalvikvm( 7807): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7807): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted

```
