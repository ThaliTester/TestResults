#### Test 57617811ecc172f_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system,
D/AmoledAdjustTimer( 2403): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4
--------- beginning of /dev/log/main
D/AndroidRuntime( 7198): 
D/AndroidRuntime( 7198): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7198): CheckJNI is OFF
D/AndroidRuntime( 7198): setted country_code = Poland
D/AndroidRuntime( 7198): setted countryiso_code = PL
D/AndroidRuntime( 7198): setted sales_code = PLS
D/AndroidRuntime( 7198): readGMSProperty: start
D/AndroidRuntime( 7198): readGMSProperty: already setted!!
D/AndroidRuntime( 7198): readGMSProperty: end
D/AndroidRuntime( 7198): addProductProperty: start
D/dalvikvm( 7198): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7198): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7198): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7198): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7198): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7198): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7198): failed to load memtrack module: -2
D/dalvikvm( 7198): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7198): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2403): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.acquire()
I/SurfaceFlinger( 1922): id=21 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1922): id=22 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7225): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7225):  
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7198): Shutting down VM
D/dalvikvm( 7198): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7225): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7225):  
I/SELinux ( 7225):  
I/SELinux ( 7225): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7225): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7225): >>>>> Normal User
E/dalvikvm( 7225): >>>>> com.test.thalitest [ userId:0 | appId:10658 ]
E/SELinux ( 7225): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7225): in addTimaSignatureService
D/TimaKeyStoreProvider( 7225): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7225): Added TimaKesytore provider
V/WindowManager( 2403): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4179): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4179): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1922): id=19 Removed Mauncher (8/10)
I/SurfaceFlinger( 1922): id=19 Removed Mauncher (-2/10)
D/Launcher( 2777): onTrimMemory. Level: 20
D/dalvikvm( 7225): GC_CONCURRENT freed 3000K, 32% free 9566K/13872K, paused 3ms+2ms, total 19ms
D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 14ms
V/WebViewChromium( 7225): Binding Chromium to the background looper Looper (main, tid 1) {4244cf50}
I/chromium( 7225): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7225): Initializing chromium process, renderers=0
W/chromium( 7225): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7225): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7225): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7225): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7225): Mali API Version : 401
,I/Mali    ( 7225): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7225): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7225): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7225): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7225): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7225): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7225): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/StatusBarManagerService( 2403): tr p:7225,o:f
W/dalvikvm( 7225): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7225): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7225): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7225): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7225): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7225): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7225): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7225): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7225): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7225): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7225): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7225): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7225): CordovaWebView is running on device made by: samsung
,D/StatusBarManagerService( 2403): semi p:7225,o:f
D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,I/SurfaceFlinger( 1922): id=23 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7225): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7225): Enabling debug mode 0
W/AwContents( 7225): nativeOnDraw failed; clearing to background color.
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/AwContents( 7225): nativeOnDraw failed; clearing to background color.
D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2403): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2403): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  pkgName : ACTIVITY_RESUME_BOOSTER@8
,W/IInputConnectionWrapper( 7225): showStatusIcon on inactive InputConnection
,D/JsMessageQueue( 7225): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7225): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424496f8
,D/dalvikvm( 7225): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x424496f8
,D/jxcore_app_log( 7225): JniHelper::setJavaVM(0x419a8220), pthread_self() = 2026775592
,I/chromium( 7225): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 7225): GC_CONCURRENT freed 1307K, 19% free 11332K/13940K, paused 2ms+2ms, total 28ms
,D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/dalvikvm( 7225): GC_FOR_ALLOC freed 2344K, 21% free 14339K/17996K, paused 33ms, total 33ms
,D/CustomFrequencyManagerService( 2403): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2403  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7225): GC_CONCURRENT freed 6474K, 33% free 16028K/23832K, paused 1ms+8ms, total 57ms
D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 29ms
,D/dalvikvm( 7225): WAIT_FOR_CONCURRENT_GC blocked 27ms
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7225): GC_FOR_ALLOC freed 5330K, 30% free 16852K/23832K, paused 42ms, total 42ms
,W/jxcore-log( 7225): Initializing JXcore engine
,W/jxcore-log( 7225): JXcore engine is ready
,W/jxcore-log( 7225): Starting JXcore engine
,W/jxcore-log( 7225): Platform android
W/jxcore-log( 7225): 
,W/jxcore-log( 7225): Process ARCH arm
W/jxcore-log( 7225): 
,I/jxcore-log( 7225): JXcore Cordova bridge is ready!
I/jxcore-log( 7225): 
,W/jxcore-log( 7225): JXcore engine is started
,I/jxcore-log( 7225): Toggling radios to true
I/jxcore-log( 7225): 
,D/BluetoothAdapter( 7225): enable(): BT is already enabled..!
,I/WifiManager( 7225): packageName : com.test.thalitest
,I/WifiManager( 7225): setWifiEnabled : true
,I/WifiService( 2403): setWifiEnabled: true pid=7225, uid=10658
W/ActivityManager( 2403): Permission Denial: getCurrentUser() from pid=7225, uid=10658 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2403): Failed getting userId using ActivityManagerNative
W/WifiService( 2403): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7225, uid=10658 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2403): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2403): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2403): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2403): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2403): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2403): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2403): disconnect: pid=7225, uid=10658
,I/wpa_supplicant( 3965): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/jxcore-log( 7225): Radios toggled
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): My device name is: samsung-SM-G800F
I/jxcore-log( 7225): 
,I/wpa_supplicant( 3965): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3965): First Scan Start
W/Settings( 2403): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2403): ignore requestNetworkTransitionWakelock airplane:true
,I/wpa_supplicant( 3965): Scan requested (ret=0) - scan timeout 30 seconds
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2403): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 3965): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3965): Skip scan - already scanning
D/ConnectivityService( 2403): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2403): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2403): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2403): net.tcp.delack.default not found in system default properties
E/ConnectivityService( 2403): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/ConnectivityService( 2403): Attempting to switch to mobile
,D/ConnectivityService( 2403): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7274): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7274):  
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1916): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,V/RouteController( 1916): /system/bin/ip -6 route del default table 2 2>&1
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/WifiStateMachine( 2403): Error! unhandled message{ when=-70ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine( 2403): Error! unhandled message{ when=-69ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2403): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 13% free 9503K/10848K, paused 3ms+5ms, total 53ms
,V/RouteController( 1916): RTNETLINK answers: No such process
,I/SELinux ( 7274): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7274):  
I/SELinux ( 7274):  
,I/SELinux ( 7274): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,V/RouteController( 1916): /system/bin/ip -6 rule del table 2 2>&1
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7274): >>>>> Normal User
,E/dalvikvm( 7274): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7274): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 3ms+5ms, total 38ms
,W/NetworkManagementService( 2403): route cmd failed: ,
W/NetworkManagementService( 2403): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2403): '
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
,W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2403): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2403): 	,at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2403): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2403): ,	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2403): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2403): ,	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2403): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2403): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1916): /system/bin/ip -4 route del default table 2 2>&1,
,V/RouteController( 1916): RTNETLINK answers: No such process,
D/TimaKeyStoreProvider( 7274): in addTimaSignatureService,
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1,
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 4ms+4ms, total 36ms
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1,
,D/TimaKeyStoreProvider( 7274): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7274): Added TimaKesytore provider,
,D/NetUtils( 2403): android_net_utils_resetConnections in env=0x789fb4d8 clazz=0x62c00001 iface=wlan0 mask=0x3,
D/ConnectivityService( 2403): resetConnections(wlan0, 3)
,V/NativeCrypto( 2849): Read error: ssl=0x7b9cb9a8: I/O error during system call, Connection timed out,
,V/NativeCrypto( 2849): SSL shutdown failed: ssl=0x7b9cb9a8: I/O error during system call, Broken pipe,
,D/dalvikvm( 7274): GC_CONCURRENT freed 2997K, 32% free 9573K/13876K, paused 4ms+2ms, total 29ms,
,D/dalvikvm( 7274): WAIT_FOR_CONCURRENT_GC blocked 20ms,
,E/SPPClientService( 5536): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out),
,E/SPPClientService( 5536): [e] exceptionCaught(). NET_TIMEOUT,
,E/SPPClientService( 5536): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.,
,E/SPPClientService( 5536): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE,
,E/SPPClientService( 5536): [b] ResponseMap empty,
,I/System.out( 7274): Inside WakeupProvider
,I/System.out( 7274): Inside onCreate() of WakeupTriggerProvide
,I/VlingoApplication( 7274): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7274): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7274): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/ConnectivityService( 2403): handleInetConditionChange: no active default network - ignore
V/NetworkStats( 2403): updateIfacesLocked()
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,V/NetworkStats( 2403): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked() took 24ms
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Set preference state off
,D/DialogFlow( 7274): initQueue()
,I/ActivityManager( 2403): Killing 6384:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
V/NearbySettings( 2834): MountReceiver.mPrefHandler - 7002
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2834): MountReceiver.mPrefHandler - 7002
,D/Tethering( 2403): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2403): MasterInitialState.processMessage what=3
,I/ApplicationPolicy( 2403): updateDataUsageMap
,D/CaptivePortalTracker( 2403): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2403): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4741): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): noConnectivity : true
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection...
,I/wpa_supplicant( 3965): nl80211: Received scan results (4 BSSes)
I/wpa_supplicant( 3965): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3965): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): Associated with C0.AA.48
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3965): freq(2412) increment count 2
,I/wpa_supplicant( 3965): meet head of list.
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/SELinux ( 7303): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7303):  
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3965): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3965): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3965): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2403): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2403): interfaceStatusChanged wlan0, true
,D/WifiNative( 2403): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/SELinux ( 7303): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
,I/SELinux ( 7303):  
I/SELinux ( 7303):  
,I/SELinux ( 7303): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7303): >>>>> Normal User
,E/dalvikvm( 7303): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7303): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7303): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7303): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7303): Added TimaKesytore provider
,D/WifiP2pService( 2403): InactiveState{ what=143375 }
,D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/dalvikvm( 7303): GC_CONCURRENT freed 3007K, 32% free 9566K/13876K, paused 5ms+2ms, total 29ms
,D/dalvikvm( 7303): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/ActivityManager( 2403): Killing 6276:com.sec.phone/1001 (adj 15): empty #43
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4380, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3989): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2580): checkOverflow(336), More:false, Req:false Child:3
,D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SELinux ( 7321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7321):  
,I/SELinux ( 7321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7321):  
I/SELinux ( 7321):  
,I/SELinux ( 7321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7321): >>>>> Normal User
,E/dalvikvm( 7321): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/dhcpcd  ( 7317): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7317): bssid match
,D/TimaKeyStoreProvider( 7321): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7321): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7321): Added TimaKesytore provider
,D/dalvikvm( 7321): GC_CONCURRENT freed 2986K, 31% free 9573K/13868K, paused 4ms+5ms, total 29ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 24ms
,D/KLMS-2.3.201 : ( 7321): KLMSValidator() : checkQATesting()
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 330, Delta = 10
,I/KLMS-2.3.201 : ( 7321): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454063564201
,I/KLMS-2.3.201 : ( 7321): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
I/ActivityManager( 2403): Killing 6335:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43
,I/SELinux ( 7337): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7337):  
,I/SELinux ( 7337): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7337):  
I/SELinux ( 7337):  
,I/SELinux ( 7337): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7337): >>>>> Normal User
,E/dalvikvm( 7337): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7337): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7337): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7337): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7337): Added TimaKesytore provider
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 7337): GC_CONCURRENT freed 2997K, 32% free 9566K/13868K, paused 4ms+1ms, total 25ms
,D/dalvikvm( 7337): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/SO_AGENT( 7337): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7337): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5819): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5819): [BDLM] already registered in spp
I/SA      ( 5819): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5819): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5819): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5819): [OR] == isSIMCardReady false ==
I/SA      ( 5819): [SCU] == networkStateCheck == false
,I/SA      ( 5819): [OR] onReceive END
I/ActivityManager( 2403): Killing 5977:com.android.calendar/u0a144 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6611): Other Intent
,I/SELinux ( 7349): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7349):  
,I/SELinux ( 7349): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7349):  
I/SELinux ( 7349):  
,I/SELinux ( 7349): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7349): >>>>> Normal User
,E/dalvikvm( 7349): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7349): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7349): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7349): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7349): Added TimaKesytore provider
,D/dalvikvm( 7349): GC_CONCURRENT freed 3001K, 32% free 9571K/13876K, paused 3ms+2ms, total 22ms
,D/dalvikvm( 7349): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7349): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7349): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5335): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7349): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5335): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7349): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5335): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2403): Killing 6155:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/Headlines( 5871): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5871): getCountryCode(): countryCode = PL
,D/Headlines( 5871): Breath.onCreate
,D/Headlines( 5871): Breath timer started. interval : 30000
,I/SELinux ( 7361): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7361):  
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5871): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
,D/HeadlinesCardManager( 5871): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5871): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2403): waitForAlarm result :8
,I/SELinux ( 7361): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7361):  
I/SELinux ( 7361):  
,I/SELinux ( 7361): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7361): >>>>> Normal User
,E/dalvikvm( 7361): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7361): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7361): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7361): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7361): Added TimaKesytore provider
,D/dalvikvm( 7361): GC_CONCURRENT freed 3016K, 32% free 9555K/13872K, paused 2ms+1ms, total 19ms,
,D/dalvikvm( 7361): WAIT_FOR_CONCURRENT_GC blocked 17ms
,V/WebViewChromium( 7361): Binding Chromium to the background looper Looper (main, tid 1) {42448028},
,I/chromium( 7361): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0,
,I/BrowserProcessMain( 7361): Initializing chromium process, renderers=0,
,W/chromium( 7361): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation,
,D/libEGL  ( 7361): loaded /system/lib/egl/libEGL_mali.so,
,D/libEGL  ( 7361): loaded /system/lib/egl/libGLESv1_CM_mali.so,
,D/libEGL  ( 7361): loaded /system/lib/egl/libGLESv2_mali.so,
,I/Mali    ( 7361): Mali API Version : 401
,I/Mali    ( 7361): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 ,
,W/GAV2    ( 7361): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1912): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/ContextImpl( 7361): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
W/Vold    ( 1912): Returning OperationFailed - no handler for errno 30
,I/NSApplication( 7361): Starting up...
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/QuickConnect[1.1][2] ( 5136): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5136): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5136): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42454fe0
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,I/SELinux ( 7411): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7411):  
,I/iu.UploadsManager( 5935): num queued entries: 0
,I/iu.UploadsManager( 5935): num updated entries: 0
,I/iu.SyncManager( 5935): NEXT; no task
,I/SELinux ( 7411): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7411):  
I/SELinux ( 7411):  
I/SELinux ( 7411): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7411): >>>>> Normal User
E/dalvikvm( 7411): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7411): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7411): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7411): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7411): Added TimaKesytore provider
,D/dalvikvm( 7411): GC_CONCURRENT freed 2984K, 31% free 9582K/13872K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7411): WAIT_FOR_CONCURRENT_GC blocked 18ms
D/WifiP2pService( 2403): InactiveState{ what=143375 }
D/WifiP2pService( 2403): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2403): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2403): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2403): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
,D/WifiStateMachine( 2403): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2403): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2403): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2403): evaluateTrafficStatsPolling
D/ConnectivityService( 2403): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2403): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2403): net.tcp.delack.wifi not found in system properties. Using defaults
,D/STATUSBAR-NetworkController( 2580): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster - setNWBoosterIndicators(false)
,D/STATUSBAR-NetworkController( 2580): refreshSignalCluster: data=-1 bt=false
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/ConnectivityService( 2403): handleConnectivityChange: setting default proxy info 
,V/RouteController( 1916): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,V/RouteController( 1916): /system/bin/ip -4 rule del table 2 2>&1
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,V/RouteController( 1916): RTNETLINK answers: No such file or directory
,V/RouteController( 1916): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1916): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1916): RTNETLINK answers: No such process
,V/RouteController( 1916): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
,V/RouteController( 1916): /system/bin/ip route flush cached 2>&1
,V/NetworkStats( 2403): updateIfacesLocked()
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit,
,V/NetworkStats( 2403): performPollLocked(flags=0x1),
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
V/NetworkStats( 2403): performPollLocked() took 25ms
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2403): currentTimeMillis() cache hit
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,I/SELinux ( 7454): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7454):  
,I/ActivityManager( 2403): Killing 6194:com.google.android.music:main/u0a125 (adj 15): empty #43
,I/SELinux ( 7454): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7454):  
I/SELinux ( 7454):  
,I/SELinux ( 7454): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7454): >>>>> Normal User
,E/dalvikvm( 7454): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,E/SELinux ( 7454): [DEBUG] seapp_context_lookup: seinfoCategory = release
,W/ActivityManager( 2403): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/TimaKeyStoreProvider( 7454): in addTimaSignatureService
,I/SELinux ( 7466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7466):  
,D/TimaKeyStoreProvider( 7454): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7454): Added TimaKesytore provider
,I/ActivityManager( 2403): Killing 6563:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 7466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7466):  
I/SELinux ( 7466):  
,I/SELinux ( 7466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7466): >>>>> Normal User
,E/dalvikvm( 7466): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7466): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7466): Added TimaKesytore provider
,D/dalvikvm( 7454): GC_CONCURRENT freed 3013K, 32% free 9559K/13876K, paused 2ms+2ms, total 37ms
,D/dalvikvm( 7454): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/BadgeProvider( 7454): onCreate
,D/BadgeProvider( 7454): DatabaseHelper
,D/BadgeProvider( 7454): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 7454): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 7454): sendNotify, [notify] : null
D/BadgeProvider( 7454): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7454): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7454): update, [UpdateCount] : 1
,D/Launcher.Model( 2777): reloadBadges entered.
,D/dalvikvm( 2403): GC_EXPLICIT freed 3722K, 53% free 25349K/53236K, paused 6ms+19ms, total 194ms
,D/dalvikvm( 7466): GC_CONCURRENT freed 2999K, 32% free 9570K/13876K, paused 2ms+1ms, total 18ms
,D/dalvikvm( 7466): WAIT_FOR_CONCURRENT_GC blocked 15ms
,D/Tethering( 2403): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2403): MasterInitialState.processMessage what=3
D/STATUSBAR-NetworkController( 2580): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2580): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2580): updateDataNetType()
,D/STATUSBAR-NetworkController( 2580): NoService, mRoamingIconId = 0
D/CaptivePortalTracker( 2403): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/DBG_DM  ( 4741): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/hcjo    ( 5957): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5957): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5957): exit::IDLE
,D/InitializeManagerStateMachine( 5957): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5957): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5957): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): entry::SUCCESS
,D/hcjo    ( 5957): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5957): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5957): exit::SUCCESS
,D/InitializeManagerStateMachine( 5957): entry::IDLE
,E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 249339
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : true
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection...
,E/SPPClientService( 5536): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,D/Headlines( 5871): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5871): Breath 1610 latestRequest time : 1454063564793 current time : 1454063566403
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5536): [[PushClientService]] <<--- deInitPushClientService  END  --->>
I/ActivityManager( 2403): Killing 6296:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,E/SPPClientService( 5536): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2834): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2834): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,D/NearbySettings( 2834): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2834): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1922): id=24 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5536): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [a] [ConnectionManager] Connection is already disconnected.
D/PowerManagerService( 2403): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2403
,E/SPPClientService( 5536): [g] getNetMCC return empty string
,I/KLMS-2.3.201 : ( 7321): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7321): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454063566763
,I/KLMS-2.3.201 : ( 7321): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7337): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
I/LocationTagReadyService( 3297): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,I/SO_AGENT( 7337): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3297): [Slink platform] The state of Slink geocode service is true
,I/dalvikvm( 7303): Total arena pages for JIT: 11
,I/dalvikvm( 7303): Total arena pages for JIT: 12
I/dalvikvm( 7303): Total arena pages for JIT: 13
I/dalvikvm( 7303): Total arena pages for JIT: 14
,I/dalvikvm( 7303): Total arena pages for JIT: 15
I/dalvikvm( 7303): Total arena pages for JIT: 16
,I/dalvikvm( 7303): Total arena pages for JIT: 17
,I/SELinux ( 7489): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7489):  
I/GallerySearchProvider( 3425): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/dalvikvm( 7303): Total arena pages for JIT: 18
I/SELinux ( 7489): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7489):  
I/SELinux ( 7489):  
,I/SELinux ( 7489): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7489): >>>>> Normal User
,E/dalvikvm( 7489): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7489): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7489): in addTimaSignatureService
,I/SELinux ( 7502): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7502):  
,D/TimaKeyStoreProvider( 7489): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7489): Added TimaKesytore provider,
,I/SELinux ( 7502): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7502):  
I/SELinux ( 7502):  
,I/SELinux ( 7502): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7502): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7502): >>>>> Normal User
,E/dalvikvm( 7502): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
,E/SELinux ( 7502): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7502): in addTimaSignatureService,
I/SA      ( 5819): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5819): [BDLM] already registered in spp
,I/SA      ( 5819): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5819): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5819): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
I/SA      ( 5819): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 7502): Cannot add TimaSignature Service, License check Failed
,I/SA      ( 5819): [SCU] == networkStateCheck == true
I/SA      ( 5819): [DM] getCountryCodeFromCSC : PL
,I/SA      ( 5819): isChinaCountryCode : false
I/SA      ( 5819): [OR] == networkStateCheck true ==
,I/SA      ( 5819): [OR] GetMyCountryZoneTask
,D/ActivityThread( 7502): Added TimaKesytore provider
,I/SA      ( 5819): [OR] onReceive END
,D/dalvikvm( 7489): GC_CONCURRENT freed 2989K, 31% free 9580K/13876K, paused 5ms+1ms, total 29ms
,D/dalvikvm( 7489): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/SA      ( 5819): [SRS] prepareGetMyCountryZone
D/PhoneNumberLocatorBootCompletedReceiver( 2753): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2753): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6611): Other Intent
,I/SA      ( 5819): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5819): [SSP] query invoked
,I/SA      ( 5819): [TPMU] GetMccFromDB : null
I/SA      ( 5819): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5819): [TPM] isNoProxy(default) : true
D/dalvikvm( 7502): GC_CONCURRENT freed 3005K, 32% free 9560K/13872K, paused 3ms+1ms, total 32ms
D/dalvikvm( 7502): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7349): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,I/SA      ( 5819): [RC New] Execute method=[GET] start
,D/Headlines( 5871): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5871): getCountryCode(): countryCode = PL
,V/KVNProvider( 7502): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7502): getFindoCursor query string : 
,D/dalvikvm( 2723): GC_EXPLICIT freed 356K, 29% free 9972K/13860K, paused 8ms+9ms, total 64ms
,V/KVNProvider( 7502): getTagSearchCursor() tagSearchCursor count : 0
,D/Headlines( 5871): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5871): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5871): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5871): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5871): requestUpdateNewsWelcomeCard !!! no welcome card
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,I/iu.Environment( 5935): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/System.out( 7303): Thread-642(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/QuickConnect[1.1][2] ( 5136): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect[1.1][2] ( 5136): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5136): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@42454fe0
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,D/RCPManagerService( 2403): exchangeData() failure , invalid userId
,I/System.out( 7303): Thread-642(ApacheHTTPLog):isShipBuild true
,I/System.out( 7303): Thread-642(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/iu.UploadsManager( 5935): num queued entries: 0
,D/hcjo    ( 5957): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5957): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5957): exit::IDLE
,D/InitializeManagerStateMachine( 5957): entry::NETWORK_CHECK
I/iu.UploadsManager( 5935): num updated entries: 0
D/InitializeManagerStateMachine( 5957): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5957): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5957): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5957): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,D/InitializeManagerStateMachine( 5957): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5957): entry::SUCCESS
,D/hcjo    ( 5957): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5957): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 5957): exit::SUCCESS
,D/InitializeManagerStateMachine( 5957): entry::IDLE
,I/iu.SyncManager( 5935): NEXT; no task
,E/SPPClientService( 5536): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5536): [SystemStateMoniter] Current Time : 250407
,E/SPPClientService( 5536): [SystemStateMoniter] No Connect : false
,D/libgps  ( 2403): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 5536): GC_CONCURRENT freed 1965K, 25% free 10446K/13864K, paused 5ms+4ms, total 42ms
,I/System.out( 7303): AsyncTask #1 calls detatch()
,W/System.err( 7303): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7303): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7303): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7303): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7303): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7303): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7303): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7303): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
,W/System.err( 7303): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 7303): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7303): Caused by: java.lang.NullPointerException
,W/System.err( 7303): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7303): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7303): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7303): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7303): 	... 8 more
,I/ActivityManager( 2403): Killing 6575:com.android.chrome/u0a85 (adj 15): empty #43
,W/WifiP2pStateTracker( 2403): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2403): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2403):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2403): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2403): updateSourceRoutes : no source routing conditions
,I/SA      ( 5819): [RC New] [v2liruge] api execute + 735
,I/SA      ( 5819): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5819): AsyncTask #2 calls detatch()
,I/SA      ( 5819): [TPMU] getNetworkMcc : 
,I/SA      ( 5819): [SCU] saveMccToPreferece Start
,I/SA      ( 5819): [SCU] RegionMCC : 260
,I/SA      ( 5819): [SSP] query invoked
I/SA      ( 5819): [TPMU] GetMccFromDB : null
,I/SA      ( 5819): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5819): [SCU] saveMccToPreferece End
I/SA      ( 5819): [RC New] executeRequest [v2liruge] end. 759
,I/SA      ( 5819): [RC New] Execute end
I/SA      ( 5819): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5819): [OR] GetMyCountryZoneTask Success
,D/PackageManager( 2403): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/libgps  ( 2403): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2403): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2403): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,E/SPPClientService( 5536): [b] __InitReply__
,I/PowerManagerService( 2403): [PWL] Off : 105s ago
,E/WifiStateMachine( 2403): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1922): id=24 Removed Uoast (10/11)
,I/SurfaceFlinger( 1922): id=24 Removed Uoast (-2/11)
I/ActivityManager( 2403): Killing 6591:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
D/PowerManagerService( 2403): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2403) eventTime = 252996
D/PowerManagerService( 2403): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2403 (0x0)
D/PowerManagerService( 2403): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2403, ws=WorkSource{1000}) (elapsedTime=3465)
,I/GAV2    ( 7361): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6665): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6665): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6665): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7225): 
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2403): stay LED for fully charged
,D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 3989): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 10
,E/Watchdog( 2403): !@Sync 8
,D/CaptivePortalTracker( 2403): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/CaptivePortalTracker( 2403): Checking http://216.58.209.46/generate_204
D/ConnectivityService( 2403): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/PreloadUpdateManagerStateMachine( 5957): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5957): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5957): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5957): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5957): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5957): entry::IDLE
,D/CaptivePortalTracker( 2403): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker( 2403): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2403): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2403): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2403): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/AmoledAdjustTimer( 2403): prevTemp = 297, currTemp = 299, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 5957): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5957): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5957): entry::CHECK_TIMEOUT_FOR_UPDATE
,D/hcjo    ( 5957): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5957): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5957): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5957): entry::IDLE
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{433fa910 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
V/AlarmManager( 2403): waitForAlarm result :8
V/AlarmManager( 2403): ClockReceiver onReceive() ACTION_TIME_TICK
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2580): handleTimeUpdate
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,I/jxcore-log( 7225): Test app app.js loaded
I/jxcore-log( 7225): 
,I/dalvikvm( 7225): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7225): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7225): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7225): setDiscoveryMode: Mode set to BLE
,I/jxcore-log( 7225): BLE advertisement is supported
I/jxcore-log( 7225): 
,I/chromium( 7225): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7225): --= Surplus to requirements =--
I/jxcore-log( 7225): 
I/jxcore-log( 7225): ****TEST TOOK:  ms ****
I/jxcore-log( 7225): 
,I/jxcore-log( 7225): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7225): 
,I/ActivityManager( 2403): Waited long enough for: ServiceRecord{44c53580 u0 com.sec.spp.push/.PushClientService}
,D/AndroidRuntime( 7536): 
D/AndroidRuntime( 7536): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7536): CheckJNI is OFF
,D/AndroidRuntime( 7536): setted country_code = Poland
,D/AndroidRuntime( 7536): setted countryiso_code = PL
,D/AndroidRuntime( 7536): setted sales_code = PLS
D/AndroidRuntime( 7536): readGMSProperty: start
,D/AndroidRuntime( 7536): readGMSProperty: already setted!!
D/AndroidRuntime( 7536): readGMSProperty: end
,D/AndroidRuntime( 7536): addProductProperty: start
,D/dalvikvm( 7536): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7536): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7536): Trying to load lib libnativehelper.so 0x0
,D/dalvikvm( 7536): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7536): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7536): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7536): failed to load memtrack module: -2
,D/dalvikvm( 7536): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7536): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2403): START PACKAGE DELETE: observer{1123668944}
D/PackageManager( 2403): pkg{<packageName>}
D/PackageManager( 2403): user{0}
,D/PackageManager( 2403): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2403): getApplicationUninstallationEnabled :  enabled true
,D/PackageManager( 2403): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 2403): deletePackageX- pkg:com.test.thalitest, userId:0
,D/PackageManager( 2403): !@killApplicatoin: 10658, uninstall pkg
,I/ActivityManager( 2403): Killing 7225:com.test.thalitest/u0a658 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1922): id=22 Removed EimLayer (5/10)
I/SurfaceFlinger( 1922): id=22 Removed EimLayer (-2/10)
,I/SurfaceFlinger( 1922): id=21 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1922): id=21 Removed EimLayer (-2/9)
,V/WindowManager( 2403): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
,D/Launcher( 2777): onRestart, Launcher: 1111993664
D/Launcher( 2777): onStart, Launcher: 1111993664
,D/Launcher.HomeView( 2777): onStart
,I/WindowState( 2403): WIN DEATH: Window{43032b18 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1922): id=23 Removed NainActivit (6/8)
I/SurfaceFlinger( 1922): id=23 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 1922): id=25 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2403): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2403): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2403): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2403): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2403): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2403): tr p:2777,o:f
,D/PhoneStatusBar( 2580): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2580): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2403): semi p:2777,o:f
,W/ContextImpl( 2403): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2403): Got RemoteException sending setActive(false) notification to pid 7225 uid 10658
,W/PackageSettings( 2403): Skipping PackageSetting{42c4aff0 com.example.hello/10614} due to missing metadata
,D/PackageManager( 2403): checkUidPermission - Execution time: 183 ms
,D/PackageManager( 2403): checkUidPermission - Execution time: 116 ms
,D/PackageManager( 2403): checkUidPermission - Execution time: 149 ms
D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10658, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6824): GC_EXPLICIT freed 158K, 30% free 9959K/14108K, paused 5ms+8ms, total 79ms
,D/PackageManager( 2403): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10658, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 2982): mOCRHelper is null
,D/QuickConnect[1.1][2] ( 5136): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
,W/GeofencerStateMachine( 2735): Ignoring removeGeofence because network location is disabled.
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "sms"
,I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux ( 7551): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7551):  
,D/dalvikvm( 2959): GC_EXPLICIT freed 1473K, 28% free 10037K/13872K, paused 18ms+16ms, total 141ms
,D/dalvikvm( 1923): GC_EXPLICIT freed 42K, 13% free 9503K/10848K, paused 3ms+4ms, total 41ms
,I/SELinux ( 7551): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7551):  
I/SELinux ( 7551):  
,I/SELinux ( 7551): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7551): >>>>> Normal User
,E/dalvikvm( 7551): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7551): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 3157): GC_EXPLICIT freed 2191K, 22% free 12534K/16028K, paused 13ms+11ms, total 251ms
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 2ms+4ms, total 34ms
,D/TimaKeyStoreProvider( 7551): in addTimaSignatureService
,D/dalvikvm( 6426): GC_EXPLICIT freed 562K, 29% free 9985K/13956K, paused 6ms+4ms, total 268ms
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 3ms+4ms, total 31ms
,D/TimaKeyStoreProvider( 7551): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7551): Added TimaKesytore provider
,D/PackageManager( 2403): queryIntentReceivers - Execution time: 128 ms
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/InputReader( 2403): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RegisteredServicesCache( 2764): empty dynamic service
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7551): GC_CONCURRENT freed 3004K, 32% free 9566K/13876K, paused 2ms+1ms, total 21ms
,D/dalvikvm( 7551): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 2777K, 53% free 25315K/53236K, paused 17ms+21ms, total 385ms
,D/dalvikvm( 2403): WAIT_FOR_CONCURRENT_GC blocked 113ms
,I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
D/EnterpriseDeviceManagerService( 2403): Package has changed for user 0
I/PackageManager( 2403):   Scheme: "sms"
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2403): PackageReceiver onReceive()
,I/HarmonyEASService( 2403): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/elm:14132( 7551): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,D/elm:14132( 7551): ELMEngine.ELMEngine( context ).
,D/elm:14132( 7551): MDMBridge.setEnterpriseBridge()
,D/elm:14132( 7551): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "mms"
,D/elm:14132( 7551): ElmAgentService : onCreate()
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/elm:14132( 7551): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7551): MainReceiver.listeningToPackageRemoved()
,I/SELinux ( 7565): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7565):  
D/elm:14132( 7551): MDMBridge.getInstance()
,D/elm:14132( 7551): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7551): MDMBridge.getAllLicenseInfoFromSDK()
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "mmsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/SELinux ( 7565): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7565):  
I/SELinux ( 7565):  
,I/SELinux ( 7565): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7565): >>>>> Normal User
E/dalvikvm( 7565): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/elm:14132( 7551): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,E/SELinux ( 7565): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/elm:14132( 7551): ElmAgentService : onDestroy().
,I/ActivityManager( 2403): Killing 6516:com.android.defcontainer/u0a6 (adj 15): empty #43
,D/TimaKeyStoreProvider( 7565): in addTimaSignatureService
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7565): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7565): Added TimaKesytore provider
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 7565): GC_CONCURRENT freed 2990K, 31% free 9579K/13876K, paused 5ms+2ms, total 51ms
,D/dalvikvm( 7565): WAIT_FOR_CONCURRENT_GC blocked 35ms
,D/dalvikvm( 2403): GC_EXPLICIT freed 978K, 53% free 25305K/53236K, paused 10ms+31ms, total 402ms
,D/PackageManager( 2403): delete sourFile : 
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SELinux ( 7580): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7580):  
,I/ActivityManager( 2403): Killing 6454:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,D/BackupManagerService( 2403): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,D/PackageManager( 2403): delete native library directory: 
,V/BackupManagerService( 2403): removePackageParticipantsLocked: uid=10658 #1
,D/PackageManager( 2403): return delete result to caller: 1123668944
,D/AndroidRuntime( 7536): Shutting down VM
,D/PackageManager( 2403): returnCode: 1
D/dalvikvm( 7536): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+0ms, total 4ms
I/SELinux ( 7580): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7580):  
I/SELinux ( 7580):  
I/SELinux ( 7580): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7580): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7580): >>>>> Normal User
E/dalvikvm( 7580): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,E/SELinux ( 7580): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "sms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7580): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7580): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7580): Added TimaKesytore provider
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "smsto"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403):   Scheme: "mms"
I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2403):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2403):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2403): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2403):   Scheme: "mmsto"
,D/dalvikvm( 7580): GC_CONCURRENT freed 2994K, 32% free 9568K/13868K, paused 4ms+3ms, total 40ms
,D/dalvikvm( 7580): WAIT_FOR_CONCURRENT_GC blocked 31ms
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/PCWCLIENTTRACE_PushUtil( 6665): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6665): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6665): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6665): [onReceive] - android.intent.action.PACKAGE_REMOVED
,D/BatteryService( 2403): level:100, scale:100, status:5, health:2, present:true, voltage: 4352, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2403): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2403): stay LED for fully charged
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UiModeManager( 2403): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2580): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2580): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2580):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
V/HeadsetService( 3989): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 3989): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2580): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2580): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/SA      ( 5819): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5819): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 2403): Killing 6638:com.samsung.groupcast/u0a15 (adj 15): empty #43
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
,E/SharedPreferencesImpl( 3425): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2403): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/Icing.InternalIcingCorporaProvider( 6426): Updating corpora: A: com.test.thalitest, C: MAYBE
,D/UsbSettingsManager( 2403): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 2403): onPackageRemoved : com.test.thalitest
E/SQLiteLog( 6426): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 6426): threadid=15: thread exiting with uncaught exception (group=0x419bbc08)
,W/AtomicFile( 2403): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
E/AndroidRuntime( 6426): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6426): Process: com.google.android.googlequicksearchbox:search, PID: 6426
E/AndroidRuntime( 6426): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6426): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6426): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6426): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6426): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6426): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6426): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6426): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6426): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/SELinux ( 7601): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7601):  
W/AppWidgetServiceImpl( 2403): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/Process ( 6426): Sending signal. PID: 6426 SIG: 9
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,D/SSRMv2:SIOP( 2403): SIOP:: AP = 340, Delta = 0
,I/ActivityManager( 2403): Process com.google.android.googlequicksearchbox:search (pid 6426) (adj 5) has died.
,I/SELinux ( 7601): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7601):  
I/SELinux ( 7601):  
,I/SELinux ( 7601): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7601): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7601): >>>>> Normal User
,E/dalvikvm( 7601): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7601): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7601): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7601): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7601): Added TimaKesytore provider
,D/dalvikvm( 7601): GC_CONCURRENT freed 2997K, 32% free 9570K/13876K, paused 3ms+3ms, total 28ms
,D/dalvikvm( 7601): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/UserAnalysis.PlaceProvider( 7601): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7601): Create SecureDbHelper
,E/SQLiteDatabase( 7601): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7601): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7601): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7601): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7601): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7601): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7601): Opened privacy in read-only mode
E/SQLiteDatabase( 7601): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7601): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7601): 	at dalvik.system.NativeStart.main(Native Method)
E/SQLiteOpenHelper( 7601): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7601): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7601): 	at dalvik.system.NativeStart.main(Native Method)
W/SQLiteOpenHelper( 7601): Opened privacy in read-only mode
E/SQLiteDatabase( 7601): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7601): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7601): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7601): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7601): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7601): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7601): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7601): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 7601): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7601): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7601): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7601): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7601): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7601): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7601): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7601): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7601): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7601): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7601): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7601): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7601): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7601): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7601): 	at dalvik.system.NativeStart.main(Native Method)
,W/ContextImpl( 6356): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6440):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2403):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2403): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6732): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6732): The package(com.test.thalitest) removed
E/SQLiteDatabase( 6356): Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
E/SQLiteDatabase( 6356): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6356): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6356): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6356): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6356): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
E/SQLiteDatabase( 6356): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
E/SQLiteDatabase( 6356): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6356): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6356): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 6356): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 2403): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 6356): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 6356): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6356): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 6356): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6356): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6356): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6356): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2403): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 6356): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 6356): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 2403): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2403): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6356): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 6356): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6356): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6356): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6356): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/System.err( 2403): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2403): 	... 8 more
W/System.err( 2403): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
,W/System.err( 2403): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
,W/System.err( 2403): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2403): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2403): 	at dalvik.system.NativeStart.run(Native Method)
,W/System.err( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 2403): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
,W/System.err( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
,W/System.err( 2403): ,	... 8 more
,D/MagazineService::MagazineBroadcastReceiver( 6759): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
,I/MagazineService::MagazineService( 6759): [onHandleIntent] ACTION_PACKAGE_REMOVED,
,I/SELinux ( 7616): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7616):  
,E/SQLiteDatabase( 6759): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.,
E/SQLiteDatabase( 6759): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6759): ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6759): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6759): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6759): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6759): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6759): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6759): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6759): 	,at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6759): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6759): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 6759): threadid=10: thread exiting with uncaught exception (group=0x419bbc08),
E/AndroidRuntime( 6759): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6759): Process: com.samsung.android.magazine.service, PID: 6759
E/AndroidRuntime( 6759): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6759): 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6759): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6759): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6759): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
,E/AndroidRuntime( 6759): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6759): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6759): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6759): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6759): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6759): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6759): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6759): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 6759): Sending signal. PID: 6759 SIG: 9,
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system),
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/ActivityManager( 2403): Process com.samsung.android.magazine.service (pid 6759) (adj 5) has died.,
,I/SELinux ( 7616): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7616):  
I/SELinux ( 7616):  
I/SELinux ( 7616): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7616): >>>>> Normal User
,E/dalvikvm( 7616): >>>>> com.android.keychain [ userId:0 | appId:1000 ],
,E/SELinux ( 7616): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7616): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7616): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7616): Added TimaKesytore provider
,D/dalvikvm( 7616): GC_CONCURRENT freed 3007K, 32% free 9559K/13872K, paused 2ms+2ms, total 24ms,
,D/dalvikvm( 7616): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/ContextImpl( 7616): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 ,
,D/KidsModeInstallReceiver( 6785): onReceive intent data =  package:com.test.thalitest
,D/KidsPlatformStub( 6785): Package not found : com.sec.android.app.kidshome
E/SQLiteDatabase( 7616): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7616): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7616): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7616): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7616): threadid=10: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7616): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7616): Process: com.android.keychain, PID: 7616
E/AndroidRuntime( 7616): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7616): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7616): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7616): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7616): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7616): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7616): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7616): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7616): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7616): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7616): Sending signal. PID: 7616 SIG: 9
,W/System.err( 6824): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
W/System.err( 6824): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6824): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6824): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 6824): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6824): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 6824): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6824): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6824): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6824): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6824): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6824): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6824): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 6824): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3157): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3157): Clearing selected account for com.test.thalitest
I/ActivityManager( 2403): Process com.android.keychain (pid 7616) (adj 5) has died.
,E/SQLiteLog( 3157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,I/LocationSettingsChecker( 3157): Removing dialog suppression flag for package com.test.thalitest
,D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3157): Module APK com.google.android.play.games already loaded
,E/DriveAsyncService( 3157): disk I/O error (code 3850)
E/DriveAsyncService( 3157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3157): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3157): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3157): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3157): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3157): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3157): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3157): 	at java.lang.Thread.run(Thread.java:841)
,E/SQLiteDatabase( 3157): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3157): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3157): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3157): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3157): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3157): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 3157): Loading module com.google.android.gms.games from APK com.google.android.play.games
E/SQLiteDatabase( 3157): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getDa,tabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3157): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3157): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ChimeraModuleLdr( 3157): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 3157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 2849): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,D/AndroidRuntime( 2849): Shutting down VM
,W/dalvikvm( 2849): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
,E/SQLiteOpenHelper( 3157): Couldn't open metrics.db for writing (will try read-only):
E/SQLiteOpenHelper( 3157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 3157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 3157): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteOpenHelper( 3157): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteOpenHelper( 3157): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteOpenHelper( 3157): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteOpenHelper( 3157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteOpenHelper( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 3157): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 3157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/SQLiteOpenHelper( 3157): Opened metrics.db in read-only mode
,E/PhenotypeInitializer( 3157): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3157): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3157): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3157): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3157): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3157): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3157): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3157): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3157): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3157): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/ClearPendingStateOp( 3157): Runtime exception while performing operation
E/ClearPendingStateOp( 3157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
E/ClearPendingStateOp( 3157): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/ClearPendingStateOp( 3157): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/ClearPendingStateOp( 3157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearPendingStateOp( 3157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/ClearPendingStateOp( 3157): 	at java.lang.Thread.run(Thread.java:841)
D/gH_CompatibleDatabase( 3157): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,D/gH_CompatibleDatabase( 3157): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
,E/AndroidRuntime( 2849): FATAL EXCEPTION: main
E/AndroidRuntime( 2849): Process: com.google.process.gapps, PID: 2849
E/AndroidRuntime( 2849): java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 2849): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2849): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 2849): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 2849): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 2849): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 2849): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 2849): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 2849): Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 2849): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.br.a(SourceFile:310)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
E/AndroidRuntime( 2849): 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
E/AndroidRuntime( 2849): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 2849): 	... 10 more
F/ClearPendingStateOp( 3157): Killing (on development devices) due to RuntimeException
F/ClearPendingStateOp( 3157): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
F/ClearPendingStateOp( 3157): 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:471)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.k.a.b(SourceFile:283)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.k.a.delete(SourceFile:273)
F/ClearPendingStateOp( 3157): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
F/ClearPendingStateOp( 3157): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.appstate.service.d.a(SourceFile:111)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
F/ClearPendingStateOp( 3157): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPo,olExecutor.java:1112)
F/ClearPendingStateOp( 3157): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
F/ClearPendingStateOp( 3157): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
F/ClearPendingStateOp( 3157): 	at java.lang.Thread.run(Thread.java:841)
E/SQLiteLog( 3157): (8) statement aborts at 19: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
E/SQLiteLog( 3157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/GMPM-SVC( 3157): Task exception on worker thread: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850): com.google.android.gms.measurement.internal.e.b(SourceFile:321)
W/dalvikvm( 3157): threadid=49: thread exiting with uncaught exception (group=0x419bbc08)
E/SQLiteLog( 3157): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3157): threadid=51: thread exiting with uncaught exception (group=0x419bbc08)
D/gH_CompatibleDatabase( 3157): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/dalvikvm( 3157): threadid=47: thread exiting with uncaught exception (group=0x419bbc08)
I/Process ( 3157): Sending signal. PID: 3157 SIG: 9
,E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
I/Process ( 2849): Sending signal. PID: 2849 SIG: 9
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
,I/GAV2    ( 5627): Thread[main,5,main]: Unexpected disconnect.
E/SQLiteDatabase( 5536): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5536): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5536): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5536): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5536): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5536): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5536): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5536): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5536): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5536): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5536): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5536): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5536): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5536): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5536): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5536): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5536): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5536): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7645): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7645):  
,I/ActivityManager( 2403): Process com.google.android.gms (pid 3157) (adj 0) has died.
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
,I/ActivityManager( 2403): Process com.google.process.gapps (pid 2849) (adj 5) has died.
,I/SELinux ( 7645): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7645):  
I/SELinux ( 7645):  
,I/SELinux ( 7645): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7645): >>>>> Normal User
,E/dalvikvm( 7645): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7645): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7645): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7645): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7645): Added TimaKesytore provider
,D/dalvikvm( 7645): GC_CONCURRENT freed 3006K, 32% free 9568K/13876K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 7645): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Documents( 7645): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7645): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7645): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7645): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7645): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7645): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7645): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7645): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7645): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7645): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7645): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7645): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7645): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7645): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7645): Shutting down VM
,W/dalvikvm( 7645): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7645): FATAL EXCEPTION: main
E/AndroidRuntime( 7645): Process: com.android.documentsui, PID: 7645
E/AndroidRuntime( 7645): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7645): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7645): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7645): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7645): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7645): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7645): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7645): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7645): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7645): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7645): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7645): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7645): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7645): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7645): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7645): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7645): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7645): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7645): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7645): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7645): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7645): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7645): 	... 10 more
,I/SELinux ( 7659): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7659):  
,I/SELinux ( 7663): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7663):  
,I/ActivityManager( 2403): Killing 6810:com.sec.enterprise.knox.cloudmdm.smdms/u0a171 (adj 15): empty #43
,I/Process ( 7645): Sending signal. PID: 7645 SIG: 9,
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	,at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/SELinux ( 7668): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7668):  
,I/ActivityManager( 2403): Process com.android.documentsui (pid 7645) (adj 9) has died.
I/SELinux ( 7659): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7659):  
I/SELinux ( 7659):  
I/SELinux ( 7659): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7659): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7659): >>>>> Normal User
E/dalvikvm( 7659): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
E/SELinux ( 7659): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7663): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7663):  
I/SELinux ( 7663):  
,I/SELinux ( 7663): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7663): >>>>> Normal User
,E/dalvikvm( 7663): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7663): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7659): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7659): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7659): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7663): in addTimaSignatureService
,I/SELinux ( 7668): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7668):  
I/SELinux ( 7668):  
D/TimaKeyStoreProvider( 7663): Cannot add TimaSignature Service, License check Failed
,I/SELinux ( 7668): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
D/ActivityThread( 7663): Added TimaKesytore provider
E/dalvikvm( 7668): >>>>> Normal User
,E/dalvikvm( 7668): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7668): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7668): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7668): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7668): Added TimaKesytore provider
,D/dalvikvm( 7659): GC_FOR_ALLOC freed 3027K, 32% free 9542K/13876K, paused 23ms, total 23ms
,D/dalvikvm( 7659): GC_CONCURRENT freed 207K, 31% free 9584K/13876K, paused 4ms+3ms, total 29ms
,D/ExternalStorage( 7659): After updating volumes, found 1 active roots
,D/dalvikvm( 7663): GC_CONCURRENT freed 2940K, 31% free 9633K/13876K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7663): WAIT_FOR_CONCURRENT_GC blocked 26ms
,W/dalvikvm( 7663): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7663): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7663): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7663): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7663): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7663): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7663): install
,I/MultiDex( 7663): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,D/dalvikvm( 7668): GC_CONCURRENT freed 2986K, 31% free 9583K/13872K, paused 4ms+2ms, total 31ms
,D/dalvikvm( 7668): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/MultiDex( 7663): loading existing secondary dex files
,I/MultiDex( 7663): load found 3 secondary dex files
,I/MultiDex( 7663): install done
,I/Icing.InternalIcingCorporaProvider( 7668): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7701): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7701):  
,I/SELinux ( 7705): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7705):  
,D/LocationManagerService( 2403): getProviders()=[passive]
,I/SELinux ( 7701): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7701):  
I/SELinux ( 7701):  
,I/SELinux ( 7701): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7701): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7701): >>>>> Normal User
,E/dalvikvm( 7701): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7701): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,I/SELinux ( 7705): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7705):  
I/SELinux ( 7705):  
,I/SELinux ( 7705): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7705): >>>>> Normal User
,E/dalvikvm( 7705): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7705): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7701): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7701): Cannot add TimaSignature Service, License check Failed
,D/TimaKeyStoreProvider( 7705): in addTimaSignatureService
,D/ActivityThread( 7701): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7705): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7705): Added TimaKesytore provider
,D/dalvikvm( 7701): GC_CONCURRENT freed 2997K, 32% free 9568K/13868K, paused 4ms+2ms, total 35ms
,D/dalvikvm( 7701): WAIT_FOR_CONCURRENT_GC blocked 27ms
,D/dalvikvm( 7705): GC_CONCURRENT freed 2994K, 31% free 9581K/13876K, paused 4ms+2ms, total 32ms
,D/dalvikvm( 7705): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/GservicesProvider( 7705): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7705): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7705): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7705): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7705): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7705): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7705): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7705): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7705): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7705): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7705): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7705): Shutting down VM
,W/dalvikvm( 7705): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7705): FATAL EXCEPTION: main
E/AndroidRuntime( 7705): Process: com.google.process.gapps, PID: 7705
E/AndroidRuntime( 7705): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7705): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7705): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7705): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7705): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7705): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7705): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7705): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7705): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7705): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7705): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7705): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7705): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7705): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7705): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7705): 	... 12 more
,I/Process ( 7705): Sending signal. PID: 7705 SIG: 9
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/ActivityManager( 2403): Process com.google.process.gapps (pid 7705) (adj 0) has died.
,W/ActivityManager( 2403): Service crashed 2 times, stopping: ServiceRecord{4340fd68 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 7735): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7735):  
,D/dalvikvm( 1923): GC_EXPLICIT freed 43K, 13% free 9503K/10848K, paused 3ms+4ms, total 34ms
,I/SELinux ( 7735): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7735):  
I/SELinux ( 7735):  
,I/SELinux ( 7735): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7735): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7735): >>>>> Normal User
,E/dalvikvm( 7735): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7735): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 4ms+3ms, total 30ms
,D/TimaKeyStoreProvider( 7735): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7735): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7735): Added TimaKesytore provider
,D/dalvikvm( 1923): GC_EXPLICIT freed <1K, 13% free 9503K/10848K, paused 3ms+4ms, total 30ms
,D/dalvikvm( 7735): GC_CONCURRENT freed 2987K, 31% free 9582K/13872K, paused 2ms+1ms, total 24ms
,D/dalvikvm( 7735): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/GservicesProvider( 7735): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7735): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7735): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7735): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7735): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7735): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7735): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7735): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7735): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7735): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7735): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7735): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7735): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7735): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7735): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7735): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7735): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7735): Shutting down VM
,W/dalvikvm( 7735): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7735): FATAL EXCEPTION: main
E/AndroidRuntime( 7735): Process: com.google.process.gapps, PID: 7735
E/AndroidRuntime( 7735): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7735): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7735): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7735): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7735): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7735): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7735): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7735): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7735): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7735): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7735): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7735): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7735): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7735): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7735): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7735): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7735): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7735): 	... 12 more
W/ActivityManager( 2403): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2403): Killing 7735:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2403): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app beca,me null
W/ActivityManager( 2403): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7701): Failed to find provider info for com.google.android.gsf.gservices
W/ActivityManager( 2403): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7668): Failed to find provider info for com.google.settings
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
E/ActivityThread( 7663): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 7751): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7751):  
,I/SELinux ( 7751): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7751):  
I/SELinux ( 7751):  
,I/SELinux ( 7751): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7751): >>>>> Normal User
,E/dalvikvm( 7751): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7751): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7751): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7751): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7751): Added TimaKesytore provider
,D/dalvikvm( 7751): GC_CONCURRENT freed 2990K, 31% free 9579K/13872K, paused 3ms+2ms, total 24ms
,D/dalvikvm( 7751): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/GservicesProvider( 7751): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7751): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7751): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7751): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7751): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7751): Shutting down VM
,W/dalvikvm( 7751): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
,E/AndroidRuntime( 7751): FATAL EXCEPTION: main
E/AndroidRuntime( 7751): Process: com.google.process.gapps, PID: 7751
E/AndroidRuntime( 7751): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7751): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7751): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7751): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7751): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7751): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7751): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7751): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7751): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7751): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7751): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7751): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7751): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7751): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7751): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7751): 	... 12 more
,I/Process ( 7751): Sending signal. PID: 7751 SIG: 9
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/ActivityManager( 2403): Process com.google.process.gapps (pid 7751) (adj 0) has died.
,I/SELinux ( 7766): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7766):  
,I/SELinux ( 7766): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7766):  
I/SELinux ( 7766):  
,I/SELinux ( 7766): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7766): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7766): >>>>> Normal User
,E/dalvikvm( 7766): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7766): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7766): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7766): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7766): Added TimaKesytore provider
,D/dalvikvm( 7766): GC_CONCURRENT freed 2987K, 31% free 9586K/13876K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7766): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/GservicesProvider( 7766): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7766): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7766): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7766): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7766): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7766): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7766): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7766): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7766): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7766): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7766): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7766): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7766): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7766): Shutting down VM
,W/dalvikvm( 7766): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7766): FATAL EXCEPTION: main
E/AndroidRuntime( 7766): Process: com.google.process.gapps, PID: 7766
E/AndroidRuntime( 7766): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7766): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7766): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7766): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7766): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7766): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7766): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7766): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7766): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7766): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7766): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7766): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7766): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7766): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7766): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7766): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7766): 	... 12 more
W/ActivityManager( 2403): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2403): Killing 7766:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2403): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launc,hing app became null
W/ActivityManager( 2403): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7701): Failed to find provider info for com.google.android.gsf.gservices
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop230.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,E/ActivityThread( 7663): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7663): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7663): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7663): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7663): VFY: unable to resolve instance field 36
D/dalvikvm( 7663): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7663): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7663): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7663): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7663): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7663): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7663): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42443d20
,I/ActivityManager( 2403): Killing 5666:com.android.mms/u0a49 (adj 15): empty #43
D/dalvikvm( 7663): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42443d20
D/dalvikvm( 7663): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42443d20, skipping init
W/dalvikvm( 2959): threadid=13: thread exiting with uncaught exception (group=0x419bbc08)
,D/dalvikvm( 7663): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42443d20
E/AndroidRuntime( 2959): FATAL EXCEPTION: ContactsProviderWorker
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
D/dalvikvm( 7663): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42443d20
,V/JNIHelp ( 7663): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Process ( 2959): Sending signal. PID: 2959 SIG: 9
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop231.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
D/CountryDetector( 2403): No listener is left
,I/ActivityManager( 2403): Process android.process.acore (pid 2959) (adj -12) has died.
,I/SELinux ( 7782): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7782):  
,D/dalvikvm( 7663): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x42443d20
,D/dalvikvm( 7663): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x42443d20
D/dalvikvm( 7663): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x42443d20
,D/dalvikvm( 7663): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42443d20
,I/SELinux ( 7782): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7782):  
I/SELinux ( 7782):  
,I/SELinux ( 7782): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7782): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7782): >>>>> Normal User
,E/dalvikvm( 7782): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 7782): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 7782): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7782): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7782): Added TimaKesytore provider
,I/ProviderInstaller( 7663): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 7794): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7794):  
,D/dalvikvm( 7782): GC_CONCURRENT freed 2998K, 31% free 9577K/13876K, paused 2ms+2ms, total 31ms
,D/dalvikvm( 7782): WAIT_FOR_CONCURRENT_GC blocked 29ms
,I/SELinux ( 7794): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7794):  
I/SELinux ( 7794):  
,I/SELinux ( 7794): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7794): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7794): >>>>> Normal User
,E/dalvikvm( 7794): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7794): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7794): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7794): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7794): Added TimaKesytore provider
,D/dalvikvm( 7794): GC_CONCURRENT freed 3002K, 32% free 9572K/13876K, paused 3ms+2ms, total 26ms
,D/dalvikvm( 7794): WAIT_FOR_CONCURRENT_GC blocked 23ms
,E/SQLiteDatabase( 7782): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7782): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7782): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7782): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7782): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 7782): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 7782): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7782): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7782): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7782): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 7782): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 7782): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 7782): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 7782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7782): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 7782): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 7782): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 7782): (14) unable to open database file
E/SQLiteDatabase( 7782): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 7782): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 7782): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 7782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7782): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7782): threadid=13: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7782): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 7782): Process: android.process.acore, PID: 7782
E/AndroidRuntime( 7782): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 7782): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 7782): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 7782): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 7782): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 7782): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 7782): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7782): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7782): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 7782): Sending signal. PID: 7782 SIG: 9
W/ActivityManager( 2403): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop232.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/ActivityManager( 2403): Process android.process.acore (pid 7782) (adj -12) has died.
,F/ActivityManager( 2403): Service ServiceRecord{44a98b90 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{42614960 7782:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2403): Can't write: system_server_wtf
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop16.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2403): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2403): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2403): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2403): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2403): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2403): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 18 more
,I/SELinux ( 7812): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7812):  
,I/GservicesProvider( 7794): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 7794): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 7794): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7794): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 7794): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 7794): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 7794): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 7794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7794): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7794): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7794): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7794): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7794): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7794): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7794): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7794): Shutting down VM
,W/dalvikvm( 7794): threadid=1: thread exiting with uncaught exception (group=0x419bbc08)
E/AndroidRuntime( 7794): FATAL EXCEPTION: main
E/AndroidRuntime( 7794): Process: com.google.process.gapps, PID: 7794
E/AndroidRuntime( 7794): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 7794): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7794): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7794): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7794): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7794): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7794): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7794): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7794): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7794): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7794): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7794): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7794): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 7794): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 7794): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 7794): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 7794): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 7794): 	... 12 more
,I/Process ( 7794): Sending signal. PID: 7794 SIG: 9
E/DropBoxManagerService( 2403): Can't write: system_app_crash
E/DropBoxManagerService( 2403): java.io.FileNotFoundException: /data/system/dropbox/drop234.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2403): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2403): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2403): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2403): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2403): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2403): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2403): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2403): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2403): 	... 5 more
,I/ActivityManager( 2403): Process com.google.process.gapps (pid 7794) (adj 0) has died.
I/SELinux ( 7812): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7812):  
I/SELinux ( 7812):  
I/SELinux ( 7812): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7812): >>>>> Normal User
E/dalvikvm( 7812): >>>>> android.process.acore [ userId:0 | appId:10020 ]
E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = shared
I/SELinux ( 7822): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7822):  
,D/TimaKeyStoreProvider( 7812): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7812): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7812): Added TimaKesytore provider
,I/SELinux ( 7822): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7822):  
I/SELinux ( 7822):  
,I/SELinux ( 7822): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7822): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7822): >>>>> Normal User
,E/dalvikvm( 7822): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 7822): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7822): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7822): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7822): Added TimaKesytore provider
,D/dalvikvm( 7812): GC_CONCURRENT freed 2981K, 31% free 9587K/13872K, paused 3ms+2ms, total 35ms
,D/dalvikvm( 7812): WAIT_FOR_CONCURRENT_GC blocked 25ms

```
