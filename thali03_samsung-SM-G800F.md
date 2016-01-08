#### Test 5546736337bcedb_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/main,
I/ClearcutLoggerApiImpl( 2856): disconnect managed GoogleApiClient
D/AndroidRuntime( 7232): 
D/AndroidRuntime( 7232): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7232): CheckJNI is OFF
D/AndroidRuntime( 7232): setted country_code = Poland
D/AndroidRuntime( 7232): setted countryiso_code = PL
D/AndroidRuntime( 7232): setted sales_code = PLS
D/AndroidRuntime( 7232): readGMSProperty: start
D/AndroidRuntime( 7232): readGMSProperty: already setted!!
D/AndroidRuntime( 7232): readGMSProperty: end
D/AndroidRuntime( 7232): addProductProperty: start
D/dalvikvm( 7232): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7232): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7232): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7232): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7232): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7232): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7232): failed to load memtrack module: -2
D/dalvikvm( 7232): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7232): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2420): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of /dev/log/system
D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2420): mDVFSHelper.acquire()
I/SELinux ( 7259): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7259):  
D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7232): Shutting down VM
D/dalvikvm( 7232): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
I/SELinux ( 7259): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7259):  
I/SELinux ( 7259):  
I/SELinux ( 7259): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7259): >>>>> Normal User
E/dalvikvm( 7259): >>>>> com.test.thalitest [ userId:0 | appId:10595 ]
E/SELinux ( 7259): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7259): in addTimaSignatureService
D/TimaKeyStoreProvider( 7259): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7259): Added TimaKesytore provider
I/SQLiteSecureOpenHelper( 4165): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4165): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (8/10)
I/SurfaceFlinger( 1920): id=18 Removed YUIInstallC (-2/10)
D/dalvikvm( 7259): GC_CONCURRENT freed 3009K, 30% free 9562K/13468K, paused 1ms+2ms, total 17ms
D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 16ms
V/WebViewChromium( 7259): Binding Chromium to the background looper Looper (main, tid 1) {42233160}
I/chromium( 7259): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7259): Initializing chromium process, renderers=0
W/chromium( 7259): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7259): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7259): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7259): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7259): Mali API Version : 401
,I/Mali    ( 7259): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7259): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
,W/dalvikvm( 7259): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7259): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7259): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0008
,D/StatusBarManagerService( 2420): tr p:7259,o:f
D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=true, mMultiWindowMode=false
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7259): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7259): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7259): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7259): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7259): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7259): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7259): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7259): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2420): semi p:7259,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=19 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2420): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2420): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2420): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2420): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2420): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7259): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7259): Enabling debug mode 0
,W/AwContents( 7259): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2420): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2420): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/AwContents( 7259): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7259): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7259): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7259): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42233ee8
D/dalvikvm( 7259): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42233ee8
D/jxcore_app_log( 7259): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027656288
D/JX-Cordova( 7259): jxcore cordova android initializing
D/dalvikvm( 7259): GC_CONCURRENT freed 1283K, 17% free 11351K/13528K, paused 2ms+2ms, total 24ms
D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 13ms
D/CustomFrequencyManagerService( 2420): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2420  tag : ACTIVITY_RESUME_BOOSTER@8
D/dalvikvm( 7259): GC_CONCURRENT freed 1898K, 16% free 15002K/17812K, paused 2ms+2ms, total 49ms
D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 5371K, 29% free 16245K/22760K, paused 42ms, total 42ms
,D/dalvikvm( 7259): GC_CONCURRENT freed 6693K, 31% free 17708K/25332K, paused 3ms+9ms, total 66ms
,D/dalvikvm( 7259): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 1131K, 31% free 17700K/25332K, paused 39ms, total 39ms
,I/dalvikvm-heap( 7259): Grow heap (frag case) to 21.698MB for 3713210-byte allocation
,D/dalvikvm( 7259): GC_FOR_ALLOC freed 2479K, 35% free 18847K/28960K, paused 35ms, total 35ms
,W/jxcore-log( 7259): Initializing JXcore engine
,W/jxcore-log( 7259): JXcore engine is ready
,W/jxcore-log( 7259): Starting JXcore engine
,W/jxcore-log( 7259): Platform android
W/jxcore-log( 7259): 
,W/jxcore-log( 7259): Process ARCH arm
W/jxcore-log( 7259): 
,I/jxcore-log( 7259): JXcore Cordova bridge is ready!
I/jxcore-log( 7259): 
,W/jxcore-log( 7259): JXcore engine is started
,I/chromium( 7259): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7259): Toggling radios to true
I/jxcore-log( 7259): 
,D/BluetoothAdapter( 7259): enable(): BT is already enabled..!
,I/WifiManager( 7259): packageName : com.test.thalitest
,I/WifiManager( 7259): setWifiEnabled : true
,I/WifiService( 2420): setWifiEnabled: true pid=7259, uid=10595
,W/ActivityManager( 2420): Permission Denial: getCurrentUser() from pid=7259, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): Failed getting userId using ActivityManagerNative
W/WifiService( 2420): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7259, uid=10595 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2420): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2420): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2420): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2420): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2420): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2420): disconnect: pid=7259, uid=10595
I/jxcore-log( 7259): Radios toggled
I/jxcore-log( 7259): 
I/wpa_supplicant( 3977): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7259): Received device characteristics:
I/jxcore-log( 7259): Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7259): Bluetooth name: S5mini-1
I/jxcore-log( 7259): Device name: samsung-SM-G800F
I/jxcore-log( 7259): 
,I/jxcore-log( 7259): Perf Test app loaded loaded
I/jxcore-log( 7259): 
,I/wpa_supplicant( 3977): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3977): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3977): First Scan Start
D/Tethering( 2420): interfaceStatusChanged wlan0, true
W/Settings( 2420): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2420): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3977): Scan requested (ret=0) - scan timeout 30 seconds
,I/jxcore-log( 7259): check test folder,
I/jxcore-log( 7259): 
D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
I/jxcore-log( 7259): found test : ./testFindPeers.js
I/jxcore-log( 7259): 
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
D/ConnectivityService( 2420): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
I/wpa_supplicant( 3977): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3977): Skip scan - already scanning
D/ConnectivityService( 2420): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2420): net.tcp.usercfg.default not found in system default properties
D/WifiP2pService( 2420): InactiveState{ what=143375 }
D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2420): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2420): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,I/SELinux ( 7306): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7306):  
D/ConnectivityService( 2420): Attempting to switch to mobile
D/ConnectivityService( 2420): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/jxcore-log( 7259): found test : ./testSendData.js
I/jxcore-log( 7259): 
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-67ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-66ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7306): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7306):  
I/SELinux ( 7306):  
,I/SELinux ( 7306): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7306): >>>>> Normal User
,E/dalvikvm( 7306): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7306): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/WifiStateMachine( 2420): Error! unhandled message{ when=-9ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/TimaKeyStoreProvider( 7306): in addTimaSignatureService
,W/NetworkManagementService( 2420): route cmd failed: 
W/NetworkManagementService( 2420): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2420): '
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2420): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2420): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2420): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2420): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2420): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2420): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7306): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7306): Added TimaKesytore provider
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/NetUtils( 2420): android_net_utils_resetConnections in env=0x77dc0a98 clazz=0x62600001 iface=wlan0 mask=0x3
D/ConnectivityService( 2420): resetConnections(wlan0, 3)
,D/dalvikvm( 7306): GC_CONCURRENT freed 2996K, 29% free 9580K/13472K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7306): WAIT_FOR_CONCURRENT_GC blocked 15ms
,V/NativeCrypto( 2856): Read error: ssl=0x7c0a21d0: I/O error during system call, Connection timed out
,V/NativeCrypto( 2856): SSL shutdown failed: ssl=0x7c0a21d0: I/O error during system call, Broken pipe
,I/System.out( 7306): Inside WakeupProvider
,I/System.out( 7306): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7306): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7306): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
E/SPPClientService( 5536): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,D/VlingoApplication( 7306): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,E/SPPClientService( 5536): [e] exceptionCaught(). NET_TIMEOUT
,I/Choreographer( 7259): Skipped 165 frames!  The application may be doing too much work on its main thread.
,I/chromium( 7259): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,E/SPPClientService( 5536): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/ConnectivityService( 2420): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,E/SPPClientService( 5536): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5536): [b] ResponseMap empty
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 63ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/dalvikvm( 2420): GC_CONCURRENT freed 4519K, 74% free 25561K/95212K, paused 14ms+18ms, total 226ms
,D/dalvikvm( 2420): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/DialogFlow( 7306): initQueue()
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4360, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
I/ActivityManager( 2420): Killing 6237:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2833): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2420): updateDataUsageMap
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): noConnectivity : true
,I/DBG_DM  ( 4749): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
I/wpa_supplicant( 3977): nl80211: Received scan results (8 BSSes)
,I/wpa_supplicant( 3977): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3977): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3977): Associated with C0.AA.48
I/wpa_supplicant( 3977): freq(2412) increment count 2
,I/wpa_supplicant( 3977): meet head of list.
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3977): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3977): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3977): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2420): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2420): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7337): GC_CONCURRENT freed 2992K, 29% free 9570K/13464K, paused 3ms+3ms, total 40ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 41ms
,D/WifiNative( 2420): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/ActivityManager( 2420): Killing 6306:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/SELinux ( 7351): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7351):  
,I/SELinux ( 7351): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7351):  
I/SELinux ( 7351):  
,I/SELinux ( 7351): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7351): >>>>> Normal User
,E/dalvikvm( 7351): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7351): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7351): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7351): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7351): Added TimaKesytore provider
,D/dalvikvm( 7351): GC_CONCURRENT freed 3003K, 29% free 9572K/13472K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7351): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/dhcpcd  ( 7363): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7363): bssid match
,I/ActivityManager( 2420): Killing 6320:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7374): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7374):  
,I/SELinux ( 7374): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7374):  
I/SELinux ( 7374):  
,I/SELinux ( 7374): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7374): >>>>> Normal User
,E/dalvikvm( 7374): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7374): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7374): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7374): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7374): Added TimaKesytore provider
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,I/jxcore-log( 7259): Connected to the server!
I/jxcore-log( 7259): 
,D/dalvikvm( 7374): GC_CONCURRENT freed 3000K, 29% free 9568K/13468K, paused 5ms+3ms, total 36ms
,D/dalvikvm( 7374): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/KLMS-2.3.201 : ( 7374): KLMSValidator() : checkQATesting()
,I/chromium( 7259): [INFO:CONSOLE(63)] "logCallback Connected to the server", source: file:///android_asset/www/js/thali_main.js (63)
,I/KLMS-2.3.201 : ( 7374): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452264794942
,I/KLMS-2.3.201 : ( 7374): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,D/WifiP2pService( 2420): InactiveState{ what=143375 }
,D/WifiP2pService( 2420): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2420): Killing 6255:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7403): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7403):  
,D/WifiStateMachine( 2420): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2420): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2420): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 9% free 9506K/10444K, paused 4ms+5ms, total 58ms
,D/WifiStateMachine( 2420): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2420): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7403): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7403):  
I/SELinux ( 7403):  
,I/SELinux ( 7403): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7403): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7403): >>>>> Normal User
,E/dalvikvm( 7403): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7403): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/WifiTrafficPoller( 2420): evaluateTrafficStatsPolling
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9506K/10444K, paused 4ms+5ms, total 40ms
D/ConnectivityService( 2420): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2420): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2420): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/TimaKeyStoreProvider( 7403): in addTimaSignatureService
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9506K/10444K, paused 3ms+4ms, total 37ms
D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/TimaKeyStoreProvider( 7403): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7403): Added TimaKesytore provider
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/dalvikvm( 7403): GC_CONCURRENT freed 3004K, 29% free 9568K/13472K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7403): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7403): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7403): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): updateIfacesLocked()
,V/NetworkStats( 2420): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
V/NetworkStats( 2420): performPollLocked() took 25ms
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SA      ( 5800): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5800): [BDLM] already registered in spp
,I/SA      ( 5800): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5800): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5800): [OR] == isSIMCardReady false ==
,I/SA      ( 5800): [SCU] == networkStateCheck == true
I/SA      ( 5800): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5800): isChinaCountryCode : false
,I/SA      ( 5800): [OR] == networkStateCheck true ==
,I/SA      ( 5800): [OR] GetMyCountryZoneTask
I/SA      ( 5800): [OR] onReceive END
,I/SA      ( 5800): [SRS] prepareGetMyCountryZone
,I/SA      ( 5800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5800): [SSP] query invoked
I/ActivityManager( 2420): Killing 6377:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,I/SA      ( 5800): [TPMU] GetMccFromDB : null
,I/SA      ( 5800): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5800): [TPM] isNoProxy(default) : true
,I/SA      ( 5800): [RC New] Execute method=[GET] start
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,I/SELinux ( 7435): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7435):  
,I/SELinux ( 7435): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7435):  
I/SELinux ( 7435):  
,I/SELinux ( 7435): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7435): >>>>> Normal User
,E/dalvikvm( 7435): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7435): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7435): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7435): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7435): Added TimaKesytore provider
,D/dalvikvm( 7435): GC_CONCURRENT freed 2997K, 29% free 9577K/13472K, paused 2ms+2ms, total 30ms
,D/dalvikvm( 7435): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/sCloudBackupApp( 7435): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7435): Other Intent
I/ActivityManager( 2420): Killing 5582:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,I/SELinux ( 7448): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7448):  
,D/Tethering( 2420): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2420): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2420): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/SELinux ( 7448): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7448):  
I/SELinux ( 7448):  
,I/SELinux ( 7448): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7448): >>>>> Normal User
,E/dalvikvm( 7448): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7448): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/DBG_DM  ( 4749): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/TimaKeyStoreProvider( 7448): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7448): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7448): Added TimaKesytore provider
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection...
,D/dalvikvm( 7448): GC_CONCURRENT freed 2994K, 29% free 9574K/13464K, paused 3ms+3ms, total 32ms
,D/dalvikvm( 7448): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7448): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7448): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5332): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7448): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5332): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7448): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5332): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2420): Killing 6286:com.sec.phone/1001 (adj 15): empty #43
,D/Headlines( 5867): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5867): getCountryCode(): countryCode = PL
,D/Headlines( 5867): Breath.onCreate
,D/Headlines( 5867): Breath timer started. interval : 30000
,I/SELinux ( 7460): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7460):  
,V/AlarmManager( 2420): waitForAlarm result :8
D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5867): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5867): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5867): requestUpdateNewsWelcomeCard !!! no welcome card
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/PackageManager( 2420): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SELinux ( 7460): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7460):  
I/SELinux ( 7460):  
,I/SELinux ( 7460): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7460): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7460): >>>>> Normal User
,E/dalvikvm( 7460): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,I/SA      ( 5800): [RC New] [v2liruge] api execute + 808
,I/SA      ( 5800): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,E/SELinux ( 7460): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/System.out( 5800): AsyncTask #2 calls detatch()
,I/SA      ( 5800): [TPMU] getNetworkMcc : 
,D/TimaKeyStoreProvider( 7460): in addTimaSignatureService
I/SA      ( 5800): [SCU] saveMccToPreferece Start
I/SA      ( 5800): [SCU] RegionMCC : 260
,I/SA      ( 5800): [SSP] query invoked
,I/SA      ( 5800): [TPMU] GetMccFromDB : null
,I/SA      ( 5800): [SCU] getMccFromPreferece mcc = 260
D/TimaKeyStoreProvider( 7460): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5800): [SCU] saveMccToPreferece End
I/SA      ( 5800): [RC New] executeRequest [v2liruge] end. 844
,I/SA      ( 5800): [RC New] Execute end
I/SA      ( 5800): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 5800): [OR] GetMyCountryZoneTask Success
,D/ActivityThread( 7460): Added TimaKesytore provider
,D/dalvikvm( 7460): GC_CONCURRENT freed 2991K, 29% free 9582K/13468K, paused 5ms+2ms, total 34ms
,D/dalvikvm( 7460): WAIT_FOR_CONCURRENT_GC blocked 25ms
,V/WebViewChromium( 7460): Binding Chromium to the background looper Looper (main, tid 1) {42230248}
,I/chromium( 7460): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7460): Initializing chromium process, renderers=0
,W/chromium( 7460): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7460): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7460): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7460): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7460): Mali API Version : 401
,I/Mali    ( 7460): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7460): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7460): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7460): Starting up...
,I/iu.Environment( 5932): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5135): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5135): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5135): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4223d770
,D/libgps  ( 2420): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection...
,I/SELinux ( 7498): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7498):  
,I/SELinux ( 7498): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7498):  
I/SELinux ( 7498):  
,I/SELinux ( 7498): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7498): >>>>> Normal User
,E/dalvikvm( 7498): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7498): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7498): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7498): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7498): Added TimaKesytore provider
,D/dalvikvm( 7498): GC_CONCURRENT freed 2994K, 29% free 9578K/13472K, paused 4ms+2ms, total 30ms
,D/dalvikvm( 7498): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/SELinux ( 7517): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7517):  
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,I/ActivityManager( 2420): Killing 6310:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,W/ActivityManager( 2420): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7517): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7517):  
I/SELinux ( 7517):  
,I/SELinux ( 7517): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7517): [DEBUG] seapp_context_lookup: seinfoCategory = release
,I/SELinux ( 7521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7521):  
E/dalvikvm( 7517): >>>>> Normal User
,E/dalvikvm( 7517): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7517): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7517): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7517): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7517): Added TimaKesytore provider
,I/SELinux ( 7521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7521):  
I/SELinux ( 7521):  
,I/SELinux ( 7521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,I/ActivityManager( 2420): Killing 5977:com.android.calendar/u0a144 (adj 15): empty #43
E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7521): >>>>> Normal User
E/dalvikvm( 7521): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7521): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7521): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7521): Added TimaKesytore provider
,D/dalvikvm( 7517): GC_CONCURRENT freed 3005K, 29% free 9568K/13468K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7517): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/BadgeProvider( 7517): onCreate
,D/BadgeProvider( 7517): DatabaseHelper
,D/BadgeProvider( 7517): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7521): GC_CONCURRENT freed 3002K, 29% free 9569K/13468K, paused 4ms+2ms, total 36ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 30ms
D/Launcher.Model( 2769): reloadBadges entered.
D/BadgeProvider( 7517): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7517): sendNotify, [notify] : null
D/BadgeProvider( 7517): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7517): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7517): update, [UpdateCount] : 1
,D/hcjo    ( 5953): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5953): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5953): exit::IDLE
,D/InitializeManagerStateMachine( 5953): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5953): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5953): exit::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5953): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5953): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): entry::SUCCESS
,D/hcjo    ( 5953): AutoUpdateManager:INITCHECK:onInitializeSuccess
I/dalvikvm( 7259): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7259): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0002
D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5953): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5953): exit::SUCCESS
,D/InitializeManagerStateMachine( 5953): entry::IDLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7259): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7259): BLE is supported
I/jxcore-log( 7259): 
,E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 281190
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5536): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5536): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2833): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2833): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5536): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,I/ActivityManager( 2420): Killing 6153:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/libgps  ( 2420): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2420): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2420): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
D/PowerManagerService( 2420): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420
,D/NearbySettings( 2833): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2833): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
,I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7374): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7374): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452264798319
,I/KLMS-2.3.201 : ( 7374): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,W/WifiP2pStateTracker( 2420): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2420): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2420):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2420): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2420): updateSourceRoutes : no source routing conditions
,I/LocationTagReadyService( 3252): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
,D/SO_AGENT( 7403): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3252): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7403): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3380): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/dalvikvm( 7351): Total arena pages for JIT: 11
,I/dalvikvm( 7351): Total arena pages for JIT: 12
,I/dalvikvm( 7351): Total arena pages for JIT: 13
,I/dalvikvm( 7351): Total arena pages for JIT: 14
,I/dalvikvm( 7351): Total arena pages for JIT: 15
,I/dalvikvm( 7351): Total arena pages for JIT: 16
,I/dalvikvm( 7351): Total arena pages for JIT: 17
,E/WifiStateMachine( 2420): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,D/dalvikvm( 2721): GC_EXPLICIT freed 283K, 31% free 10048K/14364K, paused 14ms+11ms, total 123ms
,I/SELinux ( 7553): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7553):  
,I/SA      ( 5800): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5800): [BDLM] already registered in spp
I/SA      ( 5800): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5800): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5800): [OR] == isSIMCardReady false ==
,I/SA      ( 5800): [SCU] == networkStateCheck == true
I/SA      ( 5800): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5800): isChinaCountryCode : false
,I/SA      ( 5800): [OR] == networkStateCheck true ==
,I/SA      ( 5800): [OR] GetMyCountryZoneTask
,I/SA      ( 5800): [OR] onReceive END
,I/SA      ( 5800): [SRS] prepareGetMyCountryZone
,I/SA      ( 5800): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5800): [SSP] query invoked
,I/SA      ( 5800): [TPMU] GetMccFromDB : null
I/SA      ( 5800): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5800): [TPM] isNoProxy(default) : true
,I/SA      ( 5800): [RC New] Execute method=[GET] start
,I/SELinux ( 7553): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7553):  
I/SELinux ( 7553):  
,I/SELinux ( 7553): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7553): >>>>> Normal User
E/dalvikvm( 7553): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
D/PhoneNumberLocatorBootCompletedReceiver( 2752): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2752): Phone number locator feature is dsiabled
,E/SELinux ( 7553): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SCloudBackupReceiver( 7435): Other Intent
,D/TimaKeyStoreProvider( 7553): in addTimaSignatureService
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7448): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 7553): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7553): Added TimaKesytore provider
,I/System.out( 7351): Thread-633(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SELinux ( 7570): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7570):  
,I/System.out( 7351): Thread-633(ApacheHTTPLog):isShipBuild true
,I/System.out( 7351): Thread-633(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Headlines( 5867): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5867): getCountryCode(): countryCode = PL
,D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5867): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5867): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5867): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5867): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5932): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/SELinux ( 7570): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7570):  
I/SELinux ( 7570):  
,I/SELinux ( 7570): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7570): >>>>> Normal User
,E/dalvikvm( 7570): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/QuickConnect[1.1][2] ( 5135): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5135): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
V/QuickConnect[1.1][2] ( 5135): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4223d770
,E/SELinux ( 7570): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/RCPManagerService( 2420): exchangeData() failure , invalid userId
,D/dalvikvm( 7553): GC_CONCURRENT freed 2996K, 29% free 9580K/13472K, paused 4ms+3ms, total 34ms
,D/dalvikvm( 7553): WAIT_FOR_CONCURRENT_GC blocked 33ms
,D/TimaKeyStoreProvider( 7570): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7570): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7570): Added TimaKesytore provider
,D/hcjo    ( 5953): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5953): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5953): exit::IDLE
,D/InitializeManagerStateMachine( 5953): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 5953): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 5953): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5953): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5953): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5953): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5953): entry::SUCCESS
,D/hcjo    ( 5953): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5953): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5953): exit::SUCCESS
,D/InitializeManagerStateMachine( 5953): entry::IDLE
,D/dalvikvm( 7570): GC_CONCURRENT freed 2998K, 29% free 9570K/13464K, paused 2ms+5ms, total 32ms
,D/dalvikvm( 7570): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/System.out( 7351): AsyncTask #1 calls detatch()
,E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 282364
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : false
,W/System.err( 7351): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7351): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7351): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7351): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7351): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7351): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 7351): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7351): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7351): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7351): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7351): Caused by: java.lang.NullPointerException
,W/System.err( 7351): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7351): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7351): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7351): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7351): 	... 8 more
,D/Headlines( 5867): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5867): Breath 200 latestRequest time : 1452264798722 current time : 1452264798922
,V/KVNProvider( 7570): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7570): getFindoCursor query string : 
,V/KVNProvider( 7570): getTagSearchCursor() tagSearchCursor count : 0
,I/ActivityManager( 2420): Killing 6190:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5536): GC_CONCURRENT freed 2006K, 23% free 10444K/13460K, paused 8ms+6ms, total 56ms
,I/SA      ( 5800): [RC New] [v2liruge] api execute + 523
,I/SA      ( 5800): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5800): AsyncTask #3 calls detatch()
,I/SA      ( 5800): [TPMU] getNetworkMcc : 
I/SA      ( 5800): [SCU] saveMccToPreferece Start
I/SA      ( 5800): [SCU] RegionMCC : 260
,I/SA      ( 5800): [SSP] query invoked
,I/SA      ( 5800): [TPMU] GetMccFromDB : null
I/SA      ( 5800): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5800): [SCU] saveMccToPreferece End
I/SA      ( 5800): [RC New] executeRequest [v2liruge] end. 543
,I/SA      ( 5800): [RC New] Execute end
I/SA      ( 5800): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5800): [OR] GetMyCountryZoneTask Success
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 2420): GC_EXPLICIT freed 2167K, 73% free 25502K/94072K, paused 20ms+23ms, total 288ms
,E/SPPClientService( 5536): [b] __InitReply__
,I/ActivityManager( 2420): Killing 6517:com.android.defcontainer/u0a6 (adj 15): empty #43
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=20 Removed Uoast (-2/11)
,D/PowerManagerService( 2420): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2420) eventTime = 284930
,D/PowerManagerService( 2420): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2420 (0x0)
,D/PowerManagerService( 2420): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=3502)
,I/GAV2    ( 7460): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6576): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6576): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6576): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6576): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6576): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6576): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6576): [ensureRegistration] - No Samsung account
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 9
,D/CaptivePortalTracker( 2420): DelayedCaptiveCheckState{ when=0 what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 2420): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2420): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2420): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2420): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2420): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2420): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2420): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5953): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5953): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5953): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5953): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5953): entry::IDLE
,D/PreloadUpdateManagerStateMachine( 5953): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5953): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5953): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5953): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5953): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5953): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5953): entry::IDLE
,I/PowerManagerService( 2420): [PWL] Off : 225s ago
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{463181c8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/ActivityManager( 2420): Waited long enough for: ServiceRecord{42363790 u0 com.sec.spp.push/.PushClientService}
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2420): waitForAlarm result :8
,D/Headlines( 5867): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5867): Breath 27495 latestRequest time : 1452264798722 current time : 1452264826217
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 2420): initializing...
,I/TLC_TIMA_PKM_initialize( 2420): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2420): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 2420): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2420): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2420): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2420): aligned max_sendmsg_size = 262208
,I/TZ: mc_tlc_communication( 2420): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2420): device_id = 0x0
,I/TZ: mc_tlc_communication( 2420): tlc_open() was called
,I/TZ: mc_tlc_communication( 2420): Opening MobiCore device
,I/TZ: mc_tlc_communication( 2420): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 2420): Opening the session
,I/TZ: mc_tlc_communication( 2420): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2420): Trustlet response is completed
,E/Watchdog( 2420): !@Sync 10
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 275s ago
,E/Watchdog( 2420): !@Sync 11
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 8105): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8105):  
,I/SELinux ( 8105): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8105):  
I/SELinux ( 8105):  
,I/SELinux ( 8105): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8105): [DEBUG] seapp_context_lookup: seinfoCategory = default
,E/dalvikvm( 8105): >>>>> Normal User
,E/dalvikvm( 8105): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ]
,E/SELinux ( 8105): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider( 8105): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8105): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8105): Added TimaKesytore provider
,D/dalvikvm( 8105): GC_CONCURRENT freed 3014K, 30% free 9561K/13472K, paused 3ms+1ms, total 24ms
,D/dalvikvm( 8105): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/Headlines( 5867): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5867): Breath 71649 latestRequest time : 1452264798722 current time : 1452264870371
,I/ActivityManager( 2420): Killing 6440:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 12
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8295
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8297
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8298
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8300
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8302
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8303
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8305
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8307
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8308
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 8309
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/Headlines( 5867): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5867): Breath 108483 latestRequest time : 1452264798722 current time : 1452264907205
,I/SELinux ( 8337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8337):  
,I/SELinux ( 8337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8337):  
I/SELinux ( 8337):  
,I/SELinux ( 8337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8337): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8337): >>>>> Normal User
,E/dalvikvm( 8337): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8337): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8337): Added TimaKesytore provider
,D/dalvikvm( 8337): GC_CONCURRENT freed 3000K, 29% free 9569K/13468K, paused 3ms+3ms, total 34ms
,D/dalvikvm( 8337): WAIT_FOR_CONCURRENT_GC blocked 29ms
,E/SPPClientService( 8337): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8337): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8337): PushLog.txt file is not deleted.
D/SPPClientService( 8337): PushLog.txt file is not deleted.
,D/SPPClientService( 8337): ============PushLog. stop!
,I/ActivityManager( 2420): Killing 6547:com.samsung.groupcast/u0a15 (adj 15): empty #43
,E/SPPClientService( 5536): [b] __PingReply__
,I/jxcore-log( 7259): --- start :testFindPeers.js---
I/jxcore-log( 7259): 
,I/jxcore-log( 7259): testFindPeers created [object Object]
I/jxcore-log( 7259): 
,I/jxcore-log( 7259): serverPort is 8876
I/jxcore-log( 7259): 
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7259): setDiscoveryMode: Mode set to BLE
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7259): setDiscoveryMode: Mode set to BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7259): start: Peer ID: 00:F4:6F:30:E0:6C, peer name: S5mini-1
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7259): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7259): initialize: My bluetooth address is 00:F4:6F:30:E0:6C
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 7259): verifyIdentityString: Identity string created: {"ra":"00:F4:6F:30:E0:6C","pi":"00:F4:6F:30:E0:6C","pn":"S5mini-1"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7259): startListeningForIncomingConnections
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): startListeningForIncomingConnections: Starting...
,W/BluetoothAdapter( 7259): getBluetoothService() called with no BluetoothManagerCallback
,E/BluetoothServiceJni( 4005): SOCK FLAG = 0 ***********************
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7259): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 7259): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Waiting for incoming connections...
,I/io.jxcore.node.ConnectionHelper( 7259): start: Using peer discovery mode: BLE_AND_WIFI
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7259): start: Peer ID: 00:F4:6F:30:E0:6C, peer name: S5mini-1
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 7259): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 7259): bind: Binding a new listener
,W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
E/dalvikvm( 7259): Could not find class 'org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>
,W/dalvikvm( 7259): VFY: unable to resolve new-instance 425 (Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 7259): VFY: replacing opcode 0x22 at 0x0013
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
I/dalvikvm( 7259): Could not find method android.bluetooth.le.ScanResult.getScanRecord, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.checkScanResult
W/dalvikvm( 7259): VFY: unable to resolve virtual method 90: Landroid/bluetooth/le/ScanResult;.getScanRecord ()Landroid/bluetooth/le/ScanRecord;
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0002
,E/dalvikvm( 7259): Could not find class 'android.bluetooth.le.AdvertiseSettings$Builder', referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.applySettings
W/dalvikvm( 7259): VFY: unable to resolve new-instance 20 (Landroid/bluetooth/le/AdvertiseSettings$Builder;) in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;
D/dalvikvm( 7259): VFY: replacing opcode 0x22 at 0x002d
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
,W/dalvikvm( 7259): VFY: unable to find class referenced in signature (Landroid/bluetooth/le/ScanResult;)
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 7259): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.start, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.start
W/dalvikvm( 7259): VFY: unable to resolve virtual method 1804: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.start ()Z
,D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0016
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
I/dalvikvm( 7259): Could not find method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser.stop, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.stop
W/dalvikvm( 7259): VFY: unable to resolve virtual method 1805: Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;.stop ()V
D/dalvikvm( 7259): VFY: replacing opcode 0x6e at 0x0003
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser; (17)
,W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleAdvertiser;' failed
D/dalvikvm( 7259): DexOpt: unable to opt direct call 0x0705 at 0x15 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
W/dalvikvm( 7259): Unable to resolve superclass of Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner; (24)
W/dalvikvm( 7259): Link of class 'Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BleScanner;' failed
,D/dalvikvm( 7259): DexOpt: unable to opt direct call 0x0726 at 0x25 in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.<init>
D/dalvikvm( 7259): DexOpt: unable to opt direct call 0x0048 at 0x2f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/dalvikvm( 7259): DexOpt: unable to opt direct call 0x005c at 0x5f in Lorg/thaliproject/p2p/btconnectorlib/internal/bluetooth/le/BlePeerDiscoverer;.applySettings
,D/AndroidRuntime( 7259): Shutting down VM
,W/dalvikvm( 7259): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): Uncaught exception: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): java.lang.NoClassDefFoundError: org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer.<init>(BlePeerDiscoverer.java:60)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.startBlePeerDiscovery(DiscoveryManager.java:488)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:248)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.start(DiscoveryManager.java:292)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at io.jxcore.node.ConnectionHelper.start(ConnectionHelper.java:116)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at io.jxcore.node.JXcoreExtension$6.Receiver(JXcoreExtension.java:177)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at android.os.Handler.handleCallback(Handler.java:733)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at android.os.Looper.loop(Looper.java:146)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): 	at dalvik.system.NativeStart.main(Native Method)
,I/PowerManagerService( 2420): [PWL] Off : 330s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 13
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
D/Headlines( 5867): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5867): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5867): Breath 137962 latestRequest time : 1452264798722 current time : 1452264936684
,D/Headlines( 5867): stop 
,D/Headlines( 5867): Breath.onDestroy : 
,I/ActivityManager( 2420): Killing 6560:com.android.musicfx/u0a24 (adj 15): empty #43
,I/EventLogService( 3441): Aggregate from 1452263136533 (log), 1452263136533 (data)
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2420): !@Sync 14
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK,
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2420): !@Sync 15
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 16
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/        ( 4005): remote version info [7c:f9:0e:34:8a:a0]: 7, f, 610c
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_CONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothConnectionReceiver( 6419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_CONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6419): Bluetooth Device Name: S5-1
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/dalvikvm( 6419): GC_CONCURRENT freed 2585K, 26% free 10068K/13548K, paused 5ms+3ms, total 61ms
D/dalvikvm( 6419): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/dalvikvm( 6419): WAIT_FOR_CONCURRENT_GC blocked 28ms
,I/SELinux ( 8843): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8843):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 9% free 9506K/10444K, paused 5ms+4ms, total 48ms
,I/SELinux ( 8843): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8843):  
I/SELinux ( 8843):  
,I/SELinux ( 8843): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8843): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 8843): >>>>> Normal User
,E/dalvikvm( 8843): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 8843): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9506K/10444K, paused 4ms+5ms, total 41ms
,D/TimaKeyStoreProvider( 8843): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8843): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8843): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 9% free 9506K/10444K, paused 4ms+5ms, total 40ms
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 1
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.CLASS_CHANGED
,I/BluetoothBondStateMachine( 4005): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 12 NewState: 11
D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,I/BluetoothBondStateMachine( 4005): Entering PendingCommandState State
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,I/CachedBluetoothDevice( 2833): updateProfiles
,I/CachedBluetoothDevice( 2833): updateProfiles
,D/dalvikvm( 8843): GC_CONCURRENT freed 2997K, 29% free 9579K/13472K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 8843): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/CachedBluetoothDevice( 2833): updateProfiles
,I/CachedBluetoothDevice( 2833): updateProfiles
,I/CachedBluetoothDevice( 2833): updateProfiles
,I/CachedBluetoothDevice( 2833): updateProfiles
,I/CachedBluetoothDevice( 2833): updateProfiles
,D/IOP_DB_BT( 4005): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,I/CachedBluetoothDevice( 2833): updateProfiles
,D/UserAnalysis.PlaceProvider( 8843): Create SecureDbHelper
,D/UserAnalysis.CarAnalyzer( 8843): Create SecureDbHelper
,I/ActivityManager( 2420): Killing 6588:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6657): jangil::setProperties()
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btif ( 4005): services_to_search = 3fffffff
,E/bt-btif ( 4005): ****************search UUID = 1200***********
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,W/BackupManagerService( 2420): dataChanged but no participant pkg='com.android.providers.settings' uid=10104
E/bt-btif ( 4005): RFCOMM: PORT_SUCCESS
,E/bt-btif ( 4005): services_to_search = 3ffffffe
,E/bt-btif ( 4005): ****************search UUID = 0100***********
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
W/BackupManagerService( 2420): dataChanged but no participant pkg='com.android.providers.settings' uid=10104
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection initialized (thread ID: 638)
D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Entering thread (ID: 638)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesRead: Read 63 bytes successfully (thread ID: 638)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Got valid identity from [7C:F9:0E:34:8A:A0 S5-1]
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesWritten: 67 bytes successfully written (thread ID: 638)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): removeThreadFromList: Removing thread with ID 638
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Handshake thread disposed (thread ID: 638)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): onIncomingConnectionConnected: [7C:F9:0E:34:8A:A0 S5-1]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Exiting thread (ID: 638)
,E/bt-btif ( 4005): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: 7C:F9:0E:34:8A:A0 newState: 0
,D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,I/BluetoothBondStateMachine( 4005): Bond State Change Intent:7C:F9:0E:34:8A:A0 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/HidService( 4005): getHidService(): returning com.android.bluetooth.hid.HidService@422a06a8
,D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
,W/BluetoothEventManager( 2833): showUnbondMessage: Not displaying any message for reason: 0
D/HidService( 4005): Saved priority 7C:F9:0E:34:8A:A0 = -1
,D/GMFPReceiver( 6657): jangil::setProperties()
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.UUID
,I/CachedBluetoothDevice( 2833): updateProfiles
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 4005): StableState(): Entering Off State
D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 2420): [PWL] Off : 455s ago
,E/bt-btif ( 4005): send none, EAGAIN or EWOULDBLOCK, errno:11
,D/btif_config_util( 4005): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,E/Watchdog( 2420): !@Sync 17
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/        ( 4005): remote version info [44:80:eb:7b:5a:05]: 6, 1d, 7d3
,E/BluetoothRemoteDevices( 4005): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d98c00 rs_disc_pending=1
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d992f0 rs_disc_pending=1
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 1
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.CLASS_CHANGED
I/BluetoothBondStateMachine( 4005): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 10 NewState: 11
D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,I/BluetoothBondStateMachine( 4005): Entering PendingCommandState State
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6657): jangil::setProperties()
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
,D/IOP_DB_BT( 4005): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 29
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 282, prevStep = 4, currStep = 4
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btif ( 4005): services_to_search = 3fffffff
,E/bt-btif ( 4005): ****************search UUID = 1200***********
,E/bt-btif ( 4005): RFCOMM: PORT_SUCCESS
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection initialized (thread ID: 639)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Entering thread (ID: 639)
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d992f0 rs_disc_pending=1
,E/bt-btif ( 4005): services_to_search = 3ffffffe
,E/bt-btif ( 4005): ****************search UUID = 0100***********
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesRead: Read 65 bytes successfully (thread ID: 639)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Got valid identity from [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesWritten: 67 bytes successfully written (thread ID: 639)
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): removeThreadFromList: Removing thread with ID 639
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Handshake thread disposed (thread ID: 639)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): onIncomingConnectionConnected: [44:80:EB:7B:5A:05 XT1072]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Exiting thread (ID: 639)
,E/bt-btif ( 4005): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 2 uuid:00001116-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 3 uuid:0000110e-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 4 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 5 uuid:00001112-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 6 uuid:0000111f-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 7 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 8 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: 44:80:EB:7B:5A:05 newState: 0
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 4005): Bond State Change Intent:44:80:EB:7B:5A:05 OldState: 11 NewState: 10
D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,D/HidService( 4005): getHidService(): returning com.android.bluetooth.hid.HidService@422a06a8
,D/HidService( 4005): Saved priority 44:80:EB:7B:5A:05 = -1
,I/BluetoothBondStateMachine( 4005): StableState(): Entering Off State
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,D/GMFPReceiver( 6657): jangil::setProperties()
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.UUID
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
,E/bt-btif ( 4005): send none, EAGAIN or EWOULDBLOCK, errno:11
,D/btif_config_util( 4005): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/IOP_DB_BT( 4005): db_query_create: id EnforceMasterRole :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/        ( 4005): remote version info [b0:c5:59:3f:75:69]: 7, f, 610c
,E/BluetoothRemoteDevices( 4005): aclStateChangeCallback: Device is NULL
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d994ac rs_disc_pending=0
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.NAME_CHANGED
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 1
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,I/BluetoothBondStateMachine( 4005): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 10 NewState: 11
,D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,I/BluetoothBondStateMachine( 4005): Entering PendingCommandState State
,D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6657): jangil::setProperties()
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.CLASS_CHANGED
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/IOP_DB_BT( 4005): db_query_create: id HidSdpBlacklist :: key KEY_BDADDR, value b0:c5:59:3f:75:69
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
,E/bt-btif ( 4005): RFCOMM: PORT_SUCCESS
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection accepted
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Incoming connection initialized (thread ID: 640)
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Waiting for incoming connections...
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Entering thread (ID: 640)
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d994ac rs_disc_pending=1
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
,E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
E/bt-btm  ( 4005): BTM_UseLeLink use le : 0
E/bt-btif ( 4005): services_to_search = 3fffffff
,E/bt-btif ( 4005): ****************search UUID = 1200***********
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d994ac rs_disc_pending=0
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesRead: Read 81 bytes successfully (thread ID: 640)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Got valid identity from [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): onBytesWritten: 67 bytes successfully written (thread ID: 640)
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): removeThreadFromList: Removing thread with ID 640
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 7259): Handshake thread disposed (thread ID: 640)
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 7259): onIncomingConnectionConnected: [B0:C5:59:3F:75:69 Thali Test (Galaxy S5)]
,D/org.thaliproject.p2p.btconnectorlib.utils.BluetoothSocketIoThread( 7259): Exiting thread (ID: 640)
,E/bt-btif ( 4005): services_to_search = 3ffffffe
,E/bt-btif ( 4005): ****************search UUID = 0100***********
,E/bt-btif ( 4005): Index: 0 uuid:0000110a-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 1 uuid:00001105-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 2 uuid:00001115-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 3 uuid:00001116-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 4 uuid:0000112d-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 5 uuid:0000112f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 6 uuid:00001112-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 7 uuid:0000111f-0000-1000-8000-00805f9b34fb
E/bt-btif ( 4005): Index: 8 uuid:00001132-0000-1000-8000-00805f9b34fb
,E/bt-btif ( 4005): Index: 9 uuid:fa87c0d0-afac-11de-8a39-0800200c9a66
,I/BluetoothBondStateMachine( 4005): bondStateChangeCallback: Status: 0 Address: B0:C5:59:3F:75:69 newState: 0
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.BOND_STATE_CHANGED
,I/BluetoothBondStateMachine( 4005): Bond State Change Intent:B0:C5:59:3F:75:69 OldState: 11 NewState: 10
,D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,D/HidService( 4005): getHidService(): returning com.android.bluetooth.hid.HidService@422a06a8
,D/HidService( 4005): Saved priority B0:C5:59:3F:75:69 = -1
,D/BtConfig.SecureMode( 4005): isSecureModeOn:false
,I/BluetoothBondStateMachine( 4005): StableState(): Entering Off State
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.UUID
,D/GMFPReceiver( 6657): android.bluetooth.device.action.BOND_STATE_CHANGED
,D/GMFPReceiver( 6657): jangil::setProperties()
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/GMFPReceiver( 6657): jangil::printBTStatus()
,D/GMFPReceiver( 6657): ::::::::Wearable0001::false
,D/dalvikvm( 2580): GC_CONCURRENT freed 15718K, 33% free 33872K/50484K, paused 44ms+10ms, total 165ms
,D/GMFPReceiver( 6657): ::::::::Wearable0002::false
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/bt-btif ( 4005): send none, EAGAIN or EWOULDBLOCK, errno:11
,D/btif_config_util( 4005): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/Watchdog( 2420): !@Sync 18
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d98c00 rs_disc_pending=0
,E/Watchdog( 2420): !@Sync 19
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 525s ago
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d992f0 rs_disc_pending=0
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 284, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3941K, 73% free 25480K/94072K, paused 22ms+24ms, total 257ms
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9236
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9238
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9239
,E/Watchdog( 2420): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,E/bt-btif ( 4005): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,E/bt-btm  ( 4005): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4005): btm_ble_resume_bg_conn 0
,D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 44:80:eb:7b:5a:05
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 29
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 6:2003
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,E/bt-btm  ( 4005): tBTM_SEC_DEV:0x77d994ac rs_disc_pending=1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.ACL_DISCONNECTED
,E/BluetoothEventManager( 2833): ACTION_ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,I/BluetoothConnectionReceiver( 6419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=44:80:EB:7B:5A:05, alias=null, name=XT1072, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6419): Bluetooth Device Name: XT1072
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,W/ContextImpl( 2420): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/bt-btif ( 4005): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
,E/bt-btm  ( 4005): btm_sec_disconnected - Clearing Pending flag
E/bt-btm  ( 4005): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value b0:c5:59:3f:75:69
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 2833): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=B0:C5:59:3F:75:69, alias=null, name=Thali Test (Galaxy S5), majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6419): Bluetooth Device Name: Thali Test (Galaxy S5)
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,E/bt-btif ( 4005): RFCOMM: PORT_FAILURE
,D/GKI_LINUX( 4005): acquire_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:0
E/bt-btm  ( 4005): btm_sec_disconnected - Clearing Pending flag
,E/bt-btm  ( 4005): btm_ble_resume_bg_conn 0
D/IOP_DB_BT( 4005): db_query_create: id DisablePwlCtrReq :: key KEY_BDADDR, value 7c:f9:0e:34:8a:a0
D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_MFCT, value 15
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_LMP_VER, value 7:24844
,D/IOP_DB_BT( 4005): db_query_add_key: key KEY_DIR_ALL, value *
,D/IOP_DB_BT( 4005): db_query_execute: result 1
,D/KeyguardViewMediator( 2580): Received android.bluetooth.device.action.ACL_DISCONNECTED
,V/BluetoothEventManager( 2833): Received android.bluetooth.device.action.ACL_DISCONNECTED
,D/KeyguardViewMediator( 2580): isGear1: device is not B1!
,E/BluetoothEventManager( 2833): ACTION_ACL_DISCONNECTED
,I/BluetoothConnectionReceiver( 6419): onReceive(context, Intent { act=android.bluetooth.device.action.ACL_DISCONNECTED flg=0x4000010 cmp=com.google.android.googlequicksearchbox/com.google.android.search.core.service.BluetoothConnectionReceiver (has extras) }, [BluetoothDevice: address=7C:F9:0E:34:8A:A0, alias=null, name=S5-1, majorDeviceClass=512, deviceClass=524])
,I/BluetoothClassifier( 6419): Bluetooth Device Name: S5-1
,D/GKI_LINUX( 4005): release_my_wake_lock(), g_wake_lock_fd:85, g_wake_unlock_fd:86, wake_lock_acquired:1
,D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 9421
D/BluetoothAdapterService(1109670600)( 4005): Get Bonded Devices being called
,E/Watchdog( 2420): !@Sync 21
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 310, Delta = 10
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = -10
,D/AmoledAdjustTimer( 2420): prevTemp = 282, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/PowerManagerService( 2420): [PWL] Off : 600s ago
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,I/GAV2    ( 5623): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5623): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2420): !@Sync 22
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 281, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 23
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 280, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 281, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 280, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 24
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 279, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 280, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2420): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 25
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 26
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4076): GC_CONCURRENT freed 2879K, 28% free 9728K/13504K, paused 10ms+3ms, total 69ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 27
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 279, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 765s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 279, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 28
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 29
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2420): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 855s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 31
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 278, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 32
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 278, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 33
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 950s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 34
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 4079K, 74% free 25314K/94072K, paused 22ms+19ms, total 240ms
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 35
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 36
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 277, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1050s ago
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 37
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 277, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 277, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 276, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2420): stay LED for fully charged
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 277, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 38
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2769): GC_CONCURRENT freed 7046K, 38% free 18941K/30388K, paused 18ms+8ms, total 106ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 39
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1155s ago
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 41
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 42
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,V/AlarmManager( 2420): waitForAlarm result :4
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/Sensors ( 2420): LightSensor enable = 0
D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,E/SPPClientService( 5536): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 43
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1265s ago
,E/Watchdog( 2420): !@Sync 44
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 276, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 275, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 276, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 45
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 46
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 47
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1380s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 48
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/dalvikvm( 2420): GC_CONCURRENT freed 3852K, 74% free 25313K/94072K, paused 19ms+15ms, total 231ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 49
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 50
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4076): GC_CONCURRENT freed 2048K, 28% free 9726K/13504K, paused 2ms+3ms, total 31ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 275, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/BatteryService( 2420): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 275, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 51
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1500s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 52
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:true, T:false, S:true, R:false
,E/SPPClientService( 5536): [b] __PingReply__
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 53
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 54
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 55
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 56
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 57
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 58
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 274, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 274, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 59
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/TimaService( 2420): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2420): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2420): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2420): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2420): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2420): !@Sync 60
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12491
,W/ProcessCpuTracker( 2420): Skipping unknown process pid 12502
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2420): Prepared write state in 54ms
,I/PowerManagerService( 2420): [PWL] Off : 1755s ago
,I/PowerManagerService( 2420): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2420): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2420): [PWL]       PARTIAL_WAKE_LOCK              'AlarmManager' (uid=1000, pid=2420, ws=WorkSource{1000}) (elapsedTime=89)
,I/ProcessStatsService( 2420): Pruning old procstats: /data/system/procstats/state-2016-01-07-17-22-00.bin
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 61
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 62
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2420): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2420): <AppSync3 Whitelist>
,V/AlarmManager( 2420): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2420): GC_CONCURRENT freed 3838K, 74% free 25329K/94072K, paused 16ms+16ms, total 217ms
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 63
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 64
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 6394:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1800s
,I/ActivityManager( 2420): Killing 6734:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1801s
,I/ActivityManager( 2420): Killing 6720:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1801s
,I/ActivityManager( 2420): Killing 6708:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1801s
,I/ActivityManager( 2420): Killing 6696:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1802s
I/ActivityManager( 2420): Killing 6683:com.samsung.helphub/1000 (adj 15): empty for 1802s
,I/ActivityManager( 2420): Killing 6670:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1802s
I/ActivityManager( 2420): Killing 6644:com.sec.android.service.cm/u0a82 (adj 15): empty for 1802s
,I/ActivityManager( 2420): Killing 6354:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1802s
,I/ActivityManager( 2420): Killing 5691:com.android.mms/u0a49 (adj 15): empty for 1802s
,I/ActivityManager( 2420): Killing 6618:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1803s
,I/ActivityManager( 2420): Killing 5993:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1803s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/CountryDetector( 2420): No listener is left
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,I/PowerManagerService( 2420): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 65
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 66
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,I/ActivityManager( 2420): Killing 6435:com.sec.knox.bridge/1000 (adj 15): empty for 1850s
,I/ActivityManager( 2420): Killing 4858:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1850s
,I/ActivityManager( 2420): Killing 6776:com.google.android.youtube/u0a175 (adj 15): empty for 1857s
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2420): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 272, prevStep = 4, currStep = 4
,D/BatteryService( 2420): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2420): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2420): mCoverManager.getCoverState() : true
,D/BatteryService( 2420): stay LED for fully charged
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4005): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4005): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2420): !@Sync 67
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 272, currTemp = 273, prevStep = 4, currStep = 4
,V/AlarmManager( 2420): waitForAlarm result :4
,V/NetworkStats( 2420): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2420): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,V/NetworkStats( 2420): performPollLocked() took 55ms
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
D/NtpTrustedTime( 2420): currentTimeMillis() cache hit
,I/SELinux (13000): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (13000):  
,I/SELinux (13000): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (13000):  
I/SELinux (13000):  
,I/SELinux (13000): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (13000): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(13000): >>>>> Normal User
,E/dalvikvm(13000): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
,E/SELinux (13000): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(13000): in addTimaSignatureService
,D/TimaKeyStoreProvider(13000): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(13000): Added TimaKesytore provider
,D/dalvikvm(13000): GC_CONCURRENT freed 2997K, 29% free 9572K/13468K, paused 3ms+2ms, total 26ms
,D/dalvikvm(13000): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/@ WidgetProvider(13000): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(13000): onUpdate called for widgetId : 0
,D/@ WidgetProvider(13000): Widget random data : 3
,D/@ WidgetProvider(13000): onUpdate called for widgetId : 5
,D/@ WidgetProvider(13000): Widget random data : 3
,E/dalvikvm(13000): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(13000): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13000): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13000): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13000): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13000): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13000): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(13000): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13000): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(13000): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(13000): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(13000): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(13000): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(13000): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
D/dalvikvm(13000): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(13000): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,I/SensorManagerA( 2420): getReportingMode :: sensor.mType = 5
,D/LightsService( 2420): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2420): LightSensor setDelay = 200000000
D/Sensors ( 2420): LightSensor setSensorDelay = 200000000
D/Sensors ( 2420): Light sensor flush: not enabled 0
D/Sensors ( 2420): LightSensor enable = 1
D/Sensors ( 2420): LightSensor enableSensor = 1
D/SensorManager( 2420): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2856): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ContextImpl( 6602): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 android.content.ContextWrapper.sendBroadcast:377 com.policydm.XDMBroadcastReceiver.sendRegisterIntent:471 com.policydm.XDMBroadcastReceiver.processEULAAgreement:460 com.policydm.XDMBroadcastReceiver.xdmExecResumeCase:373 
,I/System.out(13000): Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(13000): Thread-675(ApacheHTTPLog):isShipBuild true
,I/System.out(13000): Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/Sensors ( 2420): LightSensor enable = 0
,D/Sensors ( 2420): LightSensor enableSensor = 0
,D/SensorManager( 2420): unregisterListener ::   
D/LightsService( 2420): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2420): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,W/ActivityThread( 6602): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/System.out( 6602): Thread-596(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 6602): Thread-596(ApacheHTTPLog):isShipBuild true
,I/System.out( 6602): Thread-596(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/System.out(13000): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(13000): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(13000): Max ALLOWED memory (MB): 128
V/ImageManager(13000): Max SHOULD USE memory (MB): 128
,V/ImageManager(13000): Max Image Cache memory (MB): 32
,I/System.out( 6602): Thread-596 calls detatch()
,I/dalvikvm( 6602): Total arena pages for JIT: 11
,I/dalvikvm( 6602): Total arena pages for JIT: 12
I/dalvikvm( 6602): Total arena pages for JIT: 13
,I/dalvikvm( 6602): Total arena pages for JIT: 14
,D/skia    (13000): getTotalSize : Do not get file length
I/dalvikvm( 6602): Total arena pages for JIT: 15
I/dalvikvm( 6602): Total arena pages for JIT: 16
,I/dalvikvm( 6602): Total arena pages for JIT: 17
,D/@ WidgetProvider(13000): Building widget : 5
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,E/Watchdog( 2420): !@Sync 68
,V/AlarmManager( 2420): waitForAlarm result :8
,V/AlarmManager( 2420): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2420): SIOP:: AP = 300, Delta = 0
,D/AmoledAdjustTimer( 2420): prevTemp = 273, currTemp = 273, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1800000ms)
```
