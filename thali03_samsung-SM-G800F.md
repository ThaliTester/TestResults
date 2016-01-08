#### Test 54970261e0c50c1_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
D/AmoledAdjustTimer( 2419): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,--------- beginning of /dev/log/main
D/AndroidRuntime( 7493): 
D/AndroidRuntime( 7493): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7493): CheckJNI is OFF
D/AndroidRuntime( 7493): setted country_code = Poland
D/AndroidRuntime( 7493): setted countryiso_code = PL
D/AndroidRuntime( 7493): setted sales_code = PLS
D/AndroidRuntime( 7493): readGMSProperty: start
D/AndroidRuntime( 7493): readGMSProperty: already setted!!
D/AndroidRuntime( 7493): readGMSProperty: end
D/AndroidRuntime( 7493): addProductProperty: start
D/dalvikvm( 7493): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7493): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7493): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7493): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7493): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7493): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7493): failed to load memtrack module: -2
D/dalvikvm( 7493): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7493): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2419): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=19 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=20 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7521): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7521):  
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7493): Shutting down VM
D/dalvikvm( 7493): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 0ms+0ms, total 3ms
I/SELinux ( 7521): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7521):  
I/SELinux ( 7521):  
I/SELinux ( 7521): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7521): >>>>> Normal User
E/dalvikvm( 7521): >>>>> com.test.thalitest [ userId:0 | appId:10599 ]
E/SELinux ( 7521): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7521): in addTimaSignatureService
D/TimaKeyStoreProvider( 7521): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7521): Added TimaKesytore provider
V/WindowManager( 2419): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4170): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4170): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2765): onTrimMemory. Level: 20
D/dalvikvm( 7521): GC_CONCURRENT freed 3014K, 32% free 9560K/13948K, paused 2ms+1ms, total 17ms
D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7521): Binding Chromium to the background looper Looper (main, tid 1) {422a5398}
I/chromium( 7521): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7521): Initializing chromium process, renderers=0
W/chromium( 7521): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7521): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7521): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7521): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7521): Mali API Version : 401
I/Mali    ( 7521): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
I/dalvikvm( 7521): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7521): VFY: unable to resolve virtual method 250: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7521): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7521): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7521): VFY: unable to resolve virtual method 245: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 7521): VFY: replacing opcode 0x6e at 0x0008
D/StatusBarManagerService( 2419): tr p:7521,o:f
D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
W/dalvikvm( 7521): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 7521): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7521): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7521): VFY: unable to resolve virtual method 303: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 7521): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 7521): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7521): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7521): VFY: unable to resolve virtual method 261: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 7521): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7521): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7521): VFY: unable to resolve virtual method 266: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 7521): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 7521): CordovaWebView is running on device made by: samsung
D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:7521,o:f
I/SurfaceFlinger( 1920): id=21 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
I/HWUI    ( 7521): EGLImpl-HWUI Protected EGL context created
D/OpenGLRenderer( 7521): Enabling debug mode 0
W/AwContents( 7521): nativeOnDraw failed; clearing to background color.
W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/IInputConnectionWrapper( 7521): showStatusIcon on inactive InputConnection
D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2419): mDVFSHelper.release()
D/CustomFrequencyManagerService( 2419): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  pkgName : ACTIVITY_RESUME_BOOSTER@8
D/JsMessageQueue( 7521): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 7521): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229e300
D/dalvikvm( 7521): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4229e300
D/jxcore_app_log( 7521): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2027580880
D/JX-Cordova( 7521): jxcore cordova android initializing
,D/dalvikvm( 7521): GC_CONCURRENT freed 1265K, 19% free 11367K/14004K, paused 2ms+2ms, total 23ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 12ms
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7521): GC_CONCURRENT freed 1934K, 19% free 14958K/18284K, paused 1ms+2ms, total 39ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 32ms
,D/CustomFrequencyManagerService( 2419): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2419  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7521): GC_FOR_ALLOC freed 5292K, 30% free 16233K/23144K, paused 51ms, total 51ms
,D/dalvikvm( 7521): GC_CONCURRENT freed 6710K, 32% free 17694K/25796K, paused 2ms+9ms, total 67ms
,D/dalvikvm( 7521): WAIT_FOR_CONCURRENT_GC blocked 37ms
,D/dalvikvm( 7521): GC_FOR_ALLOC freed 1051K, 32% free 17684K/25796K, paused 39ms, total 39ms
,I/dalvikvm-heap( 7521): Grow heap (frag case) to 22.125MB for 3688532-byte allocation
,D/dalvikvm( 7521): GC_FOR_ALLOC freed 2402K, 36% free 18883K/29400K, paused 37ms, total 37ms
,W/jxcore-log( 7521): Initializing JXcore engine
,W/jxcore-log( 7521): JXcore engine is ready
,W/jxcore-log( 7521): Starting JXcore engine
,W/jxcore-log( 7521): Platform android
W/jxcore-log( 7521): 
,W/jxcore-log( 7521): Process ARCH arm
W/jxcore-log( 7521): 
,I/jxcore-log( 7521): JXcore Cordova bridge is ready!
I/jxcore-log( 7521): 
,W/jxcore-log( 7521): JXcore engine is started
,I/chromium( 7521): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 7521): Toggling radios to true
I/jxcore-log( 7521): 
,D/BluetoothAdapter( 7521): enable(): BT is already enabled..!
,I/WifiManager( 7521): packageName : com.test.thalitest
,I/WifiManager( 7521): setWifiEnabled : true
,I/WifiService( 2419): setWifiEnabled: true pid=7521, uid=10599
W/ActivityManager( 2419): Permission Denial: getCurrentUser() from pid=7521, uid=10599 requires android.permission.INTERACT_ACROSS_USERS
,W/WifiService( 2419): Failed getting userId using ActivityManagerNative
W/WifiService( 2419): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7521, uid=10599 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2419): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2419): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2419): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
,I/WifiService( 2419): disconnect: pid=7521, uid=10599
,I/jxcore-log( 7521): Radios toggled
I/jxcore-log( 7521): 
,I/wpa_supplicant( 3974): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
,I/wpa_supplicant( 3974): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 320, Delta = 10
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3974): reset timer : RESET_TIMER 0
I/wpa_supplicant( 3974): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3974): Disconnected - do not scan
,W/Settings( 2419): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2419): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/CommandListener( 1914): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/ConnectivityService( 2419): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
E/ConnectivityService( 2419): net.tcp.usercfg.default not found in system default properties
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
I/wpa_supplicant( 3974): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3974): First Scan Start
E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2419): net.tcp.delack.default not found in system default properties
,E/ConnectivityService( 2419): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
,I/wpa_supplicant( 3974): Scan requested (ret=0) - scan timeout 30 seconds
D/ConnectivityService( 2419): Attempting to switch to mobile
D/ConnectivityService( 2419): Attempting to switch to BLUETOOTH_TETHER
D/WifiP2pService( 2419): InactiveState{ what=143375 }
D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,D/STATUSBAR-IconMerger( 2578): checkOverflow(336), More:false, Req:false Child:3
I/SELinux ( 7567): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7567):  
,D/CommandListener( 1914): Clearing all IP addresses on wlan0
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1914): /system/bin/ip -6 route del default table 2 2>&1
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip -6 rule del table 2 2>&1
,I/SELinux ( 7567): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7567):  
I/SELinux ( 7567):  
,I/SELinux ( 7567): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7567): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7567): >>>>> Normal User
,E/dalvikvm( 7567): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
,E/SELinux ( 7567): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-115ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-114ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,W/NetworkManagementService( 2419): route cmd failed: 
W/NetworkManagementService( 2419): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 route del src v6 2' failed with '400 37 -6 rule del table 2: RTNETLINK answers: No such file or directory
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
,V/RouteController( 1914): /system/bin/ip -4 route del default table 2 2>&1
,D/TimaKeyStoreProvider( 7567): in addTimaSignatureService
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,V/RouteController( 1914): RTNETLINK answers: No such process
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7567): Cannot add TimaSignature Service, License check Failed
,E/WifiStateMachine( 2419): Error! unhandled message{ when=-6ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/ActivityThread( 7567): Added TimaKesytore provider
,D/NetUtils( 2419): android_net_utils_resetConnections in env=0x78cffee0 clazz=0x62a00001 iface=wlan0 mask=0x3
D/ConnectivityService( 2419): resetConnections(wlan0, 3)
,E/SPPClientService( 5549): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,V/NativeCrypto( 2847): Read error: ssl=0x7c19f008: I/O error during system call, Connection timed out
,D/dalvikvm( 7567): GC_CONCURRENT freed 2994K, 32% free 9574K/13944K, paused 4ms+2ms, total 27ms
,D/dalvikvm( 7567): WAIT_FOR_CONCURRENT_GC blocked 15ms
,E/SPPClientService( 5549): [e] exceptionCaught(). NET_TIMEOUT
,V/NativeCrypto( 2847): SSL shutdown failed: ssl=0x7c19f008: I/O error during system call, Broken pipe
,E/SPPClientService( 5549): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5549): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5549): [b] ResponseMap empty
,D/ConnectivityService( 2419): handleInetConditionChange: no active default network - ignore
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked(flags=0x1)
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/System.out( 7567): Inside WakeupProvider
,V/NetworkStats( 2419): performPollLocked() took 26ms
I/System.out( 7567): Inside onCreate() of WakeupTriggerProvide
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,I/VlingoApplication( 7567): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7567): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7567): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4723): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2419): Killing 6424:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 15): empty #43
,D/DialogFlow( 7567): initQueue()
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 4723): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 4723): MountReceiver.mPrefHandler - 7002
,I/ApplicationPolicy( 2419): updateDataUsageMap
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/PCWCLIENTTRACE_PushUtil( 6667): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 6667): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6667): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6667): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6667): noConnectivity : true
,I/DBG_DM  ( 4764): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
,I/SELinux ( 7599): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7599):  
,I/wpa_supplicant( 3974): nl80211: Received scan results (9 BSSes)
I/wpa_supplicant( 3974): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3974): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,I/SELinux ( 7599): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7599):  
I/SELinux ( 7599):  
,I/SELinux ( 7599): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7599): >>>>> Normal User
,E/dalvikvm( 7599): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ]
,E/SELinux ( 7599): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7599): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7599): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7599): Added TimaKesytore provider
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,I/wpa_supplicant( 3974): Associated with C0.AA.48
I/wpa_supplicant( 3974): freq(2412) increment count 2
,I/wpa_supplicant( 3974): meet head of list.
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true,
D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true,
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3974): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 3974): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
,I/wpa_supplicant( 3974): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/Tethering( 2419): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2419): interfaceStatusChanged wlan0, true
,D/WifiNative( 2419): callSECApiVoid - ID [50]
,D/dalvikvm( 7599): GC_CONCURRENT freed 2997K, 32% free 9567K/13944K, paused 3ms+2ms, total 44ms
,D/dalvikvm( 7599): WAIT_FOR_CONCURRENT_GC blocked 26ms
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
,I/ActivityManager( 2419): Killing 6514:com.sec.android.Kies/1000 (adj 15): empty #43
,I/SELinux ( 7611): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7611):  
,I/SELinux ( 7611): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7611):  
I/SELinux ( 7611):  
,I/SELinux ( 7611): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7611): >>>>> Normal User
,E/dalvikvm( 7611): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ]
,E/SELinux ( 7611): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7611): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7611): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7611): Added TimaKesytore provider
,D/dalvikvm( 7611): GC_CONCURRENT freed 3001K, 32% free 9567K/13940K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 7611): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/KLMS-2.3.201 : ( 7611): KLMSValidator() : checkQATesting()
,I/KLMS-2.3.201 : ( 7611): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452274649635
,I/KLMS-2.3.201 : ( 7611): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false
,I/dhcpcd  ( 7623): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7623): bssid match
I/ActivityManager( 2419): Killing 6316:com.sec.phone/1001 (adj 15): empty #43
,I/SELinux ( 7630): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7630):  
,I/SELinux ( 7630): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7630):  
I/SELinux ( 7630):  
,I/SELinux ( 7630): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7630): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7630): >>>>> Normal User
,E/dalvikvm( 7630): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ]
,E/SELinux ( 7630): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7630): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7630): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7630): Added TimaKesytore provider
,D/dalvikvm( 7630): GC_CONCURRENT freed 3005K, 32% free 9567K/13944K, paused 2ms+1ms, total 22ms
,D/dalvikvm( 7630): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/SO_AGENT( 7630): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7630): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5813): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5813): [BDLM] already registered in spp
,I/SA      ( 5813): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5813): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5813): [OR] == isSIMCardReady false ==
,I/SA      ( 5813): [SCU] == networkStateCheck == false
,I/SA      ( 5813): [OR] onReceive END
I/ActivityManager( 2419): Killing 6339:com.sec.android.app.videoplayer/u0a53 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6579): Other Intent
,I/SELinux ( 7642): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7642):  
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout,
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...,
I/SELinux ( 7642): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7642):  
I/SELinux ( 7642):  
,I/SELinux ( 7642): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7642): >>>>> Normal User
,E/dalvikvm( 7642): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7642): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7642): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7642): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7642): Added TimaKesytore provider
,D/dalvikvm( 7642): GC_FOR_ALLOC freed 3009K, 32% free 9558K/13944K, paused 17ms, total 17ms
,D/dalvikvm( 7642): GC_CONCURRENT freed 226K, 32% free 9570K/13944K, paused 1ms+8ms, total 21ms,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager,
,D/com.samsung.app( 7642): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7642): [KK AccuPhone]>>> RM:136 [0:0]  V init ,
,D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/com.samsung.app( 7642): [KK AccuPhone]>>> RM:128 [0:0] updateCityList,
,D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo,
,D/com.samsung.app( 7642): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0,
,D/daemonapp( 5344): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!,
I/ActivityManager( 2419): Killing 6527:com.android.chrome/u0a85 (adj 15): empty #43
,D/Headlines( 5881): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE,
,D/HeadlinesChannelUtil( 5881): getCountryCode(): countryCode = PL,
,D/Headlines( 5881): Breath.onCreate,
,D/Headlines( 5881): Breath timer started. interval : 30000,
,I/SELinux ( 7654): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7654):  
D/Headlines( 5881): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5881): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5881): requestUpdateNewsWelcomeCard : request update welcome card to content card.
D/HeadlinesDataCenter( 5881): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2419): waitForAlarm result :8
,I/SELinux ( 7654): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7654):  
I/SELinux ( 7654):  
,I/SELinux ( 7654): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7654): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7654): >>>>> Normal User
,E/dalvikvm( 7654): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7654): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7654): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7654): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7654): Added TimaKesytore provider
,D/dalvikvm( 7654): GC_CONCURRENT freed 2988K, 32% free 9573K/13940K, paused 2ms+1ms, total 19ms
,D/dalvikvm( 7654): WAIT_FOR_CONCURRENT_GC blocked 16ms
,V/WebViewChromium( 7654): Binding Chromium to the background looper Looper (main, tid 1) {422aae30}
,I/chromium( 7654): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7654): Initializing chromium process, renderers=0
,W/chromium( 7654): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7654): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7654): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7654): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7654): Mali API Version : 401
,I/Mali    ( 7654): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,W/GAV2    ( 7654): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.,
,E/cutils  ( 1910): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
,W/Vold    ( 1910): Returning OperationFailed - no handler for errno 30
W/ContextImpl( 7654): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,I/NSApplication( 7654): Starting up...
,D/WifiP2pService( 2419): InactiveState{ what=143375 }
,D/WifiP2pService( 2419): P2pEnabledState{ what=143375 }
I/iu.Environment( 5945): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,D/WifiStateMachine( 2419): VerifyingLinkState enter
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
I/iu.UploadsManager( 5945): num queued entries: 0
I/iu.UploadsManager( 5945): num updated entries: 0
,D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE,
I/iu.SyncManager( 5945): NEXT; no task
,D/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b06c8,
,I/SELinux ( 7713): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7713):  
,D/WifiStateMachine( 2419): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2419): CaptivePortalCheckState enter,
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
D/ConnectivityService( 2419): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2419): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,I/WifiTrafficPoller( 2419): evaluateTrafficStatsPolling
,D/ConnectivityService( 2419): ConnectivityChange for WIFI: CONNECTED/CONNECTED
I/SELinux ( 7713): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7713):  
I/SELinux ( 7713):  
I/SELinux ( 7713): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7713): >>>>> Normal User
,E/dalvikvm( 7713): >>>>> com.android.email [ userId:0 | appId:10157 ]
,E/SELinux ( 7713): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/STATUSBAR-NetworkController( 2578): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
E/ConnectivityService( 2419): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2419): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2578): refreshSignalCluster: data=-1 bt=false
,D/TimaKeyStoreProvider( 7713): in addTimaSignatureService
D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/TimaKeyStoreProvider( 7713): Cannot add TimaSignature Service, License check Failed
,V/RouteController( 1914): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,D/ActivityThread( 7713): Added TimaKesytore provider
,V/RouteController( 1914): /system/bin/ip -4 rule del table 2 2>&1,
,V/RouteController( 1914): RTNETLINK answers: No such file or directory
,V/RouteController( 1914): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1914): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1,
,V/RouteController( 1914): RTNETLINK answers: No such process,
,V/RouteController( 1914): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,V/RouteController( 1914): /system/bin/ip route flush cached 2>&1,
,V/NetworkStats( 2419): updateIfacesLocked()
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/dalvikvm( 7713): GC_CONCURRENT freed 2985K, 32% free 9583K/13944K, paused 4ms+2ms, total 28ms
,D/dalvikvm( 7713): WAIT_FOR_CONCURRENT_GC blocked 23ms
,V/NetworkStats( 2419): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,V/NetworkStats( 2419): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
V/NetworkStats( 2419): performPollLocked() took 18ms
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2419): currentTimeMillis() cache hit
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId,
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId,
,I/SELinux ( 7747): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7747):  
I/ActivityManager( 2419): Killing 6543:com.google.android.apps.uploader/u0a117 (adj 15): empty #43
,W/ActivityManager( 2419): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found,
I/SELinux ( 7747): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7747):  
I/SELinux ( 7747):  
I/SELinux ( 7747): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7747): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7747): >>>>> Normal User
,E/dalvikvm( 7747): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
E/SELinux ( 7747): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/SELinux ( 7757): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7757):  
,D/TimaKeyStoreProvider( 7747): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7747): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7747): Added TimaKesytore provider,
,I/ActivityManager( 2419): Killing 6384:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43,
,I/SELinux ( 7757): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7757):  
I/SELinux ( 7757):  
I/SELinux ( 7757): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7757): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7757): >>>>> Normal User
,E/dalvikvm( 7757): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ],
,E/SELinux ( 7757): [DEBUG] seapp_context_lookup: seinfoCategory = shared,
,D/TimaKeyStoreProvider( 7757): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7757): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7757): Added TimaKesytore provider
,D/dalvikvm( 7747): GC_CONCURRENT freed 2996K, 32% free 9567K/13940K, paused 3ms+1ms, total 32ms
,D/dalvikvm( 7747): WAIT_FOR_CONCURRENT_GC blocked 28ms
,D/BadgeProvider( 7747): onCreate
,D/BadgeProvider( 7747): DatabaseHelper
,D/BadgeProvider( 7747): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
D/dalvikvm( 7757): GC_CONCURRENT freed 3000K, 32% free 9567K/13944K, paused 3ms+1ms, total 23ms
,D/dalvikvm( 7757): WAIT_FOR_CONCURRENT_GC blocked 7ms
,D/BadgeProvider( 7747): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7747): sendNotify, [notify] : null
D/BadgeProvider( 7747): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7747): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 7747): update, [UpdateCount] : 1
,D/Launcher.Model( 2765): reloadBadges entered.
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,E/SPPClientService( 5549): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5549): [SystemStateMoniter] Current Time : 310538
,E/SPPClientService( 5549): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5549): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,D/Tethering( 2419): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2419): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2419): NoActiveNetworkState{ when=-2ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2578): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2578): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2578): updateDataNetType()
,D/STATUSBAR-NetworkController( 2578): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4764): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,E/SPPClientService( 5549): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5549): [a] [ConnectionManager] Connection is already disconnected.
,I/ActivityManager( 2419): Killing 6002:com.android.calendar/u0a144 (adj 15): empty #43
D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection...
D/Headlines( 5881): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
,D/Headlines( 5881): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5881): Breath 1374 latestRequest time : 1452274650217 current time : 1452274651591
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,E/SPPClientService( 5549): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5549): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 4723): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 4723): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,I/SurfaceFlinger( 1920): id=22 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5549): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,E/SPPClientService( 5549): [a] [ConnectionManager] Connection is already disconnected.
,D/PowerManagerService( 2419): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419
,D/NearbySettings( 4723): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
E/SPPClientService( 5549): [g] getNetMCC return empty string
,I/NearbySettings( 4723): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6667): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6667): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6667): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6667): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/dalvikvm( 2419): GC_EXPLICIT freed 3979K, 56% free 24992K/55956K, paused 6ms+18ms, total 184ms
,I/KLMS-2.3.201 : ( 7611): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7611): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1452274652098
,I/KLMS-2.3.201 : ( 7611): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7630): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7630): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/LocationTagReadyService( 3414): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3414): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3414): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3414): [Slink platform] The state of Slink geocode service is true
,I/SELinux ( 7783): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7783):  
,I/GallerySearchProvider( 3558): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,I/SELinux ( 7783): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7783):  
I/SELinux ( 7783):  
,I/SELinux ( 7783): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7783): >>>>> Normal User
,E/dalvikvm( 7783): >>>>> com.sec.android.app.videoplayer [ userId:0 | appId:10053 ]
,E/SELinux ( 7783): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 13% free 9504K/10924K, paused 3ms+5ms, total 35ms
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9504K/10924K, paused 2ms+3ms, total 26ms
,D/TimaKeyStoreProvider( 7783): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7783): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7783): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9504K/10924K, paused 2ms+3ms, total 26ms
,I/SELinux ( 7795): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7795):  
,I/SELinux ( 7795): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7795):  
I/SELinux ( 7795):  
I/SELinux ( 7795): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7795): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7795): >>>>> Normal User
,E/dalvikvm( 7795): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ],
E/SELinux ( 7795): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SA      ( 5813): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5813): [BDLM] already registered in spp
,I/SA      ( 5813): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5813): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,D/TimaKeyStoreProvider( 7795): in addTimaSignatureService
,I/SA      ( 5813): [OR] == isSIMCardReady false ==
,D/TimaKeyStoreProvider( 7795): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7795): Added TimaKesytore provider
,I/SA      ( 5813): [SCU] == networkStateCheck == true
,I/SA      ( 5813): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5813): isChinaCountryCode : false
,I/SA      ( 5813): [OR] == networkStateCheck true ==
,D/dalvikvm( 7783): GC_CONCURRENT freed 2997K, 32% free 9574K/13944K, paused 4ms+1ms, total 28ms
,D/dalvikvm( 7783): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/SA      ( 5813): [OR] GetMyCountryZoneTask
,I/SA      ( 5813): [OR] onReceive END
D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2749): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6579): Other Intent
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7642): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/dalvikvm( 7795): GC_CONCURRENT freed 3003K, 32% free 9572K/13948K, paused 4ms+1ms, total 50ms
,D/dalvikvm( 7795): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/SA      ( 5813): [SRS] prepareGetMyCountryZone
,I/SA      ( 5813): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5813): [SSP] query invoked
,D/Headlines( 5881): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5881): getCountryCode(): countryCode = PL
,V/KVNProvider( 7795): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7795): getFindoCursor query string : 
,I/SA      ( 5813): [TPMU] GetMccFromDB : null
,I/SA      ( 5813): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5813): [TPM] isNoProxy(default) : true
,I/SA      ( 5813): [RC New] Execute method=[GET] start
,D/Headlines( 5881): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5881): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5881): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5881): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5881): requestUpdateNewsWelcomeCard !!! no welcome card
,I/iu.Environment( 5945): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
I/QuickConnect[1.1][2] ( 5144): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5144): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@422b06c8
,I/iu.UploadsManager( 5945): num queued entries: 0
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,D/RCPManagerService( 2419): exchangeData() failure , invalid userId
,I/iu.UploadsManager( 5945): num updated entries: 0
,I/iu.SyncManager( 5945): NEXT; no task
,V/KVNProvider( 7795): getTagSearchCursor() tagSearchCursor count : 0
,D/hcjo    ( 5977): AutoUpdateManager:IDLE:execute
D/InitializeManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/InitializeManagerStateMachine( 5977): exit::IDLE
,D/InitializeManagerStateMachine( 5977): entry::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 5977): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 5977): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 5977): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 5977): entry::SUCCESS
,D/hcjo    ( 5977): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/libgps  ( 2419): agps_ril_update_network_state: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 5977): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
D/InitializeManagerStateMachine( 5977): exit::SUCCESS
,D/InitializeManagerStateMachine( 5977): entry::IDLE
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection...
,D/dalvikvm( 2720): GC_EXPLICIT freed 360K, 29% free 9971K/13932K, paused 8ms+7ms, total 186ms
,E/SPPClientService( 5549): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5549): [SystemStateMoniter] Current Time : 311744
,E/SPPClientService( 5549): [SystemStateMoniter] No Connect : false
,I/System.out( 7599): Thread-648(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 7599): Thread-648(ApacheHTTPLog):isShipBuild true
,I/System.out( 7599): Thread-648(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/dalvikvm( 5549): GC_CONCURRENT freed 1991K, 26% free 10436K/13924K, paused 5ms+3ms, total 40ms
,I/System.out( 7599): AsyncTask #1 calls detatch()
,W/System.err( 7599): com.sec.android.fota.osp.http.RestClientException
,W/System.err( 7599): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7599): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7599): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7599): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 7599): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7599): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7599): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7599): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7599): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7599): Caused by: java.lang.NullPointerException
,W/System.err( 7599): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7599): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7599): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
,W/System.err( 7599): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7599): 	... 8 more
,I/ActivityManager( 2419): Killing 6171:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/TimaService( 2419): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2419): TimaServiceHandler.handleMessage what =1
,D/TimaService( 2419): TIMA: checkEvent, operation: 50000 subject: 10000
I/TLC_TIMA_PKM_initialize( 2419): initializing...
I/TLC_TIMA_PKM_initialize( 2419): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2419): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2419): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2419): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2419): device_id = 0x0
I/TZ: mc_tlc_communication( 2419): tlc_open() was called
I/TZ: mc_tlc_communication( 2419): Opening MobiCore device
I/TZ: mc_tlc_communication( 2419): Allocating WSM for TCI
I/TZ: mc_tlc_communication( 2419): Opening the session
,I/TZ: mc_tlc_communication( 2419): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2419): Trustlet response is completed
,I/SA      ( 5813): [RC New] [v2liruge] api execute + 690
,I/SA      ( 5813): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,I/System.out( 5813): AsyncTask #2 calls detatch()
,I/SA      ( 5813): [TPMU] getNetworkMcc : 
,I/SA      ( 5813): [SCU] saveMccToPreferece Start
,I/SA      ( 5813): [SCU] RegionMCC : 260
,I/SA      ( 5813): [SSP] query invoked
,I/SA      ( 5813): [TPMU] GetMccFromDB : null
I/SA      ( 5813): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5813): [SCU] saveMccToPreferece End
,I/SA      ( 5813): [RC New] executeRequest [v2liruge] end. 716
,I/SA      ( 5813): [RC New] Execute end
,I/SA      ( 5813): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5813): [OR] GetMyCountryZoneTask Success
,D/PackageManager( 2419): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/libgps  ( 2419): agps_ril_update_network_availability: Waiting for IPC connection - timeout
,E/libgps  ( 2419): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2419): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/WifiP2pStateTracker( 2419): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2419): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2419):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2419): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2419): updateSourceRoutes : no source routing conditions
E/SPPClientService( 5549): [b] __InitReply__
,E/WifiStateMachine( 2419): CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (10/11)
,I/SurfaceFlinger( 1920): id=22 Removed Uoast (-2/11)
I/ActivityManager( 2419): Killing 5596:com.sec.android.widgetapp.activeapplicationwidget/u0a154 (adj 15): empty #43
D/PowerManagerService( 2419): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2419) eventTime = 314247
D/PowerManagerService( 2419): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2419 (0x0)
D/PowerManagerService( 2419): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2419, ws=WorkSource{1000}) (elapsedTime=3465)
,I/GAV2    ( 7654): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6667): mConnectivityHandler : connected
,W/PCWCLIENTTRACE_AccountUtil( 6667): [hasSamungAccount] - No Samsung Account
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6667): failed to loading secure library
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6667): [GetString-S]
,W/PCWCLIENTTRACE_SecurePreferencesJNI( 6667): GetString : secure API is not supported!!
I/PCWCLIENTTRACE_PushUtil( 6667): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6667): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6667): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6667): [ensureRegistration] - No Samsung account
,D/SSRMv2:SIOP( 2419): SIOP:: AP = 330, Delta = 10
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2419): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2419): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2419): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2419): stay LED for fully charged
,D/BatteryService( 2419): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2419): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2578): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2578): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2578):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2578): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2578): checkOverflow(288), More:false, Req:false Child:3
,E/Watchdog( 2419): !@Sync 10
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE
,D/CaptivePortalTracker( 2419): DelayedCaptiveCheckState{ when=-11ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2419): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2419): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2419): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2419): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker( 2419): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2419): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2419): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,I/jxcore-log( 7521): Test app app.js loaded
I/jxcore-log( 7521): 
,I/chromium( 7521): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7521): ****TEST TOOK:  ms ****
I/jxcore-log( 7521): 
,I/jxcore-log( 7521): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 7521): 
,D/AmoledAdjustTimer( 2419): prevTemp = 287, currTemp = 289, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 5977): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 5977): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 5977): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 5977): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 5977): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 5977): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 5977): entry::IDLE
,D/AndroidRuntime( 7830): 
D/AndroidRuntime( 7830): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 7830): CheckJNI is OFF
D/AndroidRuntime( 7830): setted country_code = Poland
,D/AndroidRuntime( 7830): setted countryiso_code = PL
D/AndroidRuntime( 7830): setted sales_code = PLS
D/AndroidRuntime( 7830): readGMSProperty: start
,D/AndroidRuntime( 7830): readGMSProperty: already setted!!
D/AndroidRuntime( 7830): readGMSProperty: end
,D/AndroidRuntime( 7830): addProductProperty: start
,D/dalvikvm( 7830): Trying to load lib libjavacore.so 0x0
,D/dalvikvm( 7830): Added shared lib libjavacore.so 0x0
,D/dalvikvm( 7830): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7830): Added shared lib libnativehelper.so 0x0
,D/dalvikvm( 7830): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,E/memtrack( 7830): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 7830): failed to load memtrack module: -2
,D/dalvikvm( 7830): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
,D/AndroidRuntime( 7830): Calling main entry com.android.commands.pm.Pm
,D/PackageManager( 2419): START PACKAGE DELETE: observer{1119819160}
D/PackageManager( 2419): pkg{<packageName>}
D/PackageManager( 2419): user{0}
,D/PackageManager( 2419): deletePackageAsUser : uid = 2000 userId = 0
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2419): getApplicationUninstallationEnabled :  enabled true
,D/PackageManagerService( 2419): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2419): [MSG] DELETE_PACKAGE_AS_USER
,D/PackageManager( 2419): !@killApplicatoin: 10599, uninstall pkg
,I/ActivityManager( 2419): Killing 7521:com.test.thalitest/u0a599 (adj 0): stop com.test.thalitest
,D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,I/SurfaceFlinger( 1920): id=20 Removed EimLayer (5/10)
I/SurfaceFlinger( 1920): id=20 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1920): id=19 Removed EimLayer (4/9)
,I/SurfaceFlinger( 1920): id=19 Removed EimLayer (-2/9)
,V/WindowManager( 2419): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false,
,D/Launcher( 2765): onRestart, Launcher: 1110309784,
D/Launcher( 2765): onStart, Launcher: 1110309784
,D/Launcher.HomeView( 2765): onStart
,I/SurfaceFlinger( 1920): id=21 Removed NainActivit (6/8)
,I/SurfaceFlinger( 1920): id=21 Removed NainActivit (-2/8),
,I/WindowState( 2419): WIN DEATH: Window{43089548 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=21 Removed NainActivit (-2/8)
,I/SurfaceFlinger( 1920): id=23 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/STATUSBAR-StatusBarManagerService( 2419): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2419): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2419): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2419): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2419): setHoveringSpenCustomIcon IconType is same.1
,D/StatusBarManagerService( 2419): tr p:2765,o:f
,D/PhoneStatusBar( 2578): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
,D/PhoneStatusBar( 2578): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2419): semi p:2765,o:f
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,W/InputMethodManagerService( 2419): Got RemoteException sending setActive(false) notification to pid 7521 uid 10599
,W/PackageSettings( 2419): Skipping PackageSetting{42824468 com.example.hello/10594} due to missing metadata
,D/PackageManager( 2419): checkUidPermission - Execution time: 172 ms
,D/PackageManager( 2419): checkUidPermission - Execution time: 124 ms
D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10599, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,D/dalvikvm( 6460): GC_EXPLICIT freed 561K, 29% free 9986K/14024K, paused 5ms+10ms, total 103ms
,D/dalvikvm( 6829): GC_EXPLICIT freed 160K, 30% free 9960K/14160K, paused 11ms+8ms, total 118ms
,I/FPMS_FingerprintManagerService( 2598): onReceive: android.intent.action.PACKAGE_REMOVED
,E/SamsungIME( 3001): mOCRHelper is null
,D/dalvikvm( 2954): GC_EXPLICIT freed 1469K, 29% free 10039K/13944K, paused 17ms+8ms, total 118ms
,D/PackageManager( 2419): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10599, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/QuickConnect[1.1][2] ( 5144): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
W/GeofencerStateMachine( 2732): Ignoring removeGeofence because network location is disabled.
,I/SELinux ( 7843): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7843):  
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 3153): GC_EXPLICIT freed 330K, 23% free 12401K/16060K, paused 14ms+117ms, total 230ms
,I/SELinux ( 7843): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7843):  
I/SELinux ( 7843):  
,I/SELinux ( 7843): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7843): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7843): >>>>> Normal User,
,E/dalvikvm( 7843): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
,E/SELinux ( 7843): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/TimaKeyStoreProvider( 7843): in addTimaSignatureService
,D/RegisteredServicesCache( 2754): empty dynamic service
,D/TimaKeyStoreProvider( 7843): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7843): Added TimaKesytore provider
,D/dalvikvm( 2419): GC_EXPLICIT freed 1991K, 56% free 25035K/55956K, paused 16ms+22ms, total 307ms
,D/dalvikvm( 2419): WAIT_FOR_CONCURRENT_GC blocked 96ms
,I/InputReader( 2419): Reconfiguring input devices.  changes=0x00000010
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mmsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/RCPManagerService( 2419): PackageReceiver onReceive()
,I/HarmonyEASService( 2419): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,D/dalvikvm( 7843): GC_CONCURRENT freed 2987K, 32% free 9574K/13940K, paused 22ms+2ms, total 59ms
,D/dalvikvm( 7843): WAIT_FOR_CONCURRENT_GC blocked 37ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,D/elm:14132( 7843): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Scheme: "mmsto"
D/elm:14132( 7843): ELMEngine.ELMEngine( context ).
D/elm:14132( 7843): MDMBridge.setEnterpriseBridge()
,D/dalvikvm( 2754): GC_CONCURRENT freed 2337K, 27% free 10258K/13964K, paused 16ms+4ms, total 160ms
,D/elm:14132( 7843): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,D/elm:14132( 7843): ElmAgentService : onCreate()
,I/SELinux ( 7856): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7856):  
,D/elm:14132( 7843): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132( 7843): MainReceiver.listeningToPackageRemoved()
D/elm:14132( 7843): MDMBridge.getInstance()
,D/elm:14132( 7843): MDMBridge.getAllLicenseInfoFromSDK()
,D/elm:14132( 7843): MDMBridge.getAllLicenseInfoFromSDK()
,I/SELinux ( 7856): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7856):  
I/SELinux ( 7856):  
,I/SELinux ( 7856): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7856): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7856): >>>>> Normal User
,E/dalvikvm( 7856): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
,E/SELinux ( 7856): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/EnterpriseDeviceManagerService( 2419): Package has changed for user 0
,D/TimaKeyStoreProvider( 7856): in addTimaSignatureService
,D/elm:14132( 7843): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
,D/elm:14132( 7843): ElmAgentService : onDestroy().
,D/TimaKeyStoreProvider( 7856): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7856): Added TimaKesytore provider
I/ActivityManager( 2419): Killing 6264:com.android.defcontainer/u0a6 (adj 15): empty #43
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/dalvikvm( 2419): GC_EXPLICIT freed 884K, 56% free 25102K/55956K, paused 15ms+39ms, total 564ms
,D/PackageManager( 2419): delete sourFile : 
,D/dalvikvm( 7856): GC_CONCURRENT freed 2998K, 32% free 9570K/13944K, paused 3ms+3ms, total 54ms
,D/dalvikvm( 7856): WAIT_FOR_CONCURRENT_GC blocked 50ms
,D/BackupManagerService( 2419): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,V/BackupManagerService( 2419): removePackageParticipantsLocked: uid=10599 #1
,D/PackageManager( 2419): delete native library directory: 
D/PackageManager( 2419): return delete result to caller: 1119819160
,D/AndroidRuntime( 7830): Shutting down VM
D/PackageManager( 2419): returnCode: 1
,D/dalvikvm( 7830): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 1ms+1ms, total 7ms
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "sms"
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "smsto"
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :,
I/SELinux ( 7874): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7874):  
,I/ActivityManager( 2419): Killing 6484:com.google.android.partnersetup/u0a14 (adj 15): empty #43
,I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
,I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
,I/PackageManager( 2419):   Scheme: "mms",
I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
I/SELinux ( 7874): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7874):  
I/SELinux ( 7874):  
,I/SELinux ( 7874): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2419):   Action: "android.intent.action.SENDTO"
E/dalvikvm( 7874): >>>>> Normal User
,E/dalvikvm( 7874): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
,I/PackageManager( 2419): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2419):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2419):   Scheme: "mmsto"
E/SELinux ( 7874): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7874): in addTimaSignatureService
,W/ApplicationsProvider( 2954): Could not fetch usage stats
W/ApplicationsProvider( 2954): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2954): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2954): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2954): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2954): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2954): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 7874): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7874): Added TimaKesytore provider
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 2419): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/dalvikvm( 7874): GC_CONCURRENT freed 3012K, 32% free 9559K/13944K, paused 5ms+2ms, total 40ms
,D/dalvikvm( 7874): WAIT_FOR_CONCURRENT_GC blocked 32ms
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SQLiteDatabase( 7874): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase( 7874): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7874): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7874): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase( 7874): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase( 7874): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7874): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7874): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7874): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7874): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7874): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7874): 	at dalvik.system.NativeStart.main(Native Method)
,D/AndroidRuntime( 7874): Shutting down VM
W/dalvikvm( 7874): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/AndroidRuntime( 7874): FATAL EXCEPTION: main
E/AndroidRuntime( 7874): Process: com.sec.android.app.mss, PID: 7874
E/AndroidRuntime( 7874): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7874): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7874): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7874): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7874): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7874): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7874): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7874): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7874): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7874): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7874): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7874): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7874): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7874): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7874): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7874): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7874): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime( 7874): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime( 7874): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7874): 	... 10 more
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop217.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
I/PCWCLIENTTRACE_PushUtil( 6667): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6667): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6667): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6667): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/Process ( 7874): Sending signal. PID: 7874 SIG: 9
I/ActivityManager( 2419): Process com.sec.android.app.mss (pid 7874) (adj 9) has died.
,E/SQLiteLog( 6016): (3850) statement aborts at 35: [DELETE FROM app_registry WHERE package_name=? AND plugin_id=? AND sync_status != 170004 AND sync_status = 170002] disk I/O error
,W/dalvikvm( 6016): threadid=12: thread exiting with uncaught exception (group=0x4180ac08)
,I/SA      ( 5813): [SUR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,E/AndroidRuntime( 6016): FATAL EXCEPTION: IntentService[HandleAppDataService]
E/AndroidRuntime( 6016): Process: com.sec.android.app.shealth, PID: 6016
E/AndroidRuntime( 6016): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:924)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
E/AndroidRuntime( 6016): 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1618)
E/AndroidRuntime( 6016): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericDelete(BaseContentProvider.java:486)
E/AndroidRuntime( 6016): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.delete(BaseContentProvider.java:441)
E/AndroidRuntime( 6016): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6016): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6016): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.deleteAppRegistryData(AppRegistryDbManagerWithProvider.java:459)
E/AndroidRuntime( 6016): 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:56)
E/AndroidRuntime( 6016): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6016): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6016): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6016): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SA      ( 5813): [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package ]
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop218.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/Process ( 6016): Sending signal. PID: 6016 SIG: 9
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/SharedPreferencesImpl( 3558): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/ActivityManager( 2419): Process com.sec.android.app.shealth (pid 6016) (adj 5) has died.
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/Icing.InternalIcingCorporaProvider( 6460): Updating corpora: A: com.test.thalitest, C: MAYBE
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/SQLiteLog( 6460): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,W/dalvikvm( 6460): threadid=15: thread exiting with uncaught exception (group=0x4180ac08)
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/AndroidRuntime( 6460): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 6460): Process: com.google.android.googlequicksearchbox:search, PID: 6460
E/AndroidRuntime( 6460): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 6460): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.ApplicationsHelper.updateApplicationsList(ApplicationsHelper.java:171)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$DatabaseHelper.updateApplications(InternalIcingCorporaProvider.java:511)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:288)
E/AndroidRuntime( 6460): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 6460): 	at android.content.ContentResolver.update(ContentResolver.java:1327)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateApplicationsTask.call(InternalIcingCorporaProvider.java:796)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaTask.call(InternalIcingCorporaProvider.java:691)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.startUpdateCorporaTask(InternalIcingCorporaProvider.java:1147)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.handleUpdateIntent(InternalIcingCorporaProvider.java:1087)
E/AndroidRuntime( 6460): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(InternalIcingCorporaProvider.java:1074)
E/AndroidRuntime( 6460): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6460): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6460): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6460): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/Resources( 2419): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SELinux ( 7896): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7896):  
,I/Process ( 6460): Sending signal. PID: 6460 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop219.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/CrashAnrDetector( 2419): onPackageRemoved : com.test.thalitest
D/UsbSettingsManager( 2419): clearDefaults: com.test.thalitest
,W/AtomicFile( 2419): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2419): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
I/ActivityManager( 2419): Process com.google.android.googlequicksearchbox:search (pid 6460) (adj 5) has died.
,I/SELinux ( 7896): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7896):  
I/SELinux ( 7896):  
,I/SELinux ( 7896): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7896): >>>>> Normal User
,E/dalvikvm( 7896): >>>>> com.samsung.android.intelligenceservice [ userId:0 | appId:10005 ]
,E/SELinux ( 7896): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7896): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7896): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7896): Added TimaKesytore provider
,D/dalvikvm( 7896): GC_CONCURRENT freed 3005K, 32% free 9564K/13944K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7896): WAIT_FOR_CONCURRENT_GC blocked 23ms
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{438fca08 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,D/UserAnalysis.PlaceProvider( 7896): Create SecureDbHelper
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 7896): Create SecureDbHelper
,E/SQLiteDatabase( 7896): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7896): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7896): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:324)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7896): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7896): Opened privacy in read-only mode
,E/SQLiteDatabase( 7896): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7896): 	at dalvik.system.NativeStart.main(Native Method)
,E/SQLiteOpenHelper( 7896): Couldn't open privacy for writing (will try read-only):
E/SQLiteOpenHelper( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:170)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:325)
E/SQLiteOpenHelper( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteOpenHelper( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteOpenHelper( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteOpenHelper( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteOpenHelper( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteOpenHelper( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteOpenHelper( 7896): 	at dalvik.system.NativeStart.main(Native Method)
,W/SQLiteOpenHelper( 7896): Opened privacy in read-only mode
,E/SQLiteDatabase( 7896): Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
E/SQLiteDatabase( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
E/SQLiteDatabase( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7896): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7896): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err( 7896): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 7896): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 7896): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 7896): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 7896): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteData,base.java:696)
W/System.err( 7896): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7896): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 7896): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.cleanUserConsent(PrivacyManager.java:330)
W/System.err( 7896): 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver.onReceive(UserAnalysisBroadcastReceiver.java:103)
W/System.err( 7896): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
W/System.err( 7896): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 7896): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
W/System.err( 7896): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7896): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 7896): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 7896): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 7896): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 7896): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 7896): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err( 7896): 	at dalvik.system.NativeStart.main(Native Method)
W/ContextImpl( 6398): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:165 android.app.ActivityThread.handleReceiver:2698 
D/RCPManager( 6478):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2419):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 2419): queryAllProviders():  providerCallBack is not register for 0
D/CapabilityManagerService New( 6739): Receiver Broadcast:android.intent.action.PACKAGE_REMOVED
D/CapabilityManagerService New( 6739): The package(com.test.thalitest) removed
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
,W/System.err( 2419): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 6398): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
W/System.err( 2419): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2419): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
W/System.err( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
W/System.err( 2419): 	at libcore.io.Posix.open(Native Method)
W/System.err( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 6398): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 6398): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
W/System.err( 6398): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
W/System.err( 2419): 	... 8 more
W/System.err( 6398): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
W/System.err( 6398): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
W/System.err( 6398): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
W/System.err( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
W/System.err( 6398): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
W/System.err( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
W/System.err( 6398): 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:109)
W/System.err( 2419): java.io.FileNotFoundException: /data/system/.cmanager/managedpackages.xml.tmp: open failed: EROFS (Read-only file system)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
W/System.err( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.writePackagesToXml(PackageManagerService.java:2639)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.updateManagedPermissionOfPackage(PackageManagerService.java:3738)
W/System.err( 2419): 	at android.content.pm.IPackageManager$Stub.onTransact(IPackageManager.java:372)
W/System.err( 2419): 	at com.android.server.pm.PackageManagerService.onTransact(PackageManagerService.java:2186)
W/System.err( 2419): 	at android.os.Binder.execTransact(Binder.java:404)
W/System.err( 2419): 	at dalvik.system.NativeStart.run(Native Method)
W/System.err( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
W/System.err( 6398): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
W/System.err( 6398): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 2419): 	at libcore.io.Posix.open(Native Method)
W/System.err( 6398): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err( 2419): 	... 8 more
W/System.err( 6398): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/MagazineService::MagazineBroadcastReceiver( 6764): [onReceive] android.intent.action.PACKAGE_REMOVED com.test.thalitest
I/MagazineService::MagazineService( 6764): [onHandleIntent] ACTION_PACKAGE_REMOVED
,E/SQLiteDatabase( 6764): Failed to open database '/data/data/com.samsung.android.app.headlines/databases/card.db'.
E/SQLiteDatabase( 6764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6764): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/SQLiteDatabase( 6764): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/SQLiteDatabase( 6764): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/SQLiteDatabase( 6764): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/SQLiteDatabase( 6764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 6764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6764): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 6764): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 6764): FATAL EXCEPTION: IntentService[MagazineService::MagazineService]
E/AndroidRuntime( 6764): Process: com.samsung.android.magazine.service, PID: 6764
E/AndroidRuntime( 6764): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 6764): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 6764): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 6764): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 6764): 	at com.samsung.android.magazine.service.provider.AdministratorContentProvider.delete(AdministratorContentProvider.java:407)
E/AndroidRuntime( 6764): 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:273)
E/AndroidRuntime( 6764): 	at android.content.ContentResolver.delete(ContentResolver.java:1293)
E/AndroidRuntime( 6764): 	at com.samsung.android.magazine.service.MagazineService.onHandleIntent(MagazineService.java:108)
E/AndroidRuntime( 6764): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 6764): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 6764): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 6764): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/SELinux ( 7911): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7911):  
I/Process ( 6764): Sending signal. PID: 6764 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop220.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/ActivityManager( 2419): Process com.samsung.android.magazine.service (pid 6764) (adj 5) has died.
I/SELinux ( 7911): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7911):  
I/SELinux ( 7911):  
I/SELinux ( 7911): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7911): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7911): >>>>> Normal User
,E/dalvikvm( 7911): >>>>> com.android.keychain [ userId:0 | appId:1000 ]
,E/SELinux ( 7911): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7911): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7911): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7911): Added TimaKesytore provider
,D/dalvikvm( 7911): GC_CONCURRENT freed 3015K, 32% free 9560K/13948K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 7911): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/ContextImpl( 7911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1857 android.content.ContextWrapper.startService:506 android.content.ContextWrapper.startService:506 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2698 
,D/KidsModeInstallReceiver( 6790): onReceive intent data =  package:com.test.thalitest
E/SQLiteDatabase( 7911): Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
E/SQLiteDatabase( 7911): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7911): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7911): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7911): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7911): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/SQLiteDatabase( 7911): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/SQLiteDatabase( 7911): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 7911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7911): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7911): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 7911): threadid=10: thread exiting with uncaught exception (group=0x4180ac08)
,D/KidsPlatformStub( 6790): Package not found : com.sec.android.app.kidshome
E/AndroidRuntime( 7911): FATAL EXCEPTION: IntentService[KeyChainService]
E/AndroidRuntime( 7911): Process: com.android.keychain, PID: 7911
E/AndroidRuntime( 7911): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7911): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7911): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7911): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7911): 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:353)
E/AndroidRuntime( 7911): 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:347)
E/AndroidRuntime( 7911): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 7911): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7911): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7911): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop221.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,W/System.err( 6829): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 6829): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:243)
W/System.err( 6829): 	at com.n7mobile.promenada2.applications.ApplicationInstallationReceiver.onReceive(SourceFile:27)
W/System.err( 6829): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
,W/System.err( 6829): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
W/System.err( 6829): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
I/Process ( 7911): Sending signal. PID: 7911 SIG: 9
W/System.err( 6829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6829): 	at android.os.Looper.loop(Looper.java:146)
W/System.err( 6829): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err( 6829): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 6829): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 6829): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err( 6829): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
,W/System.err( 6829): 	at dalvik.system.NativeStart.main(Native Method)
,D/PackageBroadcastService( 3153): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,D/AccountUtils( 3153): Clearing selected account for com.test.thalitest
I/ActivityManager( 2419): Process com.android.keychain (pid 7911) (adj 5) has died.
,E/SQLiteLog( 3153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,D/ChimeraCfgMgr( 3153): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3153): Module APK com.google.android.play.games already loaded
,I/LocationSettingsChecker( 3153): Removing dialog suppression flag for package com.test.thalitest
,E/DriveAsyncService( 3153): disk I/O error (code 3850)
E/DriveAsyncService( 3153): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/DriveAsyncService( 3153): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/DriveAsyncService( 3153): 	at com.google.android.gms.drive.database.k.k(SourceFile:486)
E/DriveAsyncService( 3153): 	at com.google.android.gms.drive.database.k.b(SourceFile:461)
E/DriveAsyncService( 3153): 	at com.google.android.gms.drive.database.f.i(SourceFile:1519)
E/DriveAsyncService( 3153): 	at com.google.android.gms.drive.api.a.bl.a(SourceFile:16)
E/DriveAsyncService( 3153): 	at com.google.android.gms.common.service.f.run(SourceFile:176)
E/DriveAsyncService( 3153): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/DriveAsyncService( 3153): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/DriveAsyncService( 3153): 	at com.google.android.gms.common.util.a.c.run(SourceFile:17)
E/DriveAsyncService( 3153): 	at java.lang.Thread.run(Thread.java:841)
,D/ChimeraCfgMgr( 3153): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3153): Module APK com.google.android.play.games already loaded
,E/SQLiteLog( 2847): (3850) statement aborts at 29: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 2847): Shutting down VM
,W/dalvikvm( 2847): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
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
E/SQLiteDatabase( 3153): Failed to open database '/data/data/com.google.android.gms/databases/phenotype.db'.
E/SQLiteDatabase( 3153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3153): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3153): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 31,53): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 3153): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/SQLiteDatabase( 3153): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3153): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3153): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/PhenotypeInitializer( 3153): Could not unregister android package com.test.thalitest
E/PhenotypeInitializer( 3153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/PhenotypeInitializer( 3153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/PhenotypeInitializer( 3153): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3153): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/PhenotypeInitializer( 3153): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/PhenotypeInitializer( 3153): 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
E/PhenotypeInitializer( 3153): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/PhenotypeInitializer( 3153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/PhenotypeInitializer( 3153): 	at android.os.Looper.loop(Looper.java:146)
E/PhenotypeInitializer( 3153): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 3153): threadid=47: thread exiting with uncaught exception (group=0x4180ac08)
,E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop222.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
E/SQLiteLog( 3153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
E/SQLiteLog( 3153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
I/Process ( 2847): Sending signal. PID: 2847 SIG: 9
E/SQLiteDatabase( 3153): Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
E/SQLiteDatabase( 3153): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 3153): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 3153): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 3153): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 3153): 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
E/SQLiteDatabase( 3153): 	at com.google.android.gms.googlehelp.b.a.b(SourceFile:52)
E/SQLiteDatabase( 3153): 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
E/SQLiteDatabase( 3153): 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
E/SQLiteDatabase( 3153): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/SQLiteDatabase( 3153): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 3153): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 3153): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/SQLiteLog( 3153): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 3153): threadid=52: thread exiting with uncaught exception (group=0x4180ac08)
I/Process ( 3153): Sending signal. PID: 3153 SIG: 9
,E/SQLiteDatabase( 5549): Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
E/SQLiteDatabase( 5549): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 5549): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 5549): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 5549): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 5549): 	at com.sec.spp.push.i.a.a(Unknown Source)
E/SQLiteDatabase( 5549): 	at com.sec.spp.push.i.d.e(Unknown Source)
E/SQLiteDatabase( 5549): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5549): 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
E/SQLiteDatabase( 5549): 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
E/SQLiteDatabase( 5549): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 5549): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 5549): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 5549): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 5549): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 5549): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 5549): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 5549): 	at dalvik.system.NativeStart.main(Native Method)
,E/SPPClientService( 5549): [d] [getAppId()] Exception with message =not an error (code 0): Could not open the database in read/write mode.
,E/SQLiteDatabase( 6441): Failed to open database '/data/data/com.sec.spp.push/databases/evtDb'.
E/SQLiteDatabase( 6441): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.tracking.h.b(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.tracking.g.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.tracking.f.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.tracking.a.c(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.tracking.a.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6441): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6441): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6441): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6441): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6441): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6441): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6441): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6441): [g] not an error (code 0): Could not open the database in read/write mode.
,I/SELinux ( 7938): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7938):  
I/ActivityManager( 2419): Process com.google.process.gapps (pid 2847) (adj 5) has died.
,E/SQLiteDatabase( 6441): Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
E/SQLiteDatabase( 6441): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 6441): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 6441): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 6441): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.b.b.<init>(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.b.b.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.q.b(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.q.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.PackageChangeEventReceiver.a(Unknown Source)
E/SQLiteDatabase( 6441): 	at com.sec.spp.push.notisvc.registration.l.handleMessage(Unknown Source)
E/SQLiteDatabase( 6441): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 6441): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 6441): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 6441): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 6441): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 6441): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 6441): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 6441): 	at dalvik.system.NativeStart.main(Native Method)
,E/LNoti   ( 6441): [b] open fail. android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
I/ActivityManager( 2419): Process com.google.android.gms (pid 3153) (adj 0) has died.
,D/GAV2    ( 5640): Thread[main,5,main]: service disconnected: ComponentInfo{com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService}
,I/GAV2    ( 5640): Thread[main,5,main]: Unexpected disconnect.
,I/SELinux ( 7938): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7938):  
I/SELinux ( 7938):  
,I/SELinux ( 7938): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7938): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7938): >>>>> Normal User
,E/dalvikvm( 7938): >>>>> com.android.documentsui [ userId:0 | appId:10093 ]
,E/SELinux ( 7938): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7938): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7938): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7938): Added TimaKesytore provider
,D/dalvikvm( 7938): GC_CONCURRENT freed 2996K, 32% free 9572K/13944K, paused 2ms+2ms, total 25ms
,D/dalvikvm( 7938): WAIT_FOR_CONCURRENT_GC blocked 21ms
,D/Documents( 7938): Loading roots for com.android.externalstorage.documents
,E/SQLiteDatabase( 7938): Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
E/SQLiteDatabase( 7938): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 7938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 7938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 7938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 7938): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/SQLiteDatabase( 7938): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/SQLiteDatabase( 7938): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/SQLiteDatabase( 7938): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/SQLiteDatabase( 7938): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/SQLiteDatabase( 7938): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase( 7938): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase( 7938): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 7938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 7938): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 7938): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 7938): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 7938): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 7938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 7938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 7938): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 7938): Shutting down VM
,W/dalvikvm( 7938): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 7938): FATAL EXCEPTION: main
E/AndroidRuntime( 7938): Process: com.android.documentsui, PID: 7938
E/AndroidRuntime( 7938): java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7938): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime( 7938): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime( 7938): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 7938): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 7938): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 7938): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 7938): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 7938): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 7938): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 7938): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 7938): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 7938): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 7938): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 7938): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 7938): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 7938): 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:307)
E/AndroidRuntime( 7938): 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:265)
E/AndroidRuntime( 7938): 	at android.content.ContentProvider$Transport.call(ContentProvider.java:325)
E/AndroidRuntime( 7938): 	at android.content.ContentResolver.call(ContentResolver.java:1366)
E/AndroidRuntime( 7938): 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:35)
E/AndroidRuntime( 7938): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime( 7938): 	... 10 more
I/SELinux ( 7954): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7954):  
,I/SELinux ( 7958): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7958):  
,I/Process ( 7938): Sending signal. PID: 7938 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop223.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/ActivityManager( 2419): Process com.android.documentsui (pid 7938) (adj 9) has died.
,I/SELinux ( 7954): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7954):  
I/SELinux ( 7954):  
,I/SELinux ( 7954): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,E/dalvikvm( 7954): >>>>> Normal User
,E/dalvikvm( 7954): >>>>> com.android.externalstorage [ userId:0 | appId:10009 ]
,E/SELinux ( 7954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,I/SELinux ( 7969): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7969):  
I/SELinux ( 7958): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7958):  
I/SELinux ( 7958):  
,I/SELinux ( 7958): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7958): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,E/dalvikvm( 7958): >>>>> Normal User
,E/dalvikvm( 7958): >>>>> com.google.android.gms [ userId:0 | appId:10012 ]
,E/SELinux ( 7958): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7954): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7954): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7954): Added TimaKesytore provider
,D/TimaKeyStoreProvider( 7958): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7958): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7958): Added TimaKesytore provider
,I/SELinux ( 7969): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7969):  
I/SELinux ( 7969):  
,I/SELinux ( 7969): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7969): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7969): >>>>> Normal User
,E/dalvikvm( 7969): >>>>> com.google.android.googlequicksearchbox:search [ userId:0 | appId:10059 ]
,E/SELinux ( 7969): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7969): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7969): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7969): Added TimaKesytore provider
,D/dalvikvm( 7954): GC_CONCURRENT freed 2993K, 32% free 9577K/13944K, paused 4ms+5ms, total 30ms
,D/dalvikvm( 7954): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/ExternalStorage( 7954): After updating volumes, found 1 active roots
D/dalvikvm( 7958): GC_CONCURRENT freed 2948K, 32% free 9620K/13944K, paused 3ms+2ms, total 30ms
,D/dalvikvm( 7958): WAIT_FOR_CONCURRENT_GC blocked 24ms
,W/dalvikvm( 7958): VFY: unable to resolve static field 560 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 7958): VFY: replacing opcode 0x60 at 0x000b
,I/dalvikvm( 7958): Could not find method com.google.android.gms.common.app.GmsApplication.getSystemService, referenced from method com.google.android.gms.common.app.GmsApplication.onCreate
W/dalvikvm( 7958): VFY: unable to resolve virtual method 11562: Lcom/google/android/gms/common/app/GmsApplication;.getSystemService (Ljava/lang/Class;)Ljava/lang/Object;
,D/dalvikvm( 7958): VFY: replacing opcode 0x6e at 0x00cd
I/MultiDex( 7958): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 7958): install
,I/MultiDex( 7958): MultiDexExtractor.load(/data/app/com.google.android.gms-5.apk, false)
,I/MultiDex( 7958): loading existing secondary dex files
,I/MultiDex( 7958): load found 3 secondary dex files
,I/MultiDex( 7958): install done
,D/dalvikvm( 7969): GC_CONCURRENT freed 2994K, 32% free 9577K/13948K, paused 4ms+2ms, total 26ms
,D/dalvikvm( 7969): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Icing.InternalIcingCorporaProvider( 7969): Updating corpora: A: com.test.thalitest, C: MAYBE
,I/SELinux ( 7996): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7996):  
,D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 13% free 9504K/10924K, paused 3ms+4ms, total 35ms
,I/SELinux ( 7996): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7996):  
I/SELinux ( 7996):  
,I/SELinux ( 7996): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7996): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7996): >>>>> Normal User
,E/dalvikvm( 7996): >>>>> com.google.android.partnersetup [ userId:0 | appId:10014 ]
,E/SELinux ( 7996): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9504K/10924K, paused 3ms+4ms, total 29ms
,D/TimaKeyStoreProvider( 7996): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7996): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7996): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 13% free 9504K/10924K, paused 3ms+3ms, total 29ms
,I/SELinux ( 8008): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8008):  
,D/LocationManagerService( 2419): getProviders()=[passive]
,I/SELinux ( 8008): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8008):  
I/SELinux ( 8008):  
,I/SELinux ( 8008): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8008): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8008): >>>>> Normal User
,E/dalvikvm( 8008): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8008): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/dalvikvm( 7996): GC_CONCURRENT freed 3005K, 32% free 9562K/13944K, paused 3ms+2ms, total 31ms
,D/dalvikvm( 7996): WAIT_FOR_CONCURRENT_GC blocked 19ms
,D/TimaKeyStoreProvider( 8008): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8008): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8008): Added TimaKesytore provider
,I/ActivityManager( 2419): Waited long enough for: ServiceRecord{4310a878 u0 com.sec.spp.push/.PushClientService}
,D/dalvikvm( 8008): GC_CONCURRENT freed 2990K, 32% free 9578K/13944K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 8008): WAIT_FOR_CONCURRENT_GC blocked 24ms
,I/GservicesProvider( 8008): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 8008): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8008): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8008): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8008): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8008): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8008): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8008): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8008): Shutting down VM
,W/dalvikvm( 8008): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8008): FATAL EXCEPTION: main
E/AndroidRuntime( 8008): Process: com.google.process.gapps, PID: 8008
E/AndroidRuntime( 8008): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8008): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8008): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8008): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8008): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8008): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8008): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8008): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8008): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8008): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8008): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8008): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8008): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8008): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8008): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8008): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8008): 	... 12 more
,I/Process ( 8008): Sending signal. PID: 8008 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop224.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/ActivityManager( 2419): Process com.google.process.gapps (pid 8008) (adj 0) has died.
,W/ActivityManager( 2419): Service crashed 2 times, stopping: ServiceRecord{43097870 u0 com.google.android.gms/.gcm.GcmService}
,I/SELinux ( 8030): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8030):  
,I/SELinux ( 8030): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8030):  
I/SELinux ( 8030):  
,I/SELinux ( 8030): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8030): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8030): >>>>> Normal User
,E/dalvikvm( 8030): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8030): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8030): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8030): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8030): Added TimaKesytore provider
,D/dalvikvm( 8030): GC_CONCURRENT freed 2994K, 32% free 9580K/13948K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 8030): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/GservicesProvider( 8030): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 8030): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8030): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8030): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8030): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8030): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8030): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8030): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8030): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8030): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8030): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8030): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8030): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8030): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8030): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8030): Shutting down VM
,W/dalvikvm( 8030): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8030): FATAL EXCEPTION: main
E/AndroidRuntime( 8030): Process: com.google.process.gapps, PID: 8030
E/AndroidRuntime( 8030): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8030): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8030): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8030): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8030): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8030): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8030): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8030): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8030): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8030): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8030): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8030): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8030): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8030): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8030): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8030): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8030): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8030): 	... 12 more
W/ActivityManager( 2419): Process com.google.process.gapps has crashed too many times: killing!
I/ActivityManager( 2419): Killing 8030:com.google.process.gapps/u0a12 (adj 0): crash
W/ActivityManager( 2419): Unable to launch app com.google.android.gsf/10012 for provider com.google.settings: launching app beca,me null
W/ActivityManager( 2419): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
W/ActivityManager( 2419): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/ActivityThread( 7996): Failed to find provider info for com.google.android.gsf.gservices
E/ActivityThread( 7969): Failed to find provider info for com.google.settings
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
E/ActivityThread( 7958): Failed to find provider info for com.google.android.gsf.gservices
,I/SELinux ( 8046): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8046):  
,I/SELinux ( 8046): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8046):  
I/SELinux ( 8046):  
,I/SELinux ( 8046): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 8046): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8046): >>>>> Normal User
E/dalvikvm( 8046): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
E/SELinux ( 8046): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8046): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8046): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8046): Added TimaKesytore provider
,D/dalvikvm( 8046): GC_CONCURRENT freed 2998K, 32% free 9573K/13948K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8046): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/GservicesProvider( 8046): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 8046): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8046): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8046): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8046): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8046): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8046): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8046): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8046): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8046): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8046): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8046): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8046): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8046): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8046): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8046): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8046): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8046): Shutting down VM
,W/dalvikvm( 8046): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 8046): FATAL EXCEPTION: main
E/AndroidRuntime( 8046): Process: com.google.process.gapps, PID: 8046
E/AndroidRuntime( 8046): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8046): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8046): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8046): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8046): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8046): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8046): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8046): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8046): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8046): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8046): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8046): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8046): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8046): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8046): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8046): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8046): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8046): 	... 12 more
,I/Process ( 8046): Sending signal. PID: 8046 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/ActivityManager( 2419): Process com.google.process.gapps (pid 8046) (adj 0) has died.
,I/SELinux ( 8061): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8061):  
,I/SELinux ( 8061): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8061):  
I/SELinux ( 8061):  
,I/SELinux ( 8061): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8061): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8061): >>>>> Normal User
,E/dalvikvm( 8061): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8061): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8061): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8061): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8061): Added TimaKesytore provider
,D/dalvikvm( 8061): GC_CONCURRENT freed 2985K, 32% free 9583K/13944K, paused 3ms+2ms, total 25ms
,D/dalvikvm( 8061): WAIT_FOR_CONCURRENT_GC blocked 22ms
,W/dalvikvm( 2954): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
,E/AndroidRuntime( 2954): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 2954): Process: android.process.acore, PID: 2954
E/AndroidRuntime( 2954): android.database.sqlite.SQLiteDatabaseLockedException: database is locked (code 5)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:745)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:507)
E/AndroidRuntime( 2954): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:418)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:408)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:377)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2467)
E/AndroidRuntime( 2954): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 2954): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2954): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 2954): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 2954): Sending signal. PID: 2954 SIG: 9
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop227.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/GservicesProvider( 8061): Gservices pushing to system: true; secure/global: true
,E/SQLiteDatabase( 8061): Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
E/SQLiteDatabase( 8061): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8061): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 8061): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/SQLiteDatabase( 8061): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/SQLiteDatabase( 8061): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/SQLiteDatabase( 8061): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase( 8061): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8061): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8061): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase( 8061): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase( 8061): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase( 8061): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase( 8061): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase( 8061): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime( 8061): Shutting down VM
,W/dalvikvm( 8061): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
I/ActivityManager( 2419): Process android.process.acore (pid 2954) (adj -12) has died.
E/AndroidRuntime( 8061): FATAL EXCEPTION: main
E/AndroidRuntime( 8061): Process: com.google.process.gapps, PID: 8061
E/AndroidRuntime( 8061): java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5297)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4888)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4771)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime( 8061): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8061): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime( 8061): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime( 8061): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime( 8061): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime( 8061): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime( 8061): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime( 8061): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8061): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime( 8061): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 8061): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 8061): 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:393)
E/AndroidRuntime( 8061): 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:173)
E/AndroidRuntime( 8061): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1591)
E/AndroidRuntime( 8061): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1562)
E/AndroidRuntime( 8061): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5294)
E/AndroidRuntime( 8061): 	... 12 more
,I/SELinux ( 8076): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8076):  
,W/ActivityManager( 2419): Process com.google.process.gapps has crashed too many times: killing!
,I/ActivityManager( 2419): Killing 8061:com.google.process.gapps/u0a12 (adj 0): crash
,W/ActivityManager( 2419): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop228.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,E/ActivityThread( 7996): Failed to find provider info for com.google.android.gsf.gservices
,W/ActivityManager( 2419): Unable to launch app com.google.android.gsf/10012 for provider com.google.android.gsf.gservices: launching app became null
,E/ActivityThread( 7958): Failed to find provider info for com.google.android.gsf.gservices
D/dalvikvm( 7958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7958): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7958): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 7958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 7958): VFY: unable to resolve instance field 36
D/dalvikvm( 7958): VFY: replacing opcode 0x54 at 0x005f
D/dalvikvm( 7958): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7958): VFY: unable to resolve static field 120 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7958): VFY: replacing opcode 0x62 at 0x0047
D/dalvikvm( 7958): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
I/dalvikvm( 7958): DexOpt: unable to optimize instance field ref 0x0024 at 0x63 in Lcom/google/android/gms/common/util/ay;.b
,D/dalvikvm( 7958): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422a3bd0
,I/ActivityManager( 2419): Killing 6639:com.samsung.groupcast/u0a15 (adj 15): empty #43
D/dalvikvm( 7958): Added shared lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422a3bd0
D/dalvikvm( 7958): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422a3bd0, skipping init
D/dalvikvm( 7958): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422a3bd0
D/dalvikvm( 7958): Added shared lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422a3bd0
V/JNIHelp ( 7958): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SELinux ( 8076): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8076):  
I/SELinux ( 8076):  
,I/SELinux ( 8076): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8076): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 8076): >>>>> Normal User
,E/dalvikvm( 8076): >>>>> android.process.acore [ userId:0 | appId:10020 ]
,E/SELinux ( 8076): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/TimaKeyStoreProvider( 8076): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8076): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8076): Added TimaKesytore provider
,D/dalvikvm( 7958): Trying to load lib /data/app-lib/com.google.android.gms-5/libgmscore.so 0x422a3bd0
,D/dalvikvm( 7958): Shared lib '/data/app-lib/com.google.android.gms-5/libgmscore.so' already loaded in same CL 0x422a3bd0
D/dalvikvm( 7958): Trying to load lib /data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so 0x422a3bd0
,D/dalvikvm( 7958): Shared lib '/data/app-lib/com.google.android.gms-5/libconscrypt_gmscore_jni.so' already loaded in same CL 0x422a3bd0
,D/dalvikvm( 8076): GC_CONCURRENT freed 2989K, 32% free 9581K/13944K, paused 2ms+2ms, total 24ms
,D/dalvikvm( 8076): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/ProviderInstaller( 7958): Installed default security provider GmsCore_OpenSSL
,I/SELinux ( 8093): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8093):  
,I/SELinux ( 8093): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8093):  
I/SELinux ( 8093):  
,I/SELinux ( 8093): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8093): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 8093): >>>>> Normal User
,E/dalvikvm( 8093): >>>>> com.google.process.gapps [ userId:0 | appId:10012 ]
,E/SELinux ( 8093): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 8093): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8093): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8093): Added TimaKesytore provider
,E/SQLiteDatabase( 8076): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 8076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase( 8076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 8076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8076): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteOpenHelper( 8076): Couldn't open contacts2.db for writing (will try read-only):
E/SQLiteOpenHelper( 8076): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteOpenHelper( 8076): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteOpenHelper( 8076): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteOpenHelper( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteOpenHelper( 8076): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteOpenHelper( 8076): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteOpenHelper( 8076): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteOpenHelper( 8076): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteOpenHelper( 8076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteOpenHelper( 8076): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteOpenHelper( 8076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/SQLiteLog( 8076): (14) cannot open file at line 31285 of [00bb9c9ce4]
E/SQLiteLog( 8076): (14) os_unix.c:31285: (30) open(/data/user/0/com.android.providers.contacts/databases/contacts2.db-shm) - 
,E/SQLiteLog( 8076): (14) unable to open database file
,E/SQLiteDatabase( 8076): Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
E/SQLiteDatabase( 8076): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/SQLiteDatabase( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/SQLiteDatabase( 8076): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/SQLiteDatabase( 8076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8076): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase( 8076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 8076): threadid=13: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime( 8076): FATAL EXCEPTION: ContactsProviderWorker
E/AndroidRuntime( 8076): Process: android.process.acore, PID: 8076
E/AndroidRuntime( 8076): android.database.sqlite.SQLiteCantOpenDatabaseException: unable to open database file (code 14): , while compiling: PRAGMA synchronous
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.nativePrepareStatement(Native Method)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.acquirePreparedStatement(SQLiteConnection.java:1113)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.executeForString(SQLiteConnection.java:824)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.setSyncMode(SQLiteConnection.java:491)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:378)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:235)
E/AndroidRuntime( 8076): 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:188)
E/AndroidRuntime( 8076): 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
E/AndroidRuntime( 8076): 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:2315)
E/AndroidRuntime( 8076): 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:2402)
E/AndroidRuntime( 8076): 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:2256)
E/AndroidRuntime( 8076): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8076): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime( 8076): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/Process ( 8076): Sending signal. PID: 8076 SIG: 9
W/ActivityManager( 2419): Process android.process.acore has crashed too many times: killing!
E/DropBoxManagerService( 2419): Can't write: system_app_crash
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop229.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 5 more
,I/ActivityManager( 2419): Process android.process.acore (pid 8076) (adj -12) has died.
,F/ActivityManager( 2419): Service ServiceRecord{44121ea8 u0 com.android.providers.contacts/.VoicemailCleanupService} in process ProcessRecord{43025968 8076:android.process.acore/u0a20} not same as in map: null
,E/DropBoxManagerService( 2419): Can't write: system_server_wtf
E/DropBoxManagerService( 2419): java.io.FileNotFoundException: /data/system/dropbox/drop164.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2419): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2419): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2419): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12553)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.handleApplicationWtf(ActivityManagerService.java:12360)
E/DropBoxManagerService( 2419): 	at com.android.internal.os.RuntimeInit.wtf(RuntimeInit.java:395)
E/DropBoxManagerService( 2419): 	at android.util.Log$1.onTerribleFailure(Log.java:106)
E/DropBoxManagerService( 2419): 	at android.util.Log.wtf(Log.java:418)
E/DropBoxManagerService( 2419): 	at android.util.Slog.wtf(Slog.java:163)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActiveServices.killServicesLocked(ActiveServices.java:2151)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.cleanUpApplicationRecordLocked(ActivityManagerService.java:15153)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4944)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService.appDiedLocked(ActivityManagerService.java:5122)
E/DropBoxManagerService( 2419): 	at com.android.server.am.ActivityManagerService$AppDeathRecipient.binderDied(ActivityManagerService.java:1322)
E/DropBoxManagerService( 2419): 	at android.os.BinderProxy.sendDeathNotice(Binder.java:493)
E/DropBoxManagerService( 2419): 	at dalvik.system.NativeStart.run(Native Method)
E/DropBoxManagerService( 2419): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2419): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2419): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2419): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2419): 	... 18 more
,I/SELinux ( 8108): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8108):  
,D/dalvikvm( 8093): GC_CONCURRENT freed 2986K, 32% free 9580K/13944K, paused 7ms+2ms, total 30ms

```
