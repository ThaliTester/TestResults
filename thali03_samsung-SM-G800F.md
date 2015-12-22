#### Test 543122982543be8_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
I/PowerManagerService( 2422): [PWL] Off : 225s ago
--------- beginning of /dev/log/main
D/AndroidRuntime( 7195): 
D/AndroidRuntime( 7195): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7195): CheckJNI is OFF
D/AndroidRuntime( 7195): setted country_code = Poland
D/AndroidRuntime( 7195): setted countryiso_code = PL
D/AndroidRuntime( 7195): setted sales_code = PLS
D/AndroidRuntime( 7195): readGMSProperty: start
D/AndroidRuntime( 7195): readGMSProperty: already setted!!
D/AndroidRuntime( 7195): readGMSProperty: end
D/AndroidRuntime( 7195): addProductProperty: start
D/dalvikvm( 7195): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7195): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7195): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7195): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7195): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7195): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7195): failed to load memtrack module: -2
D/dalvikvm( 7195): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7195): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2422): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=18 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7222): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7222):  
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7195): Shutting down VM
D/dalvikvm( 7195): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7222): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7222):  
I/SELinux ( 7222):  
I/SELinux ( 7222): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7222): >>>>> Normal User
E/dalvikvm( 7222): >>>>> com.test.thalitest [ userId:0 | appId:10576 ]
E/SELinux ( 7222): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7222): in addTimaSignatureService
D/TimaKeyStoreProvider( 7222): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7222): Added TimaKesytore provider
V/WindowManager( 2422): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4177): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4177): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2785): onTrimMemory. Level: 20
D/dalvikvm( 7222): GC_CONCURRENT freed 3006K, 30% free 9558K/13652K, paused 2ms+1ms, total 19ms
D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/WebViewChromium( 7222): Binding Chromium to the background looper Looper (main, tid 1) {42445330}
I/chromium( 7222): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7222): Initializing chromium process, renderers=0
W/chromium( 7222): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7222): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7222): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7222): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7222): Mali API Version : 401
,I/Mali    ( 7222): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7222): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7222): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7222): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7222): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7222): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7222): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:7222,o:f
,W/dalvikvm( 7222): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7222): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7222): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7222): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7222): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7222): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7222): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7222): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7222): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7222): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7222): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7222): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7222): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2422): semi p:7222,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1920): id=20 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7222): EGLImpl-HWUI Protected EGL context created
,D/OpenGLRenderer( 7222): Enabling debug mode 0
,W/AwContents( 7222): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7222): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2422): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2422): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7222): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7222): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7222): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424460b8
,D/dalvikvm( 7222): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424460b8
D/jxcore_app_log( 7222): JniHelper::setJavaVM(0x419dc220), pthread_self() = 2030906488
,D/JX-Cordova( 7222): jxcore cordova android initializing
,D/dalvikvm( 7222): GC_CONCURRENT freed 1287K, 18% free 11343K/13712K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 9ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 14ms
,D/dalvikvm( 7222): GC_CONCURRENT freed 1941K, 17% free 14895K/17932K, paused 2ms+2ms, total 42ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/CustomFrequencyManagerService( 2422): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2422  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7222): GC_FOR_ALLOC freed 5353K, 30% free 16179K/22836K, paused 64ms, total 64ms
,D/dalvikvm( 7222): GC_CONCURRENT freed 6701K, 31% free 17648K/25452K, paused 2ms+9ms, total 61ms
,D/dalvikvm( 7222): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/dalvikvm( 7222): GC_FOR_ALLOC freed 1467K, 32% free 17335K/25452K, paused 55ms, total 55ms
,I/dalvikvm-heap( 7222): Grow heap (frag case) to 21.524MB for 3713210-byte allocation
,D/dalvikvm( 7222): GC_FOR_ALLOC freed 2445K, 37% free 18516K/29080K, paused 53ms, total 53ms
,W/jxcore-log( 7222): Initializing JXcore engine
,W/jxcore-log( 7222): JXcore engine is ready
,W/jxcore-log( 7222): Starting JXcore engine
,W/jxcore-log( 7222): Platform android
W/jxcore-log( 7222): 
,W/jxcore-log( 7222): Process ARCH arm
W/jxcore-log( 7222): 
,I/jxcore-log( 7222): JXcore Cordova bridge is ready!
I/jxcore-log( 7222): 
,W/jxcore-log( 7222): JXcore engine is started
,I/chromium( 7222): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 10
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,I/jxcore-log( 7222): Toggling radios to true
I/jxcore-log( 7222): 
D/BluetoothAdapter( 7222): enable(): BT is already enabled..!
I/WifiManager( 7222): packageName : com.test.thalitest
I/WifiManager( 7222): setWifiEnabled : true
I/WifiService( 2422): setWifiEnabled: true pid=7222, uid=10576
W/ActivityManager( 2422): Permission Denial: getCurrentUser() from pid=7222, uid=10576 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): Failed getting userId using ActivityManagerNative
W/WifiService( 2422): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7222, uid=10576 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2422): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2422): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2422): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2422): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2422): 	at dalvik.system.NativeStart.run(Native Method)
I/WifiService( 2422): disconnect: pid=7222, uid=10576
I/jxcore-log( 7222): Radios toggled
I/jxcore-log( 7222): 
I/wpa_supplicant( 3964): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7222): Got Device Bluetooth address: 00:F4:6F:30:E0:6C
I/jxcore-log( 7222): 
I/wpa_supplicant( 3964): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/jxcore-log( 7222): Perf Test app loaded loaded
I/jxcore-log( 7222): 
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
D/Tethering( 2422): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3964): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
I/wpa_supplicant( 3964): First Scan Start
W/Settings( 2422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/wpa_supplicant( 3964): Scan requested (ret=0) - scan timeout 30 seconds
I/WifiStateMachine( 2422): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2422): InactiveState{ what=143375 }
I/jxcore-log( 7222): check test folder
I/jxcore-log( 7222): 
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
I/jxcore-log( 7222): found test : ./testFindPeers.js
I/jxcore-log( 7222): 
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1915): Clearing all IP addresses on wlan0
I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
I/wpa_supplicant( 3964): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3964): Skip scan - already scanning
D/ConnectivityService( 2422): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/WifiP2pService( 2422): InactiveState{ what=143375 }
D/ConnectivityService( 2422): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2422): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2422): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2422): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
I/SELinux ( 7270): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7270):  
D/ConnectivityService( 2422): Attempting to switch to mobile
D/ConnectivityService( 2422): Attempting to switch to BLUETOOTH_TETHER
D/STATUSBAR-IconMerger( 2583): checkOverflow(336), More:false, Req:false Child:3
D/CommandListener( 1915): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
E/WifiStateMachine( 2422): Error! unhandled message{ when=-49ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2422): Error! unhandled message{ when=-48ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/jxcore-log( 7222): found test : ./testSendData.js
I/jxcore-log( 7222): 
V/RouteController( 1915): RTNETLINK answers: No such file or directory
I/SELinux ( 7270): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7270):  
I/SELinux ( 7270):  
I/SELinux ( 7270): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7270): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7270): >>>>> Normal User
E/dalvikvm( 7270): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
E/SELinux ( 7270): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
W/NetworkManagementService( 2422): route cmd failed: 
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
V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
E/WifiStateMachine( 2422): Error! unhandled message{ when=-23ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
D/TimaKeyStoreProvider( 7270): in addTimaSignatureService
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
D/TimaKeyStoreProvider( 7270): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7270): Added TimaKesytore provider
D/NetUtils( 2422): android_net_utils_resetConnections in env=0x77f3cdf0 clazz=0x62900001 iface=wlan0 mask=0x3
D/ConnectivityService( 2422): resetConnections(wlan0, 3)
I/jxcore-log( 7222): found test : ./testSendData2.js
I/jxcore-log( 7222): 
D/dalvikvm( 7270): GC_CONCURRENT freed 2985K, 30% free 9583K/13652K, paused 4ms+2ms, total 27ms
D/dalvikvm( 7270): WAIT_FOR_CONCURRENT_GC blocked 17ms
V/NativeCrypto( 2860): Read error: ssl=0x79f95ca0: I/O error during system call, Connection timed out
V/NativeCrypto( 2860): SSL shutdown failed: ssl=0x79f95ca0: I/O error during system call, Broken pipe
E/SPPClientService( 5519): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
E/SPPClientService( 5519): [e] exceptionCaught(). NET_TIMEOUT
E/SPPClientService( 5519): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
E/SPPClientService( 5519): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
E/SPPClientService( 5519): [b] ResponseMap empty
D/ConnectivityService( 2422): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2422): updateIfacesLocked()
V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
I/System.out( 7270): Inside WakeupProvider
I/System.out( 7270): Inside onCreate() of WakeupTriggerProvide
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 24ms
I/chromium( 7222): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
I/VlingoApplication( 7270): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
D/VlingoApplication( 7270): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
D/VlingoApplication( 7270): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 2836): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2836): DMSUtil.isNetworkConnected - P2P: IDLE,
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2836): MountReceiver.onReceive - Set preference state off,
,D/DialogFlow( 7270): initQueue(),
I/ActivityManager( 2422): Killing 6141:com.sec.android.app.sns3/u0a37 (adj 15): empty #43
,V/NearbySettings( 2836): MountReceiver.mPrefHandler - 7002,
,D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,V/NearbySettings( 2836): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2836): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2836): MountReceiver.mPrefHandler - 7002
,D/dalvikvm( 2422): GC_CONCURRENT freed 3790K, 71% free 25104K/84020K, paused 9ms+22ms, total 288ms
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
,D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/ApplicationPolicy( 2422): updateDataUsageMap
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): noConnectivity : true
,I/DBG_DM  ( 4734): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/SELinux ( 7299): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7299):  
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,I/wpa_supplicant( 3964): nl80211: Received scan results (4 BSSes)
,I/wpa_supplicant( 3964): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3964): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/SELinux ( 7299): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7299):  
I/SELinux ( 7299):  
,I/SELinux ( 7299): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7299): >>>>> Normal User
,E/dalvikvm( 7299): >>>>> com.sec.android.cloudagent [ userId:0 | appId:10002 ]
,E/SELinux ( 7299): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7299): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7299): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7299): Added TimaKesytore provider
W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3964): Associated with C0.AA.48
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3964): freq(2412) increment count 2
,I/wpa_supplicant( 3964): meet head of list.
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3964): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3964): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3964): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2422): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2422): interfaceStatusChanged wlan0, true
,D/WifiNative( 2422): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/dalvikvm( 7299): GC_CONCURRENT freed 3007K, 30% free 9567K/13656K, paused 5ms+2ms, total 36ms
,D/dalvikvm( 7299): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/ActivityManager( 2422): Killing 6211:com.sec.android.app.music:service/u0a152 (adj 15): empty #43
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,I/SELinux ( 7313): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7313):  
,I/SELinux ( 7313): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7313):  
I/SELinux ( 7313):  
,I/SELinux ( 7313): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7313): >>>>> Normal User
,E/dalvikvm( 7313): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7313): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7313): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7313): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7313): Added TimaKesytore provider
,I/dhcpcd  ( 7323): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7323): bssid match
,D/dalvikvm( 7313): GC_CONCURRENT freed 2993K, 30% free 9576K/13656K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7313): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/ActivityManager( 2422): Killing 6265:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,I/SELinux ( 7332): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7332):  
,I/SELinux ( 7332): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7332):  
I/SELinux ( 7332):  
I/SELinux ( 7332): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7332): >>>>> Normal User
E/dalvikvm( 7332): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7332): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7332): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7332): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7332): Added TimaKesytore provider
,D/dalvikvm( 7332): GC_CONCURRENT freed 2997K, 30% free 9565K/13648K, paused 3ms+2ms, total 27ms
,D/dalvikvm( 7332): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/KLMS-2.3.201 : ( 7332): KLMSValidator() : checkQATesting()
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
,I/KLMS-2.3.201 : ( 7332): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450745690871
,I/KLMS-2.3.201 : ( 7332): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/ActivityManager( 2422): Killing 6282:com.sec.android.app.voicenote/1000 (adj 15): empty #43
,I/SELinux ( 7344): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7344):  
,I/SELinux ( 7344): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7344):  
I/SELinux ( 7344):  
,I/SELinux ( 7344): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7344): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7344): >>>>> Normal User
,E/dalvikvm( 7344): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7344): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7344): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7344): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7344): Added TimaKesytore provider
,D/dalvikvm( 7344): GC_CONCURRENT freed 3011K, 30% free 9555K/13648K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 7344): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/SO_AGENT( 7344): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7344): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5782): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5782): [BDLM] already registered in spp
I/SA      ( 5782): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5782): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5782): [OR] == isSIMCardReady false ==
I/SA      ( 5782): [SCU] == networkStateCheck == false
,I/SA      ( 5782): [OR] onReceive END
I/ActivityManager( 2422): Killing 5564:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
,I/SELinux ( 7356): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7356):  
,D/dalvikvm( 1922): GC_EXPLICIT freed 43K, 11% free 9502K/10628K, paused 3ms+5ms, total 47ms
,I/SELinux ( 7356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7356):  
I/SELinux ( 7356):  
,I/SELinux ( 7356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7356): >>>>> Normal User
,E/dalvikvm( 7356): >>>>> com.samsung.android.scloud.backup [ userId:0 | appId:10062 ]
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 3ms+4ms, total 35ms
,D/TimaKeyStoreProvider( 7356): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7356): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7356): Added TimaKesytore provider
,D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 3ms+4ms, total 36ms
,D/dalvikvm( 7356): GC_CONCURRENT freed 2998K, 30% free 9570K/13652K, paused 4ms+2ms, total 29ms
,D/dalvikvm( 7356): WAIT_FOR_CONCURRENT_GC blocked 22ms
,D/PackageManager( 2422): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/sCloudBackupApp( 7356): sCloudBackupApp Version Info : 3.7.3.KK_APP
,I/SCloudBackupReceiver( 7356): Other Intent
I/ActivityManager( 2422): Killing 6247:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7369): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7369):  
,I/SELinux ( 7369): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7369):  
I/SELinux ( 7369):  
,I/SELinux ( 7369): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7369): >>>>> Normal User
,E/dalvikvm( 7369): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7369): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7369): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7369): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7369): Added TimaKesytore provider
,D/dalvikvm( 7369): GC_CONCURRENT freed 2990K, 30% free 9570K/13648K, paused 2ms+3ms, total 29ms
,D/dalvikvm( 7369): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7369): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7369): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7369): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7369): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5313): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/ActivityManager( 2422): Killing 6309:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43,
,D/Headlines( 5849): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5849): getCountryCode(): countryCode = PL,
,D/Headlines( 5849): Breath.onCreate
,D/Headlines( 5849): Breath timer started. interval : 30000
,I/SELinux ( 7395): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7395):  
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
,V/AlarmManager( 2422): waitForAlarm result :8
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5849): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5849): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5849): requestUpdateNewsWelcomeCard !!! no welcome card
,I/SELinux ( 7395): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7395):  
I/SELinux ( 7395):  
,I/SELinux ( 7395): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7395): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7395): >>>>> Normal User
,E/dalvikvm( 7395): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7395): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7395): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7395): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7395): Added TimaKesytore provider
,D/dalvikvm( 7395): GC_CONCURRENT freed 2994K, 30% free 9572K/13648K, paused 3ms+2ms, total 33ms
,D/dalvikvm( 7395): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/WifiP2pService( 2422): InactiveState{ what=143375 }
,D/WifiP2pService( 2422): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2422): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiStateMachine( 2422): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine( 2422): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2422): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2422): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2422): evaluateTrafficStatsPolling
D/ConnectivityService( 2422): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2422): net.tcp.usercfg.wifi not found in system properties. Using defaults
,V/WebViewChromium( 7395): Binding Chromium to the background looper Looper (main, tid 1) {424422c0}
E/ConnectivityService( 2422): net.tcp.delack.wifi not found in system properties. Using defaults
,I/chromium( 7395): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
D/STATUSBAR-NetworkController( 2583): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2583): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2583): refreshSignalCluster: data=-1 bt=false
I/BrowserProcessMain( 7395): Initializing chromium process, renderers=0
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,W/chromium( 7395): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1,
,D/libEGL  ( 7395): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7395): loaded /system/lib/egl/libGLESv1_CM_mali.so
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/libEGL  ( 7395): loaded /system/lib/egl/libGLESv2_mali.so
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,I/Mali    ( 7395): Mali API Version : 401
,I/Mali    ( 7395): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2422): updateIfacesLocked()
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
V/NetworkStats( 2422): performPollLocked() took 22ms
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
W/GAV2    ( 7395): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ContextImpl( 7395): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7395): Starting up...
,I/iu.Environment( 5913): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5115): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5115): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5115): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424520b0
,I/SELinux ( 7455): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7455):  
,I/SELinux ( 7455): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7455):  
I/SELinux ( 7455):  
,I/SELinux ( 7455): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7455): >>>>> Normal User
,E/dalvikvm( 7455): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7455): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7455): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7455): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7455): Added TimaKesytore provider
,D/Tethering( 2422): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2422): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2422): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/STATUSBAR-NetworkController( 2583): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2583): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2583): updateDataNetType()
D/STATUSBAR-NetworkController( 2583): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4734): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/dalvikvm( 7455): GC_CONCURRENT freed 2980K, 30% free 9585K/13652K, paused 3ms+3ms, total 46ms
D/dalvikvm( 7455): WAIT_FOR_CONCURRENT_GC blocked 36ms
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection...
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/SELinux ( 7474): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7474):  
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,W/ActivityManager( 2422): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,I/ActivityManager( 2422): Killing 5959:com.android.calendar/u0a144 (adj 15): empty #43
,I/SELinux ( 7474): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7474):  
I/SELinux ( 7474):  
,I/SELinux ( 7474): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7474): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7474): >>>>> Normal User
,E/dalvikvm( 7474): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,I/SELinux ( 7478): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7478):  
,E/SELinux ( 7474): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7474): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7474): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7474): Added TimaKesytore provider
,I/ActivityManager( 2422): Killing 6298:com.android.providers.calendar/u0a45 (adj 15): empty #43
,I/SELinux ( 7478): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7478):  
I/SELinux ( 7478):  
,I/SELinux ( 7478): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7478): >>>>> Normal User
,E/dalvikvm( 7478): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7478): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7478): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7478): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7478): Added TimaKesytore provider
,D/dalvikvm( 7474): GC_CONCURRENT freed 3002K, 30% free 9565K/13652K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7474): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/BadgeProvider( 7474): onCreate
,D/BadgeProvider( 7474): DatabaseHelper
,D/BadgeProvider( 7474): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/dalvikvm( 7478): GC_CONCURRENT freed 2999K, 30% free 9565K/13652K, paused 5ms+2ms, total 33ms
D/BadgeProvider( 7474): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/dalvikvm( 7478): WAIT_FOR_CONCURRENT_GC blocked 28ms
D/BadgeProvider( 7474): sendNotify, [notify] : null
D/BadgeProvider( 7474): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7474): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7474): update, [UpdateCount] : 1
,D/Launcher.Model( 2785): reloadBadges entered.
,D/hcjo    ( 5934): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5934): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5934): exit::IDLE
,D/InitializeManagerStateMachine( 5934): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5934): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5934): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5934): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5934): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5934): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5934): entry::SUCCESS
,D/hcjo    ( 5934): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5934): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5934): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5934): exit::SUCCESS
,D/InitializeManagerStateMachine( 5934): entry::IDLE
,E/SPPClientService( 5519): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5519): [SystemStateMoniter] Current Time : 306694
,E/SPPClientService( 5519): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5519): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2836): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - P2P: IDLE
,I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2836): MountReceiver.onReceive - Keep current state
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
E/SPPClientService( 5519): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5519): [a] [ConnectionManager] Connection is already disconnected.
D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5849): Breath 1755 latestRequest time : 1450745691910 current time : 1450745693665
,D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2836): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5519): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/dalvikvm( 7222): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7222): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7222): VFY: replacing opcode 0x6e at 0x0002
D/AndroidRuntime( 7222): Shutting down VM
,W/dalvikvm( 7222): threadid=1: thread exiting with uncaught exception (group=0x419efc08)
,E/SPPClientService( 5519): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2836): DMSUtil.isNetworkConnected - flag-null, state-null
,E/AndroidRuntime( 7222): FATAL EXCEPTION: main
E/AndroidRuntime( 7222): Process: com.test.thalitest, PID: 7222
E/AndroidRuntime( 7222): java.lang.NoSuchMethodError: android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported
E/AndroidRuntime( 7222): 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported(BluetoothManager.java:121)
E/AndroidRuntime( 7222): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:144)
E/AndroidRuntime( 7222): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.setDiscoveryMode(DiscoveryManager.java:188)
E/AndroidRuntime( 7222): 	at org.thaliproject.p2p.btconnectorlib.DiscoveryManager.<init>(DiscoveryManager.java:106)
E/AndroidRuntime( 7222): 	at io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported(ConnectionHelper.java:154)
E/AndroidRuntime( 7222): 	at io.jxcore.node.JXcoreExtension$3.Receiver(JXcoreExtension.java:90)
E/AndroidRuntime( 7222): 	at io.jxcore.node.jxcore.javaCall(jxcore.java:228)
E/AndroidRuntime( 7222): 	at io.jxcore.node.jxcore.loopOnce(Native Method)
E/AndroidRuntime( 7222): 	at io.jxcore.node.jxcore$4.run(jxcore.java:196)
E/AndroidRuntime( 7222): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 7222): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 7222): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7222): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7222): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7222): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7222): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7222): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7222): 	at dalvik.system.NativeStart.main(Native Method)
I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2836): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2836): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2836): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 2422):   Force finishing activity com.test.thalitest/.MainActivity
,D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
I/ActivityManager( 2422): Killing 6128:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/CrashAnrDetector( 2422): processName: com.test.thalitest
,D/CrashAnrDetector( 2422): broadcastEvent : com.test.thalitest data_app_crash
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1515 com.android.server.analytics.data.collection.application.CrashAnrDetector.broadcastEvent:296 com.android.server.analytics.data.collection.application.CrashAnrDetector.processDropBoxEntry:254 com.android.server.analytics.data.collection.application.CrashAnrDetector.access$100:60 com.android.server.analytics.data.collection.application.CrashAnrDetector$1.onReceive:102 
,I/Process ( 7222): Sending signal. PID: 7222 SIG: 9
,E/SPPClientService( 5519): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=4, Uoast
,I/ActivityManager( 2422): Process com.test.thalitest (pid 7222) (adj 9) has died.
W/InputDispatcher( 2422): channel ~ Consumer closed input channel or an error occurred.  events=0x9
E/InputDispatcher( 2422): channel ~ Channel is unrecoverably broken and will be disposed!
,D/PowerManagerService( 2422): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422
,W/InputDispatcher( 2422): Attempted to unregister already unregistered input channel
I/SurfaceFlinger( 1920): id=20 Removed NainActivit (8/11)
,I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/11)
,I/WindowState( 2422): WIN DEATH: Window{432df788 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/NearbySettings( 2836): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
I/NearbySettings( 2836): MountReceiver.onReceive - Keep current state
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (6/10)
I/SurfaceFlinger( 1920): id=20 Removed NainActivit (-2/10)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (5/9)
I/SurfaceFlinger( 1920): id=18 Removed EimLayer (-2/9)
,E/SPPClientService( 5519): [a] [ConnectionManager] Connection is already disconnected.
,V/WindowManager( 2422): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
E/SPPClientService( 5519): [g] getNetMCC return empty string
,I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/Launcher( 2785): onRestart, Launcher: 1111978608
D/Launcher( 2785): onStart, Launcher: 1111978608
,D/Launcher.HomeView( 2785): onStart
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4372, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/libgps  ( 2422): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection...
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,I/SurfaceFlinger( 1920): id=22 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2422): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2422): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2422): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2422): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2422): setHoveringSpenCustomIcon IconType is same.1
,D/PhoneStatusBar( 2583): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2422): tr p:2785,o:f
,D/StatusBarManagerService( 2422): semi p:2785,o:f
D/PhoneStatusBar( 2583): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2422): Got RemoteException sending setActive(false) notification to pid 7222 uid 10576
,I/KLMS-2.3.201 : ( 7332): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7332): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1450745694282
,I/KLMS-2.3.201 : ( 7332): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7344): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/LocationTagReadyService( 3254): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7344): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3254): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3254): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3254): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7515): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7515):  
,I/GallerySearchProvider( 3382): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7515): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7515):  
I/SELinux ( 7515):  
,I/SELinux ( 7515): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7515): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7515): >>>>> Normal User
,E/dalvikvm( 7515): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,I/SELinux ( 7520): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7520):  
,E/SELinux ( 7515): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 2726): GC_EXPLICIT freed 336K, 27% free 10037K/13640K, paused 11ms+9ms, total 91ms
,D/TimaKeyStoreProvider( 7515): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7515): Cannot add TimaSignature Service, License check Failed
I/SELinux ( 7520): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7520):  
I/SELinux ( 7520):  
,I/SELinux ( 7520): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7520): >>>>> Normal User
,E/dalvikvm( 7520): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,D/ActivityThread( 7515): Added TimaKesytore provider
,E/SELinux ( 7520): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7520): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7520): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7520): Added TimaKesytore provider
,I/SA      ( 5782): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5782): [BDLM] already registered in spp
I/SA      ( 5782): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5782): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5782): [OR] == isSIMCardReady false ==
,I/SA      ( 5782): [SCU] == networkStateCheck == true
I/SA      ( 5782): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5782): isChinaCountryCode : false
,I/SA      ( 5782): [OR] == networkStateCheck true ==
,I/SA      ( 5782): [OR] GetMyCountryZoneTask
,I/System.out( 7313): Thread-630(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/SA      ( 5782): [OR] onReceive END
,I/SA      ( 5782): [SRS] prepareGetMyCountryZone
,D/dalvikvm( 7515): GC_CONCURRENT freed 2992K, 30% free 9577K/13652K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 7515): WAIT_FOR_CONCURRENT_GC blocked 25ms
,I/SA      ( 5782): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5782): [SSP] query invoked
I/System.out( 7313): Thread-630(ApacheHTTPLog):isShipBuild true
,I/System.out( 7313): Thread-630(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/PhoneNumberLocatorBootCompletedReceiver( 2755): onReceive
D/PhoneNumberLocatorBootCompletedReceiver( 2755): Phone number locator feature is dsiabled
D/dalvikvm( 7520): GC_CONCURRENT freed 2994K, 30% free 9566K/13648K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7520): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/SA      ( 5782): [TPMU] GetMccFromDB : null
,I/SA      ( 5782): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5782): [TPM] isNoProxy(default) : true
,I/SCloudBackupReceiver( 7356): Other Intent
,I/SA      ( 5782): [RC New] Execute method=[GET] start
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7369): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,V/KVNProvider( 7520): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7520): getFindoCursor query string : 
,D/Headlines( 5849): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5849): getCountryCode(): countryCode = PL
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5849): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5849): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5849): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5849): requestUpdateNewsWelcomeCard !!! no welcome card
,V/KVNProvider( 7520): getTagSearchCursor() tagSearchCursor count : 0
,I/iu.Environment( 5913): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,D/QuickConnect[1.1][2] ( 5115): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5115): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5115): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@424520b0
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/RCPManagerService( 2422): exchangeData() failure , invalid userId
,D/hcjo    ( 5934): AutoUpdateManager:IDLE:execute
,I/System.out( 7313): AsyncTask #1 calls detatch()
D/InitializeManagerStateMachine( 5934): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5934): exit::IDLE
,D/InitializeManagerStateMachine( 5934): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5934): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5934): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5934): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5934): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5934): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5934): entry::SUCCESS
,D/hcjo    ( 5934): AutoUpdateManager:INITCHECK:onInitializeSuccess
D/hcjo    ( 5934): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5934): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5934): exit::SUCCESS
,D/InitializeManagerStateMachine( 5934): entry::IDLE
,E/SPPClientService( 5519): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5519): [SystemStateMoniter] Current Time : 307988
,W/System.err( 7313): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7313): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7313): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7313): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
,W/System.err( 7313): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7313): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,E/SPPClientService( 5519): [SystemStateMoniter] No Connect : false
W/System.err( 7313): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
,W/System.err( 7313): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7313): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7313): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7313): Caused by: java.lang.NullPointerException
,W/System.err( 7313): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
,W/System.err( 7313): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
,W/System.err( 7313): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7313): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7313): 	... 8 more
,I/ActivityManager( 2422): Killing 6164:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 5519): GC_CONCURRENT freed 2005K, 24% free 10444K/13644K, paused 11ms+5ms, total 60ms
,D/libgps  ( 2422): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2422): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2422): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SA      ( 5782): [RC New] [v2liruge] api execute + 863
,I/SA      ( 5782): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5782): AsyncTask #2 calls detatch()
,I/SA      ( 5782): [TPMU] getNetworkMcc : 
,I/SA      ( 5782): [SCU] saveMccToPreferece Start
,I/SA      ( 5782): [SCU] RegionMCC : 260
,I/SA      ( 5782): [SSP] query invoked
,I/SA      ( 5782): [TPMU] GetMccFromDB : null
,I/SA      ( 5782): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5782): [SCU] saveMccToPreferece End
I/SA      ( 5782): [RC New] executeRequest [v2liruge] end. 896
,I/SA      ( 5782): [RC New] Execute end
,I/SA      ( 5782): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5782): [OR] GetMyCountryZoneTask Success
,E/WifiStateMachine( 2422): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,W/WifiP2pStateTracker( 2422): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2422): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2422):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2422): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2422): updateSourceRoutes : no source routing conditions
,E/SPPClientService( 5519): [b] __InitReply__
,I/ActivityManager( 2422): Killing 6494:com.android.defcontainer/u0a6 (adj 15): empty #43,
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (8/9),
,I/SurfaceFlinger( 1920): id=21 Removed Uoast (-2/9),
,D/PowerManagerService( 2422): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2422) eventTime = 310482,
,D/PowerManagerService( 2422): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2422 (0x0),
,D/PowerManagerService( 2422): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2422, ws=WorkSource{1000}) (elapsedTime=3491),
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 296, prevStep = 4, currStep = 4,
,I/GAV2    ( 7395): Thread[GAThread,5,main]: No campaign data found.,
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6552): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6552): [hasSamungAccount] - No Samsung Account,
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. ,
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1,
,I/TLC_TIMA_PKM_initialize( 2422): initializing...,
I/TLC_TIMA_PKM_initialize( 2422): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 2422): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2422): root = 0, root_len = 1
,I/TZ: mc_tlc_communication( 2422): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2422): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2422): device_id = 0x0,
I/TZ: mc_tlc_communication( 2422): tlc_open() was called
,I/TZ: mc_tlc_communication( 2422): Opening MobiCore device,
,I/TZ: mc_tlc_communication( 2422): Allocating WSM for TCI,
,I/TZ: mc_tlc_communication( 2422): Opening the session,
,I/TZ: mc_tlc_communication( 2422): tlc_open() succeeded,
,I/TLC_TIMA_PKM_initialize( 2422): Trustlet response is completed
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6552): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6552): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6552): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6552): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6552): [ensureRegistration] - No Samsung account
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/CaptivePortalTracker( 2422): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler },
D/ConnectivityService( 2422): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/CaptivePortalTracker( 2422): Checking http://216.58.209.46/generate_204,
,D/CaptivePortalTracker( 2422): Don't send network conditions - lacking user consent.,
D/CaptivePortalTracker( 2422): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2422): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2422): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2422): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 5934): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5934): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5934): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5934): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5934): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5934): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5934): entry::IDLE
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4371, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PreloadUpdateManagerStateMachine( 5934): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5934): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5934): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5934): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5934): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5934): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5934): entry::IDLE
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3,
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;,
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 10
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{46a8f5c8 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService},
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/ActivityManager( 2422): Waited long enough for: ServiceRecord{46971d68 u0 com.sec.spp.push/.PushClientService},
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/dalvikvm( 2422): GC_EXPLICIT freed 2650K, 71% free 25085K/84020K, paused 12ms+22ms, total 257ms,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/BatteryService( 2422): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 275s ago,
,E/Watchdog( 2422): !@Sync 11,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4,
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7750): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7750):  
,I/SELinux ( 7750): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7750):  
I/SELinux ( 7750):  
I/SELinux ( 7750): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7750): >>>>> Normal User
,E/dalvikvm( 7750): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7750): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7750): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7750): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7750): Added TimaKesytore provider,
,D/dalvikvm( 7750): GC_CONCURRENT freed 2999K, 30% free 9568K/13656K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 7750): WAIT_FOR_CONCURRENT_GC blocked 23ms
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5849): Breath 45539 latestRequest time : 1450745694746 current time : 1450745740285
,I/ActivityManager( 2422): Killing 6413:com.google.android.partnersetup/u0a14 (adj 15): empty #43,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 57191 latestRequest time : 1450745694746 current time : 1450745751937,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0
D/AmoledAdjustTimer( 2422): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2422): !@Sync 12,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2422): stay LED for fully charged,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 87184 latestRequest time : 1450745694746 current time : 1450745781930,
,I/PowerManagerService( 2422): [PWL] Off : 330s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2422): !@Sync 13,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5849): Breath 117189 latestRequest time : 1450745694746 current time : 1450745811935,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2422): !@Sync 14,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4,
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,D/Headlines( 5849): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5849): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5849): Breath 147190 latestRequest time : 1450745694746 current time : 1450745841936
,D/Headlines( 5849): stop ,
,D/Headlines( 5849): Breath.onDestroy : ,
I/ActivityManager( 2422): Killing 6526:com.samsung.groupcast/u0a15 (adj 15): empty #43
,I/PowerManagerService( 2422): [PWL] Off : 390s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2422): !@Sync 15,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = -10,
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2422): !@Sync 16,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2422): [PWL] Off : 455s ago,
,E/Watchdog( 2422): !@Sync 17,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8,
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,E/Watchdog( 2422): !@Sync 18,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,E/Watchdog( 2422): !@Sync 19,
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2422): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 3998): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 525s ago,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0,
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,W/ContextImpl( 2422): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 2422): !@Sync 21
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 289, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 600s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,I/GAV2    ( 5606): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5606): Thread[disconnect check,5,main]: Disconnected from service
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2583): GC_CONCURRENT freed 15765K, 34% free 33819K/50664K, paused 23ms+9ms, total 148ms
,E/Watchdog( 2422): !@Sync 22
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 23
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 288, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2422): GC_CONCURRENT freed 3893K, 71% free 25084K/84020K, paused 11ms+16ms, total 208ms
,D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 196ms
,E/Watchdog( 2422): !@Sync 24
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 680s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 25
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4078): GC_CONCURRENT freed 2880K, 30% free 9690K/13688K, paused 23ms+3ms, total 72ms
,D/dalvikvm( 4078): WAIT_FOR_CONCURRENT_GC blocked 51ms
,E/Watchdog( 2422): !@Sync 26
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,E/SPPClientService( 5519): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/Sensors ( 2422): LightSensor enable = 0
D/Sensors ( 2422): LightSensor enableSensor = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 27
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 765s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 28
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 29
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 855s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 31
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 32
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 33
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 950s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2422): !@Sync 34
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 35
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 36
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5519): [b] __PingReply__
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 37
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 38
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3924K, 71% free 24984K/84020K, paused 21ms+18ms, total 240ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 39
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 40
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2422): [PWL] Off : 1155s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 285, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 41
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/BatteryService( 2422): stay LED for fully charged
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 285, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 42
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 43
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,V/AlarmManager( 2422): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2422): [PWL] Off : 1265s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 44
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 45
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 46
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,D/Sensors ( 2422): LightSensor enable = 0
,D/Sensors ( 2422): LightSensor enableSensor = 0
,D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 47
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 284, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1380s ago
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4078): GC_CONCURRENT freed 1895K, 29% free 9723K/13684K, paused 3ms+2ms, total 39ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 284, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 48
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 49
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 50
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 51
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1500s ago
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 52
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 53
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/dalvikvm( 2422): GC_CONCURRENT freed 3771K, 71% free 24988K/84020K, paused 24ms+17ms, total 248ms
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 54
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 55
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/PowerManagerService( 2422): [PWL] Off : 1625s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 56
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 283, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,E/SPPClientService( 5519): [[PushClientService]] F:false, D:false, E:false, T:false, S:true, R:false
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 283, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 57
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 58
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 59
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/ProcessStatsService( 2422): Prepared write state in 85ms
,W/ProcessCpuTracker( 2422): Skipping unknown process pid 11025
,I/ProcessStatsService( 2422): Pruning old procstats: /data/system/procstats/state-2015-12-21-08-11-00.bin
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2422): !@Sync 60
,I/PowerManagerService( 2422): [PWL] Off : 1755s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 61
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 62
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/UiModeManager( 2422): mCoverManager.getCoverState() : true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 63
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): stay LED for fully charged
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2422): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2422): <AppSync3 Whitelist>
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
V/AlarmManager( 2422): (AppSync) ### 0 added ###
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2422): stay LED for fully charged
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 64
,D/BatteryService( 2422): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2422): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2422): mCoverManager.getCoverState() : true
D/BatteryService( 2422): stay LED for fully charged
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2583): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2583):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 3998): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3998): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2583): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 1890s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 65
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,I/ActivityManager( 2422): Killing 6407:com.sec.knox.bridge/1000 (adj 15): empty for 1839s
,I/ActivityManager( 2422): Killing 4839:com.sec.android.app.FileShareServer/u0a73 (adj 15): empty for 1839s
,I/ActivityManager( 2422): Killing 6393:com.google.android.googlequicksearchbox:search/u0a59 (adj 15): empty for 1839s
,I/ActivityManager( 2422): Killing 6368:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 15): empty for 1849s
,I/ActivityManager( 2422): Killing 6711:com.n7mobile.promenadaplusa/u0a183 (adj 15): empty for 1850s
,I/ActivityManager( 2422): Killing 6697:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty for 1850s
,I/ActivityManager( 2422): Killing 6685:com.samsung.android.provider.shootingmodeprovider/u0a164 (adj 15): empty for 1850s
I/ActivityManager( 2422): Killing 6673:com.sec.kidsplat.installer/u0a160 (adj 15): empty for 1850s
,I/ActivityManager( 2422): Killing 6660:com.samsung.helphub/1000 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 6647:com.samsung.android.magazine.service/u0a110 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 6634:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 6621:com.sec.android.service.cm/u0a82 (adj 15): empty for 1851s
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,I/ActivityManager( 2422): Killing 6327:com.samsung.android.app.assistantmenu/1000 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 5675:com.android.mms/u0a49 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 6595:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty for 1851s
,I/ActivityManager( 2422): Killing 5973:com.sec.android.app.shealth/u0a36 (adj 15): empty for 1852s
,I/ActivityManager( 2422): Killing 6565:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty for 1852s
,I/ActivityManager( 2422): Killing 6539:com.android.musicfx/u0a24 (adj 15): empty for 1852s
,D/CountryDetector( 2422): No listener is left
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 66
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :4
,V/NetworkStats( 2422): performPollLocked(flags=0x3)
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,V/AlarmManager( 2422): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,V/NetworkStats( 2422): performPollLocked() took 45ms
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
D/NtpTrustedTime( 2422): currentTimeMillis() cache hit
,I/SELinux (11550): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11550):  
,I/SELinux (11550): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11550):  
I/SELinux (11550):  
,I/SELinux (11550): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux (11550): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm(11550): >>>>> Normal User
,E/dalvikvm(11550): >>>>> com.n7mobile.muzodajnia:main [ userId:0 | appId:10184 ]
E/SELinux (11550): [DEBUG] seapp_context_lookup: seinfoCategory = default
,D/TimaKeyStoreProvider(11550): in addTimaSignatureService
,D/TimaKeyStoreProvider(11550): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread(11550): Added TimaKesytore provider
,D/dalvikvm(11550): GC_CONCURRENT freed 2996K, 30% free 9576K/13656K, paused 3ms+2ms, total 29ms
,D/dalvikvm(11550): WAIT_FOR_CONCURRENT_GC blocked 25ms
,D/@ WidgetProvider(11550): onReceive = android.appwidget.action.APPWIDGET_UPDATE
,D/@ WidgetProvider(11550): onUpdate called for widgetId : 0
,D/@ WidgetProvider(11550): Widget random data : 2
,D/@ WidgetProvider(11550): onUpdate called for widgetId : 5
,D/@ WidgetProvider(11550): Widget random data : 1
,E/dalvikvm(11550): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJson
W/dalvikvm(11550): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11550): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11550): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11550): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11550): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11550): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPOST
W/dalvikvm(11550): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
D/dalvikvm(11550): VFY: replacing opcode 0x22 at 0x0038
E/dalvikvm(11550): Could not find class 'com.fasterxml.jackson.databind.ObjectMapper', referenced from method com.n7mobile.common.Networking.downloadAndParseJsonWithPUT
W/dalvikvm(11550): VFY: unable to resolve new-instance 944 (Lcom/fasterxml/jackson/databind/ObjectMapper;) in Lcom/n7mobile/common/Networking;
,D/dalvikvm(11550): VFY: replacing opcode 0x22 at 0x0038
,D/dalvikvm(11550): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJson
D/dalvikvm(11550): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11550): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPOST
,D/dalvikvm(11550): DexOpt: unable to opt direct call 0x2055 at 0x3a in Lcom/n7mobile/common/Networking;.downloadAndParseJsonWithPUT
,D/LightsService( 2422): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
I/SensorManagerA( 2422): getReportingMode :: sensor.mType = 5
D/Sensors ( 2422): LightSensor setDelay = 200000000
D/Sensors ( 2422): LightSensor setSensorDelay = 200000000
D/Sensors ( 2422): Light sensor flush: not enabled 0
D/Sensors ( 2422): LightSensor enable = 1
D/Sensors ( 2422): LightSensor enableSensor = 1
D/SensorManager( 2422): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,I/EventLogService( 3444): Aggregate from 1450745451446 (log), 1450745451446 (data)
,D/dalvikvm( 2422): GC_CONCURRENT freed 3866K, 71% free 24959K/84020K, paused 15ms+18ms, total 235ms
,V/GLSActivity( 2860): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 2860): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(11550): Thread-666(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(11550): Thread-666(ApacheHTTPLog):isShipBuild true
,I/System.out(11550): Thread-666(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/Sensors ( 2422): LightSensor enable = 0
D/Sensors ( 2422): LightSensor enableSensor = 0
,W/dalvikvm( 2860): VFY: unable to find class referenced in signature (Landroid/net/Network;)
E/dalvikvm( 2860): Could not find class 'android.net.Network', referenced from method com.google.android.gms.http.l.a
W/dalvikvm( 2860): VFY: unable to resolve check-cast 229 (Landroid/net/Network;) in Lcom/google/android/gms/http/l;
D/dalvikvm( 2860): VFY: replacing opcode 0x1f at 0x0011
,D/SensorManager( 2422): unregisterListener ::   
D/LightsService( 2422): [SvcLED]  onSensorChanged::light value = 0
,D/LightsService( 2422): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
I/dalvikvm( 2860): Could not find method android.os.PowerManager.isInteractive, referenced from method com.google.android.gms.common.util.y.a
W/dalvikvm( 2860): VFY: unable to resolve virtual method 1378: Landroid/os/PowerManager;.isInteractive ()Z
D/dalvikvm( 2860): VFY: replacing opcode 0x6e at 0x003d
,I/System.out( 2860): Thread-56(HTTPLog):isShipBuild true
,I/System.out( 2860): Thread-56(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 2860): GC_CONCURRENT freed 1822K, 22% free 10854K/13836K, paused 4ms+5ms, total 49ms
,I/System.out(11550): AsyncNetworking-1-thread-1 calls detatch()
,I/System.out(11550): AsyncNetworking-1-thread-1 calls detatch()
,V/ImageManager(11550): Max ALLOWED memory (MB): 128
V/ImageManager(11550): Max SHOULD USE memory (MB): 128
,V/ImageManager(11550): Max Image Cache memory (MB): 32
,I/System.out(11550): AsyncNetworking-1-thread-1 calls detatch()
,D/skia    (11550): getTotalSize : Do not get file length
,D/@ WidgetProvider(11550): Building widget : 5
,D/dalvikvm( 2785): GC_FOR_ALLOC freed 8779K, 40% free 18349K/30092K, paused 76ms, total 76ms
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 67
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,V/AlarmManager( 2422): waitForAlarm result :8
,V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 68
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,E/Watchdog( 2422): !@Sync 69
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,I/PowerManagerService( 2422): [PWL] Off : 2030s ago
,D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
,D/TimaService( 2422): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2422): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2422): TimaServiceHandler.handleMessage what =1
,TIME-OUT KILL (timeout was 1800000ms),V/AlarmManager( 2422): waitForAlarm result :8
V/AlarmManager( 2422): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2583): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2583): handleTimeUpdate
I/ActivityManager( 2422): Killing 6579:com.policydm/1000 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 7344:com.sec.android.soagent/u0a38 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 7270:com.vlingo.midas/u0a34 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 7332:com.samsung.klmsagent/u0a18 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 7313:com.sec.android.fotaclient/u0a11 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 5722:com.sec.android.diagmonagent/1000 (adj 15): empty for 1805s
I/ActivityManager( 2422): Killing 7299:com.sec.android.cloudagent/u0a2 (adj 15): empty for 1806s
I/ActivityManager( 2422): Killing 6552:com.sec.pcw.device/1000 (adj 15): empty for 1806s
I/ActivityManager( 2422): Killing 2836:com.android.settings/1000 (adj 15): empty for 1806s
I/ActivityManager( 2422): Killing 7474:com.sec.android.provider.badge/u0a76 (adj 15): empty for 1806s
D/STATUSBAR-IconMerger( 2583): checkOverflow(288), More:false, Req:false Child:3
D/AndroidRuntime(11830): 
D/AndroidRuntime(11830): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11830): CheckJNI is OFF
D/AndroidRuntime(11830): setted country_code = Poland
D/AndroidRuntime(11830): setted countryiso_code = PL
D/AndroidRuntime(11830): setted sales_code = PLS
D/AndroidRuntime(11830): readGMSProperty: start
D/AndroidRuntime(11830): readGMSProperty: already setted!!
D/AndroidRuntime(11830): readGMSProperty: end
D/AndroidRuntime(11830): addProductProperty: start
D/dalvikvm(11830): Trying to load lib libjavacore.so 0x0
D/dalvikvm(11830): Added shared lib libjavacore.so 0x0
D/dalvikvm(11830): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(11830): Added shared lib libnativehelper.so 0x0
D/dalvikvm(11830): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(11830): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(11830): failed to load memtrack module: -2
D/dalvikvm(11830): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(11830): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2422): START PACKAGE DELETE: observer{1123856792}
D/PackageManager( 2422): pkg{<packageName>}
D/PackageManager( 2422): user{0}
D/PackageManager( 2422): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2422): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2422): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2422): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 2422): !@killApplicatoin: 10576, uninstall pkg
W/PackageSettings( 2422): Skipping PackageSetting{42760de8 com.example.hello/10551} due to missing metadata
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10576, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2603): onReceive: android.intent.action.PACKAGE_REMOVED
E/SamsungIME( 2979): mOCRHelper is null
I/InputReader( 2422): Reconfiguring input devices.  changes=0x00000010
D/PackageManager( 2422): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10576, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/QuickConnect[1.1][2] ( 5115): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2738): Ignoring removeGeofence because network location is disabled.
I/SELinux (11859): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11859):  
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/SELinux (11859): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11859):  
I/SELinux (11859):  
I/SELinux (11859): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11859): >>>>> Normal User
E/dalvikvm(11859): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
D/dalvikvm( 2983): GC_EXPLICIT freed 1468K, 27% free 10035K/13652K, paused 9ms+7ms, total 179ms
E/SELinux (11859): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(11859): in addTimaSignatureService
D/TimaKeyStoreProvider(11859): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11859): Added TimaKesytore provider
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 3444): GC_EXPLICIT freed 2339K, 22% free 12527K/15948K, paused 10ms+38ms, total 290ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2422): GC_EXPLICIT freed 2329K, 71% free 24955K/84020K, paused 14ms+25ms, total 359ms
D/dalvikvm( 2422): WAIT_FOR_CONCURRENT_GC blocked 127ms
D/RegisteredServicesCache( 2759): empty dynamic service
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm(11859): GC_CONCURRENT freed 3000K, 30% free 9565K/13648K, paused 5ms+2ms, total 48ms
D/dalvikvm(11859): WAIT_FOR_CONCURRENT_GC blocked 35ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
D/elm:14132(11859): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/elm:14132(11859): ELMEngine.ELMEngine( context ).
D/elm:14132(11859): MDMBridge.setEnterpriseBridge()
D/RCPManagerService( 2422): PackageReceiver onReceive()
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/HarmonyEASService( 2422): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/elm:14132(11859): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/elm:14132(11859): ElmAgentService : onCreate()
D/elm:14132(11859): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(11859): MainReceiver.listeningToPackageRemoved()
D/elm:14132(11859): MDMBridge.getInstance()
D/elm:14132(11859): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14132(11859): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (11873): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11873):  
D/dalvikvm( 1922): GC_EXPLICIT freed 42K, 11% free 9502K/10628K, paused 3ms+4ms, total 40ms
I/SELinux (11873): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11873):  
I/SELinux (11873):  
I/SELinux (11873): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11873): >>>>> Normal User
E/dalvikvm(11873): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
E/SELinux (11873): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 3ms+4ms, total 34ms
D/TimaKeyStoreProvider(11873): in addTimaSignatureService
D/dalvikvm( 1922): GC_EXPLICIT freed <1K, 11% free 9502K/10628K, paused 3ms+3ms, total 33ms
D/TimaKeyStoreProvider(11873): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11873): Added TimaKesytore provider
D/elm:14132(11859): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
D/EnterpriseDeviceManagerService( 2422): Package has changed for user 0
D/elm:14132(11859): ElmAgentService : onDestroy().
I/ActivityManager( 2422): Killing 7515:com.sec.android.app.videoplayer/u0a53 (adj 15): empty for 1808s
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(11873): GC_CONCURRENT freed 2997K, 30% free 9568K/13652K, paused 3ms+1ms, total 75ms
D/dalvikvm(11873): WAIT_FOR_CONCURRENT_GC blocked 66ms
D/BackupManagerService( 2422): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/BackupManagerService( 2422): removePackageParticipantsLocked: uid=10576 #1
D/dalvikvm( 2422): GC_EXPLICIT freed 1123K, 71% free 25054K/84020K, paused 12ms+31ms, total 613ms
I/SELinux (11889): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11889):  
I/ActivityManager( 2422): Killing 7520:com.sec.android.app.voicenote/1000 (adj 15): empty for 1808s
I/SELinux (11889): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11889):  
I/SELinux (11889):  
I/SELinux (11889): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11889): >>>>> Normal User
E/dalvikvm(11889): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (11889): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(11889): in addTimaSignatureService
D/TimaKeyStoreProvider(11889): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11889): Added TimaKesytore provider
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/ApplicationsProvider( 2983): Could not fetch usage stats
W/ApplicationsProvider( 2983): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2983): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2983): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2983): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2983): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2983): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2983): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2983): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2983): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2983): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2983): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2983): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/PackageManager( 2422): delete sourFile : 
D/dalvikvm(11889): GC_CONCURRENT freed 2997K, 30% free 9571K/13656K, paused 2ms+1ms, total 20ms
D/dalvikvm(11889): WAIT_FOR_CONCURRENT_GC blocked 17ms
D/PackageManager( 2422): delete native library directory: 
D/PackageManager( 2422): return delete result to caller: 1123856792
D/AndroidRuntime(11830): Shutting down VM
D/PackageManager( 2422): returnCode: 1
D/dalvikvm(11830): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+1ms, total 4ms
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "sms"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "smsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (11903): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11903):  
I/ActivityManager( 2422): Killing 5782:com.osp.app.signin/u0a44 (adj 15): empty for 1809s
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mms"
I/SELinux (11903): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11903):  
I/SELinux (11903):  
I/SELinux (11903): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11903): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(11903): >>>>> Normal User
E/dalvikvm(11903): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (11903): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/PackageManager( 2422):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2422):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2422):   Scheme: "mmsto"
I/PackageManager( 2422): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(11903): in addTimaSignatureService
D/TimaKeyStoreProvider(11903): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11903): Added TimaKesytore provider
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(11903): GC_CONCURRENT freed 2993K, 30% free 9565K/13648K, paused 3ms+2ms, total 33ms
D/dalvikvm(11903): WAIT_FOR_CONCURRENT_GC blocked 26ms
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2422): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/SELinux (11916): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11916):  
I/CrashAnrDetector( 2422): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2422): clearDefaults: com.test.thalitest
I/SELinux (11916): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11916):  
I/SELinux (11916):  
I/SELinux (11916): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11916): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11916): >>>>> Normal User
E/dalvikvm(11916): >>>>> com.sec.pcw.device [ userId:0 | appId:1000 ]
E/SELinux (11916): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dalvikvm(11916): Enabling JNI app bug workarounds for target SDK version 8...
D/TimaKeyStoreProvider(11916): in addTimaSignatureService
D/TimaKeyStoreProvider(11916): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11916): Added TimaKesytore provider
I/ActivityManager( 2422): Killing 7356:com.samsung.android.scloud.backup/u0a62 (adj 15): empty for 1809s
D/dalvikvm(11916): GC_CONCURRENT freed 2996K, 30% free 9574K/13656K, paused 4ms+1ms, total 29ms
D/dalvikvm(11916): WAIT_FOR_CONCURRENT_GC blocked 22ms
E/SQLiteDatabase(11916): Failed to open database '/data/data/com.sec.pcw.device/databases/value.db'.
E/SQLiteDatabase(11916): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(11916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(11916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(11916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(11916): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/SQLiteDatabase(11916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase(11916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(11916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11916): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(11916): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(11916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(11916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(11916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(11916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(11916): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(11916): Shutting down VM
W/dalvikvm(11916): threadid=1: thread exiting with uncaught exception (group=0x419efc08)
E/AndroidRuntime(11916): FATAL EXCEPTION: main
E/AndroidRuntime(11916): Process: com.sec.pcw.device, PID: 11916
E/AndroidRuntime(11916): java.lang.RuntimeException: Unable to get provider com.sec.pcw.device.contentprovider.URLProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime(11916): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime(11916): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime(11916): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(11916): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(11916): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11916): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(11916): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(11916): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(11916): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(11916): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(11916): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(11916): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(11916): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(11916): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(11916): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(11916): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(11916): 	at com.sec.pcw.device.contentprovider.URLProvider.onCreate(URLProvider.java:30)
E/AndroidRuntime(11916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime(11916): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime(11916): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime(11916): 	... 12 more
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
I/SELinux (11932): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11932):  
I/Process (11916): Sending signal. PID: 11916 SIG: 9
I/ActivityManager( 2422): Process com.sec.pcw.device (pid 11916) (adj 0) has died.
D/SSRMv2:SIOP( 2422): SIOP:: AP = 310, Delta = 0
D/AmoledAdjustTimer( 2422): prevTemp = 282, currTemp = 282, prevStep = 4, currStep = 4
I/SELinux (11932): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11932):  
I/SELinux (11932):  
I/SELinux (11932): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11932): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11932): >>>>> Normal User
E/dalvikvm(11932): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (11932): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(11932): in addTimaSignatureService
D/TimaKeyStoreProvider(11932): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11932): Added TimaKesytore provider
D/dalvikvm(11932): GC_CONCURRENT freed 2995K, 30% free 9569K/13652K, paused 4ms+2ms, total 26ms
D/dalvikvm(11932): WAIT_FOR_CONCURRENT_GC blocked 19ms
W/System.err(11932): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(11932): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(11932): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(11932): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(11932): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(11932): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(11932): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(11932): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(11932): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(11932): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(11932): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(11932): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(11932): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(11932): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(11932): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(11932): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(11932): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(11932): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(11932): 	at libcore.io.Posix.open(Native Method)
W/System.err(11932): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(11932): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(11932): 	... 21 more
D/GalaxyFinderApplication(11932): [Slink platform] Version = 29011
D/GalaxyFinderApplication(11932): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (11946): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11946):  
I/ActivityManager( 2422): Killing 7369:com.sec.android.widgetapp.ap.hero.accuweather/u0a68 (adj 15): empty for 1810s
I/SELinux (11946): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11946):  
I/SELinux (11946):  
I/SELinux (11946): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11946): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(11946): >>>>> Normal User
E/dalvikvm(11946): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (11946): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(11946): in addTimaSignatureService
D/TimaKeyStoreProvider(11946): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11946): Added TimaKesytore provider
D/dalvikvm(11946): GC_CONCURRENT freed 3006K, 30% free 9561K/13652K, paused 2ms+2ms, total 25ms
D/dalvikvm(11946): WAIT_FOR_CONCURRENT_GC blocked 22ms
W/ContextImpl(11946): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2422): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
E/Device Type Shared Preferences(11946): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(11946): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(11946): ContentProvider is not null
D/TimaService( 2422): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2422): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
W/ResourceType(11946): No package identifier when getting value for resource number 0x00000000
I/System.out(11946): resource Id::2131361807
E/SQLiteDatabase(11946): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(11946): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(11946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(11946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(11946): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(11946): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(11946): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(11946): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(11946): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(11946): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(11946): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(11946): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(11946): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(11946): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(11946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11946): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(11946): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(11946): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(11946): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(11946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(11946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(11946): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(11946): Shutting down VM
W/dalvikvm(11946): threadid=1: thread exiting with uncaught exception (group=0x419efc08)
E/AndroidRuntime(11946): FATAL EXCEPTION: main
E/AndroidRuntime(11946): Process: com.sec.android.app.shealth, PID: 11946
E/AndroidRuntime(11946): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11946): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(11946): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(11946): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(11946): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11946): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(11946): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(11946): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(11946): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(11946): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(11946): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(11946): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(11946): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(11946): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(11946): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(11946): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(11946): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(11946): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(11946): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(11946): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(11946): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(11946): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(11946): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(11946): 	... 10 more
E/DropBoxManagerService( 2422): Can't write: system_app_crash
E/DropBoxManagerService( 2422): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
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
I/SELinux (11966): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11966):  
I/Process (11946): Sending signal. PID: 11946 SIG: 9
I/ActivityManager( 2422): Process com.sec.android.app.shealth (pid 11946) (adj 0) has died.
D/Launcher( 2785): onTrimMemory. Level: 5
D/HeadlinesChannelApplication( 5849): HeadlinesChannelApplication.onTrimMemory(). level : 60
V/SamsungIME( 2979): onTrimMeomory Level = 5
I/SELinux (11966): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11966):  
I/SELinux (11966):  
I/SELinux (11966): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11966): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(11966): >>>>> Normal User
E/dalvikvm(11966): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
W/GeoLookout( 3104): at (DisasterAlertApplication.java:67) [onTrimMemory()]

```
