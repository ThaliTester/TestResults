#### Test 575312430087a60_thali03_samsung-SM-G800F Logs


```
--------- beginning of /dev/log/system
V/AlarmManager( 2394): waitForAlarm result :8
V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
--------- beginning of /dev/log/main
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4
D/AndroidRuntime( 7233): 
D/AndroidRuntime( 7233): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7233): CheckJNI is OFF
D/AndroidRuntime( 7233): setted country_code = Poland
D/AndroidRuntime( 7233): setted countryiso_code = PL
D/AndroidRuntime( 7233): setted sales_code = PLS
D/AndroidRuntime( 7233): readGMSProperty: start
D/AndroidRuntime( 7233): readGMSProperty: already setted!!
D/AndroidRuntime( 7233): readGMSProperty: end
D/AndroidRuntime( 7233): addProductProperty: start
D/dalvikvm( 7233): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 7233): Added shared lib libjavacore.so 0x0
D/dalvikvm( 7233): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 7233): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 7233): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack( 7233): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 7233): failed to load memtrack module: -2
D/dalvikvm( 7233): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime( 7233): Calling main entry com.android.commands.am.Am
V/ApplicationPolicy( 2394): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/CustomFrequencyManagerService( 2394): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2394  pkgName : ACTIVITY_RESUME_BOOSTER@4
W/ActivityManager( 2394): mDVFSHelper.acquire()
I/SurfaceFlinger( 1920): id=21 createSurf (16x16),-1 flag=20004, EimLayer
I/SurfaceFlinger( 1920): id=22 createSurf (16x16),-1 flag=20004, EimLayer
I/SELinux ( 7245): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7245):  
D/PointerIcon( 2394): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2394): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2394): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2394): setHoveringSpenCustomIcon IconType is same.1
D/AndroidRuntime( 7233): Shutting down VM
D/dalvikvm( 7233): GC_CONCURRENT freed 97K, 13% free 714K/816K, paused 1ms+0ms, total 4ms
I/SELinux ( 7245): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7245):  
I/SELinux ( 7245):  
I/SELinux ( 7245): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7245): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7245): >>>>> Normal User
E/dalvikvm( 7245): >>>>> com.test.thalitest [ userId:0 | appId:10616 ]
E/SELinux ( 7245): [DEBUG] seapp_context_lookup: seinfoCategory = default
D/TimaKeyStoreProvider( 7245): in addTimaSignatureService
D/TimaKeyStoreProvider( 7245): Cannot add TimaSignature Service, License check Failed
D/ActivityThread( 7245): Added TimaKesytore provider
V/WindowManager( 2394): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
I/SQLiteSecureOpenHelper( 4165): getWritableDatabase(pwd)
I/SQLiteSecureOpenHelper( 4165): getDatabaseLocked(b,b,pwd)...
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (8/10)
I/SurfaceFlinger( 1920): id=9 Removed Mauncher (-2/10)
D/Launcher( 2800): onTrimMemory. Level: 20
D/dalvikvm( 7245): GC_CONCURRENT freed 2994K, 30% free 9570K/13500K, paused 1ms+1ms, total 17ms
D/dalvikvm( 7245): WAIT_FOR_CONCURRENT_GC blocked 15ms
V/WebViewChromium( 7245): Binding Chromium to the background looper Looper (main, tid 1) {422382e8}
I/chromium( 7245): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 7245): Initializing chromium process, renderers=0
W/chromium( 7245): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
D/libEGL  ( 7245): loaded /system/lib/egl/libEGL_mali.so
D/libEGL  ( 7245): loaded /system/lib/egl/libGLESv1_CM_mali.so
D/libEGL  ( 7245): loaded /system/lib/egl/libGLESv2_mali.so
I/Mali    ( 7245): Mali API Version : 401
I/Mali    ( 7245): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,I/dalvikvm( 7245): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 7245): VFY: unable to resolve virtual method 252: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 7245): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 7245): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 7245): VFY: unable to resolve virtual method 247: Landroid/webkit/CookieManager;.flush ()V
,D/dalvikvm( 7245): VFY: replacing opcode 0x6e at 0x0008
,D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2394): tr p:7245,o:f
,W/dalvikvm( 7245): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
,W/dalvikvm( 7245): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 7245): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 7245): VFY: unable to resolve virtual method 305: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
,D/dalvikvm( 7245): VFY: replacing opcode 0x6f at 0x001a
,W/dalvikvm( 7245): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 7245): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 7245): VFY: unable to resolve virtual method 263: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
,D/dalvikvm( 7245): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 7245): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 7245): VFY: unable to resolve virtual method 268: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
,D/dalvikvm( 7245): VFY: replacing opcode 0x6e at 0x0000
,D/SystemWebViewEngine( 7245): CordovaWebView is running on device made by: samsung
,D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2394): semi p:7245,o:f
,I/SurfaceFlinger( 1920): id=23 createSurf (1x1),1 flag=404, NainActivit
D/STATUSBAR-StatusBarManagerService( 2394): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/PointerIcon( 2394): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2394): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2394): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,D/PointerIcon( 2394): setHoveringSpenCustomIcon IconType is same.1
,I/HWUI    ( 7245): EGLImpl-HWUI Protected EGL context created
D/STATUSBAR-StatusBarManagerService( 2394): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
,D/OpenGLRenderer( 7245): Enabling debug mode 0
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/AwContents( 7245): nativeOnDraw failed; clearing to background color.
,W/IInputConnectionWrapper( 7245): showStatusIcon on inactive InputConnection
,D/CustomFrequencyManagerService( 2394): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2394  tag : ACTIVITY_RESUME_BOOSTER@4
,W/ActivityManager( 2394): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 2394): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2394  pkgName : ACTIVITY_RESUME_BOOSTER@8
,D/JsMessageQueue( 7245): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 7245): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42230850
,D/dalvikvm( 7245): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x42230850
,D/jxcore_app_log( 7245): JniHelper::setJavaVM(0x4170d250), pthread_self() = 2030125624
,I/chromium( 7245): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/dalvikvm( 7245): GC_CONCURRENT freed 1290K, 17% free 11353K/13572K, paused 3ms+2ms, total 24ms
D/dalvikvm( 7245): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/dalvikvm( 7245): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/CustomFrequencyManagerService( 2394): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1400000  uid : 1000  pid : 2394  tag : ACTIVITY_RESUME_BOOSTER@8
,D/dalvikvm( 7245): GC_FOR_ALLOC freed 2339K, 19% free 14346K/17628K, paused 45ms, total 45ms
,D/dalvikvm( 7245): GC_CONCURRENT freed 6474K, 32% free 16035K/23468K, paused 2ms+12ms, total 65ms
,D/dalvikvm( 7245): WAIT_FOR_CONCURRENT_GC blocked 34ms
,D/dalvikvm( 7245): GC_FOR_ALLOC freed 5329K, 29% free 16859K/23468K, paused 42ms, total 43ms
,W/jxcore-log( 7245): Initializing JXcore engine
,W/jxcore-log( 7245): JXcore engine is ready
,W/jxcore-log( 7245): Starting JXcore engine
,W/jxcore-log( 7245): Platform android
W/jxcore-log( 7245): 
,W/jxcore-log( 7245): Process ARCH arm
W/jxcore-log( 7245): 
,I/jxcore-log( 7245): JXcore Cordova bridge is ready!
I/jxcore-log( 7245): 
,W/jxcore-log( 7245): JXcore engine is started
,I/jxcore-log( 7245): Toggling radios to true
I/jxcore-log( 7245): 
,D/BluetoothAdapter( 7245): enable(): BT is already enabled..!
,I/WifiManager( 7245): packageName : com.test.thalitest
,I/WifiManager( 7245): setWifiEnabled : true
,I/WifiService( 2394): setWifiEnabled: true pid=7245, uid=10616
,W/WifiService( 2394): Failed getting userId using ActivityManagerNative
W/WifiService( 2394): java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7245, uid=10616 requires android.permission.INTERACT_ACROSS_USERS
W/WifiService( 2394): 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:20671)
W/WifiService( 2394): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2348)
W/WifiService( 2394): 	at com.android.server.wifi.WifiService.setWifiEnabled(WifiService.java:2336)
W/WifiService( 2394): 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:178)
W/WifiService( 2394): 	at android.os.Binder.execTransact(Binder.java:404)
W/WifiService( 2394): 	at dalvik.system.NativeStart.run(Native Method)
,W/ActivityManager( 2394): Permission Denial: getCurrentUser() from pid=7245, uid=10616 requires android.permission.INTERACT_ACROSS_USERS,
I/WifiService( 2394): disconnect: pid=7245, uid=10616
I/wpa_supplicant( 3968): [wpa_supplicant_ctrl_iface_process] : DISCONNECT
I/jxcore-log( 7245): Radios toggled
I/jxcore-log( 7245): 
I/jxcore-log( 7245): My device name is: samsung-SM-G800F
I/jxcore-log( 7245): 
,I/wpa_supplicant( 3968): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
,I/wpa_supplicant( 3968): reset timer : RESET_TIMER 0
,I/wpa_supplicant( 3968): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,I/wpa_supplicant( 3968): First Scan Start
,I/wpa_supplicant( 3968): Scan requested (ret=0) - scan timeout 30 seconds
W/Settings( 2394): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/WifiStateMachine( 2394): ignore requestNetworkTransitionWakelock airplane:true
D/WifiP2pService( 2394): InactiveState{ what=143375 }
D/WifiP2pService( 2394): P2pEnabledState{ what=143375 }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,I/WifiTrafficPoller( 2394): evaluateTrafficStatsPolling
I/wpa_supplicant( 3968): wlan0: Setting scan request: 0 sec 0 usec
,I/wpa_supplicant( 3968): Skip scan - already scanning
D/ConnectivityService( 2394): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityService( 2394): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
E/ConnectivityService( 2394): net.tcp.usercfg.default not found in system default properties
E/ConnectivityService( 2394): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_use_userconfig: open failed: ENOENT (No such file or directory)
E/ConnectivityService( 2394): net.tcp.delack.default not found in system default properties
D/WifiP2pService( 2394): InactiveState{ what=143375 }
E/ConnectivityService( 2394): Can't set delayed ACK size:java.io.FileNotFoundException: /sys/kernel/ipv4/tcp_delack_seg: open failed: ENOENT (No such file or directory)
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/WifiP2pService( 2394): P2pEnabledState{ what=143375 }
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false)
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/ConnectivityService( 2394): Attempting to switch to mobile
,D/ConnectivityService( 2394): Attempting to switch to BLUETOOTH_TETHER
,D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,V/RouteController( 1915): /system/bin/ip -6 route del default table 2 2>&1
,I/SELinux ( 7294): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7294):  
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -6 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,D/CommandListener( 1915): Clearing all IP addresses on wlan0
,W/NetworkManagementService( 2394): route cmd failed: 
W/NetworkManagementService( 2394): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '35 route del src v6 2' failed with '400 35 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService( 2394): '
W/NetworkManagementService( 2394): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:406)
W/NetworkManagementService( 2394): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:338)
W/NetworkManagementService( 2394): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:303)
W/NetworkManagementService( 2394): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:288)
W/NetworkManagementService( 2394): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2502)
W/NetworkManagementService( 2394): 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:4156)
W/NetworkManagementService( 2394): 	at com.android.server.ConnectivityService.handleConnectivityChange(ConnectivityService.java:3938)
W/NetworkManagementService( 2394): 	at com.android.server.ConnectivityService.handleDisconnect(ConnectivityService.java:3088)
W/NetworkManagementService( 2394): 	at com.android.server.ConnectivityService.access$1800(ConnectivityService.java:258)
W/NetworkManagementService( 2394): 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:4781)
W/NetworkManagementService( 2394): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService( 2394): 	at android.os.Looper.loop(Looper.java:146)
W/NetworkManagementService( 2394): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,V/RouteController( 1915): /system/bin/ip -4 route del default table 2 2>&1
,I/WifiTrafficPoller( 2394): evaluateTrafficStatsPolling
,E/WifiStateMachine( 2394): Error! unhandled message{ when=-75ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,E/WifiStateMachine( 2394): Error! unhandled message{ when=-75ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
V/RouteController( 1915): RTNETLINK answers: No such process
V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
I/SELinux ( 7294): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7294):  
I/SELinux ( 7294):  
I/SELinux ( 7294): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7294): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/WifiStateMachine( 2394): Error! unhandled message{ when=-5ms what=135188 target=com.android.internal.util.StateMachine$SmHandler }
E/dalvikvm( 7294): >>>>> Normal User
E/dalvikvm( 7294): >>>>> com.vlingo.midas [ userId:0 | appId:10034 ]
E/SELinux ( 7294): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,D/TimaKeyStoreProvider( 7294): in addTimaSignatureService
,D/NetUtils( 2394): android_net_utils_resetConnections in env=0x77c7d0f0 clazz=0x62900001 iface=wlan0 mask=0x3
D/ConnectivityService( 2394): resetConnections(wlan0, 3)
,D/TimaKeyStoreProvider( 7294): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7294): Added TimaKesytore provider
,E/SPPClientService( 5538): [e] Push Channel Exception : java.net.SocketException: recvfrom failed: ETIMEDOUT (Connection timed out)
,V/NativeCrypto( 2850): Read error: ssl=0x7badb918: I/O error during system call, Connection timed out
,E/SPPClientService( 5538): [e] exceptionCaught(). NET_TIMEOUT
,V/NativeCrypto( 2850): SSL shutdown failed: ssl=0x7badb918: I/O error during system call, Broken pipe
,E/SPPClientService( 5538): [e] exceptionCaught(). if case. But because of NoActive signal. ignore.
,E/SPPClientService( 5538): [b] SharedConstants.WHAT_PUSH_NETWORK_NOT_AVAILABLE
,E/SPPClientService( 5538): [b] ResponseMap empty
,D/dalvikvm( 7294): GC_CONCURRENT freed 2991K, 30% free 9585K/13504K, paused 4ms+2ms, total 24ms
,D/dalvikvm( 7294): WAIT_FOR_CONCURRENT_GC blocked 17ms
,I/System.out( 7294): Inside WakeupProvider
,I/System.out( 7294): Inside onCreate() of WakeupTriggerProvide
,V/NetworkStats( 2394): updateIfacesLocked()
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,V/NetworkStats( 2394): performPollLocked(flags=0x1)
D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
V/NetworkStats( 2394): advisePersistThreshold() given 9223372036854775, clamped to 2097152
D/ConnectivityService( 2394): handleInetConditionChange: no active default network - ignore
,I/VlingoApplication( 7294): VlingoApplication appVersion ='11.4.0.3.34005', ro.csc.sales_code=PLS
,D/VlingoApplication( 7294): Couldn't create com.nuance.nuancedebugutilpackage context for host settings utility
,D/VlingoApplication( 7294): Couldn't create com.vlingo.midas.lmttutilitypackage context for host settings utility
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
V/NetworkStats( 2394): performPollLocked() took 28ms
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
I/ActivityManager( 2394): Killing 5391:com.google.android.talk/u0a109 (adj 15): empty #43
,D/DialogFlow( 7294): initQueue()
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 2828): MountReceiver.onReceive - Set preference state off
,V/NearbySettings( 2828): MountReceiver.mPrefHandler - 7002
,I/SELinux ( 7321): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7321):  
,I/SELinux ( 7321): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7321):  
I/SELinux ( 7321):  
,I/SELinux ( 7321): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7321): >>>>> Normal User
,E/dalvikvm( 7321): >>>>> com.google.android.talk [ userId:0 | appId:10109 ]
,E/SELinux ( 7321): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7321): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7321): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7321): Added TimaKesytore provider
,D/dalvikvm( 7321): GC_CONCURRENT freed 2995K, 30% free 9581K/13508K, paused 3ms+2ms, total 19ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 8ms
,I/dalvikvm( 7321): Could not find method android.os.PowerManager.isPowerSaveMode, referenced from method g.N
W/dalvikvm( 7321): VFY: unable to resolve virtual method 3967: Landroid/os/PowerManager;.isPowerSaveMode ()Z
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0008
,E/dalvikvm( 7321): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0000
,E/dalvikvm( 7321): Could not find class 'android.app.RemoteInput$Builder', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-instance 419 (Landroid/app/RemoteInput$Builder;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0037
,W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
I/dalvikvm( 7321): Could not find method dqp.q, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 23228: Ldqp;.q ()Ldra;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0000
,I/ApplicationPolicy( 2394): updateDataUsageMap
D/Tethering( 2394): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2394): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2394): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2394): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,I/DBG_DM  ( 4755): [3.19.140541][Line:2247][xdmProtoIsWIFIConnected] WiFi DisConnected
,D/libgps  ( 2394): agps_ril_update_network_state: Waiting for IPC connection...
E/dalvikvm( 7321): Could not find class 'android.app.Notification$Action$Builder', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-instance 407 (Landroid/app/Notification$Action$Builder;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0000
W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Ldqp;)
W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
I/dalvikvm( 7321): Could not find method dqp.getState, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 23205: Ldqp;.getState ()I
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0008
E/dalvikvm( 7321): Could not find class 'android.text.style.TtsSpan', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve const-class 834 (Landroid/text/style/TtsSpan;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x1c at 0x0026
W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Ldqp;)
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/DisconnectCause;)
W/dalvikvm( 7321): Unable to resolve superclass of Ldqp; (762)
W/dalvikvm( 7321): Link of class 'Ldqp;' failed
,I/dalvikvm( 7321): Could not find method dqp.d, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 23194: Ldqp;.d ()Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0003
,W/dalvikvm( 7321): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7321): Link of class 'Lax;' failed
E/dalvikvm( 7321): Could not find class 'ax', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-instance 1304 (Lax;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0006
W/dalvikvm( 7321): Unable to resolve superclass of Laz; (841)
,W/dalvikvm( 7321): Link of class 'Laz;' failed
E/dalvikvm( 7321): Could not find class 'az', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-instance 1358 (Laz;) in Lg;
D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x002c
I/dalvikvm( 7321): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0008
,I/dalvikvm( 7321): Could not find method android.view.ViewGroup.isTransitionGroup, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 5653: Landroid/view/ViewGroup;.isTransitionGroup ()Z
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x000c
I/dalvikvm( 7321): Could not find method android.view.View.getTransitionName, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 5484: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0006
I/dalvikvm( 7321): Could not find method android.transition.Transition.getTargetNames, referenced from method g.a
,W/dalvikvm( 7321): VFY: unable to resolve virtual method 5144: Landroid/transition/Transition;.getTargetNames ()Ljava/util/List;
D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x000a
I/dalvikvm( 7321): Could not find method android.view.ViewParent.onNestedPreFling, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve interface method 5703: Landroid/view/ViewParent;.onNestedPreFling (Landroid/view/View;FF)Z
,D/dalvikvm( 7321): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7321): Could not find method android.view.ViewParent.onNestedFling, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve interface method 5702: Landroid/view/ViewParent;.onNestedFling (Landroid/view/View;FFZ)Z
D/dalvikvm( 7321): VFY: replacing opcode 0x72 at 0x0000
I/dalvikvm( 7321): Could not find method android.view.ViewParent.onStartNestedScroll, referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve interface method 5707: Landroid/view/ViewParent;.onStartNestedScroll (Landroid/view/View;Landroid/view/View;I)Z
,D/dalvikvm( 7321): VFY: replacing opcode 0x72 at 0x0000
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature ([Landroid/app/RemoteInput;)
E/dalvikvm( 7321): Could not find class 'android.app.RemoteInput[]', referenced from method g.a
W/dalvikvm( 7321): VFY: unable to resolve new-array 9720 ([Landroid/app/RemoteInput;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x23 at 0x0005
,I/dalvikvm( 7321): Could not find method android.transition.TransitionSet.getTransitionCount, referenced from method g.b
W/dalvikvm( 7321): VFY: unable to resolve virtual method 5153: Landroid/transition/TransitionSet;.getTransitionCount ()I
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0009
,W/dalvikvm( 7321): Unable to resolve superclass of Lcom/google/android/apps/hangouts/telephony/TeleConnectionService; (764)
,W/dalvikvm( 7321): Link of class 'Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;' failed
E/dalvikvm( 7321): Could not find class 'com.google.android.apps.hangouts.telephony.TeleConnectionService', referenced from method g.l
W/dalvikvm( 7321): VFY: unable to resolve const-class 2678 (Lcom/google/android/apps/hangouts/telephony/TeleConnectionService;) in Lg;
,D/dalvikvm( 7321): VFY: replacing opcode 0x1c at 0x0002
,E/dalvikvm( 7321): Could not find class 'android.telecom.TelecomManager', referenced from method g.n
W/dalvikvm( 7321): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Lg;
D/dalvikvm( 7321): VFY: replacing opcode 0x1f at 0x000c
D/dalvikvm( 7321): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 7321): VFY: unable to resolve static field 1410 (SUPPORTED_ABIS) in Landroid/os/Build;
D/dalvikvm( 7321): VFY: replacing opcode 0x62 at 0x0006
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x0a9b at 0x3d in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x0a45 at 0x0e in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x1407 at 0x69 in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x1405 at 0x88 in Lg;.a
W/dalvikvm( 7321): Unable to resolve superclass of Lax; (841)
W/dalvikvm( 7321): Link of class 'Lax;' failed
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x1ea6 at 0x08 in Lg;.a
W/dalvikvm( 7321): Unable to resolve superclass of Laz; (841)
W/dalvikvm( 7321): Link of class 'Laz;' failed
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x1f7d at 0x2e in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x0a9b at 0x13 in Lg;.a
D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x133d at 0x0b in Lg;.l
,I/wpa_supplicant( 3968): nl80211: Received scan results (3 BSSes)
,I/wpa_supplicant( 3968): wlan0: Setting scan request: 8 sec 0 usec
I/wpa_supplicant( 3968): Trying to associate with C0.AA.48 (SSID='4E47373030' freq=2412 MHz)
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00.00.00 SSID=
,D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
,D/dalvikvm( 7321): Trying to load lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42232860
D/dalvikvm( 7321): Added shared lib /data/app-lib/com.google.android.talk-1/libcrashreporterer.so 0x42232860
,D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
,D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
I/wpa_supplicant( 3968): Associated with C0.AA.48
,D/Tethering( 2394): interfaceStatusChanged wlan0, true
I/wpa_supplicant( 3968): freq(2412) increment count 2
,I/wpa_supplicant( 3968): meet head of list.
,I/dalvikvm( 7321): Could not find method android.telephony.SmsManager.getCarrierConfigValues, referenced from method dnm.b
W/dalvikvm( 7321): VFY: unable to resolve virtual method 5004: Landroid/telephony/SmsManager;.getCarrierConfigValues ()Landroid/os/Bundle;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0076
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=C0.AA.48 SSID=4E47373030
,I/Babel_SMS( 7321): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7321): MmsConfig.loadMmsSettings
I/Babel_SMS( 7321): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,I/Babel_SMS( 7321): MmsConfig.loadFromDatabase
,I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 3968): WPA: Key negotiation completed with C0.AA.48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 3968): CTRL-EVENT-CONNECTED - Connection to C0.AA.48 completed (auth) [id=0 id_str=]
I/wpa_supplicant( 3968): CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=C0.AA.48 SSID=4E47373030
D/Tethering( 2394): interfaceLinkStateChanged wlan0, true
D/Tethering( 2394): interfaceStatusChanged wlan0, true
,D/WifiNative( 2394): callSECApiVoid - ID [50]
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,E/Babel_SMS( 7321): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7321): MmsConfig.loadFromResources
,E/Babel_SMS( 7321): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 7321): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-G800F, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-G800F.xml
,W/dalvikvm( 7321): Unable to resolve superclass of Lfzc; (613)
W/dalvikvm( 7321): Link of class 'Lfzc;' failed
E/dalvikvm( 7321): Could not find class 'fzc', referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.<init>
W/dalvikvm( 7321): VFY: unable to resolve new-instance 5387 (Lfzc;) in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0033
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjectionManager;)
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/media/projection/MediaProjection;)
I/dalvikvm( 7321): Could not find method android.media.projection.MediaProjection.createVirtualDisplay, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.e
W/dalvikvm( 7321): VFY: unable to resolve virtual method 3636: Landroid/media/projection/MediaProjection;.createVirtualDisplay (Ljava/lang/String;IIIILandroid/view/Surface;Landroid/hardware/display/VirtualDisplay$Callback;Landroid/os/Handler;)Landroid/hardware/display/VirtualDisplay;
,D/dalvikvm( 7321): VFY: replacing opcode 0x74 at 0x006d
I/dalvikvm( 7321): Could not find method android.media.projection.MediaProjectionManager.createScreenCaptureIntent, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 3640: Landroid/media/projection/MediaProjectionManager;.createScreenCaptureIntent ()Landroid/content/Intent;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0033
I/dalvikvm( 7321): Could not find method android.media.projection.MediaProjection.stop, referenced from method com.google.android.libraries.hangouts.video.sdk.ScreenVideoCapturer.f
W/dalvikvm( 7321): VFY: unable to resolve virtual method 3638: Landroid/media/projection/MediaProjection;.stop ()V
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0030
W/dalvikvm( 7321): Unable to resolve superclass of Lfzc; (613)
,W/dalvikvm( 7321): Link of class 'Lfzc;' failed
,D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x7c80 at 0x35 in Lcom/google/android/libraries/hangouts/video/sdk/ScreenVideoCapturer;.<init>
E/SensorService( 2394): Permission Denial : SEC Private Sensor 
,E/SensorService( 2394): Permission Denial : SEC Private Sensor 
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getNumberOfCameras)
,D/ExynosCameraInterface( 1924): DEBUG:duration time(    0 msec):(HAL_getCameraInfo)
,D/dalvikvm( 7321): GC_CONCURRENT freed 1764K, 20% free 10924K/13584K, paused 3ms+3ms, total 37ms
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 15ms
D/WifiP2pService( 2394): InactiveState{ what=143375 }
D/WifiP2pService( 2394): P2pEnabledState{ what=143375 }
,W/Settings( 7321): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7321): startup - clean
,I/Babel   ( 7321): deleted: false for 0
,I/dalvikvm( 7321): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method eeq.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 2973: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x000d
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/dalvikvm( 7321): Could not find method android.telecom.TelecomManager.clearAccounts, referenced from method dry.f
W/dalvikvm( 7321): VFY: unable to resolve virtual method 4959: Landroid/telecom/TelecomManager;.clearAccounts ()V
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x004e
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7321): Could not find class 'android.telecom.PhoneAccount$Builder', referenced from method dry.f
W/dalvikvm( 7321): VFY: unable to resolve new-instance 766 (Landroid/telecom/PhoneAccount$Builder;) in Ldry;
,D/dalvikvm( 7321): VFY: replacing opcode 0x22 at 0x0071
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4368, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
E/dalvikvm( 7321): Could not find class 'android.telecom.TelecomManager', referenced from method dry.i
W/dalvikvm( 7321): VFY: unable to resolve check-cast 774 (Landroid/telecom/TelecomManager;) in Ldry;
,D/dalvikvm( 7321): VFY: replacing opcode 0x1f at 0x0021
,W/dalvikvm( 7321): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/dalvikvm( 7321): DexOpt: unable to opt direct call 0x1338 at 0x7d in Ldry;.f
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/SSRMv2:SIOP( 2394): SIOP:: AP = 340, Delta = 10
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/dalvikvm( 7321): Could not find method android.media.MediaCodecInfo$CodecCapabilities.getVideoCapabilities, referenced from method fuo.a
W/dalvikvm( 7321): VFY: unable to resolve virtual method 3568: Landroid/media/MediaCodecInfo$CodecCapabilities;.getVideoCapabilities ()Landroid/media/MediaCodecInfo$VideoCapabilities;
,D/dalvikvm( 7321): VFY: replacing opcode 0x6e at 0x0074
I/PCWCLIENTTRACE_PushUtil( 6643): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6643): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6643): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6643): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6643): noConnectivity : true
D/STATUSBAR-IconMerger( 2581): checkOverflow(336), More:false, Req:false Child:3
,I/ActivityManager( 2394): Killing 6317:com.sec.phone/1001 (adj 15): empty #43
,I/vclib   ( 7321): onServiceConnected
,W/Babel   ( 7321): Attempted to change video mute state without an active call.
,I/dhcpcd  ( 7349): if(wlan0) info get Success. (MAC : C0.AA.48)
,I/dhcpcd  ( 7349): bssid match
,I/SELinux ( 7356): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7356):  
,D/dalvikvm( 7321): GC_CONCURRENT freed 1015K, 15% free 11924K/13884K, paused 3ms+2ms, total 56ms,
,D/dalvikvm( 7321): WAIT_FOR_CONCURRENT_GC blocked 42ms,
,I/SELinux ( 7356): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7356):  
I/SELinux ( 7356):  
,I/SELinux ( 7356): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7356): >>>>> Normal User
,E/dalvikvm( 7356): >>>>> com.sec.android.fotaclient [ userId:0 | appId:10011 ],
,E/SELinux ( 7356): [DEBUG] seapp_context_lookup: seinfoCategory = release,
,D/TimaKeyStoreProvider( 7356): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7356): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7356): Added TimaKesytore provider,
,D/dalvikvm( 7321): GC_FOR_ALLOC freed 474K, 16% free 12401K/14652K, paused 43ms, total 43ms,
,D/dalvikvm( 7356): GC_CONCURRENT freed 2999K, 30% free 9570K/13504K, paused 3ms+1ms, total 20ms,
,D/dalvikvm( 7356): WAIT_FOR_CONCURRENT_GC blocked 12ms,
,D/dalvikvm( 7321): GC_FOR_ALLOC freed 1759K, 22% free 12772K/16236K, paused 30ms, total 31ms,
,I/ActivityManager( 2394): Killing 6336:com.sec.providers.settingsearch/u0a162 (adj 15): empty #43,
,I/SELinux ( 7368): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7368):  
,I/SELinux ( 7368): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7368):  
I/SELinux ( 7368):  
,I/SELinux ( 7368): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7368): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7368): >>>>> Normal User
,E/dalvikvm( 7368): >>>>> com.samsung.klmsagent [ userId:0 | appId:10018 ],
,E/SELinux ( 7368): [DEBUG] seapp_context_lookup: seinfoCategory = platform,
,D/TimaKeyStoreProvider( 7368): in addTimaSignatureService,
D/libgps  ( 2394): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2394): LIBGPS: Cannot communicate (write) with a GPSD,
E/libgps  ( 2394): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2394): agps_ril_update_network_availability: Waiting for IPC connection...,
,D/TimaKeyStoreProvider( 7368): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7368): Added TimaKesytore provider,
,D/dalvikvm( 7368): GC_CONCURRENT freed 3009K, 30% free 9563K/13504K, paused 1ms+2ms, total 18ms,
,D/dalvikvm( 7368): WAIT_FOR_CONCURRENT_GC blocked 16ms,
,D/KLMS-2.3.201 : ( 7368): KLMSValidator() : checkQATesting(),
,I/KLMS-2.3.201 : ( 7368): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454092147816,
,I/KLMS-2.3.201 : ( 7368): KLMSUtility() : isNetworkAvailable() - WIFI : false| MOBILE : false,
,I/ActivityManager( 2394): Killing 5988:com.android.calendar/u0a144 (adj 15): empty #43,
,I/SELinux ( 7380): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7380):  
,I/SELinux ( 7380): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7380):  
I/SELinux ( 7380):  
,I/SELinux ( 7380): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7380): >>>>> Normal User
,E/dalvikvm( 7380): >>>>> com.sec.android.soagent [ userId:0 | appId:10038 ],
,E/SELinux ( 7380): [DEBUG] seapp_context_lookup: seinfoCategory = release
,D/TimaKeyStoreProvider( 7380): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7380): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7380): Added TimaKesytore provider
,D/dalvikvm( 7380): GC_CONCURRENT freed 2988K, 30% free 9581K/13504K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7380): WAIT_FOR_CONCURRENT_GC blocked 10ms
,D/SO_AGENT( 7380): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/SO_AGENT( 7380): [AccRegisterReceiver.java(Line:80/Method:onReceive)] Network is not available
,I/SA      ( 5802): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5802): [BDLM] already registered in spp
,I/SA      ( 5802): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5802): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [OR] == isSIMCardReady false ==
,I/SA      ( 5802): [SCU] == networkStateCheck == false
,I/SA      ( 5802): [OR] onReceive END
I/ActivityManager( 2394): Killing 6285:com.android.providers.calendar/u0a45 (adj 15): empty #43
,D/PhoneNumberLocatorBootCompletedReceiver( 2766): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2766): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6558): Other Intent
,I/SELinux ( 7392): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7392):  
,I/SELinux ( 7392): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7392):  
I/SELinux ( 7392):  
,I/SELinux ( 7392): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7392): >>>>> Normal User
,E/dalvikvm( 7392): >>>>> com.sec.android.widgetapp.ap.hero.accuweather [ userId:0 | appId:10068 ]
,E/SELinux ( 7392): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/TimaKeyStoreProvider( 7392): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7392): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7392): Added TimaKesytore provider
,D/dalvikvm( 7392): GC_CONCURRENT freed 2992K, 30% free 9575K/13500K, paused 3ms+1ms, total 21ms
,D/dalvikvm( 7392): WAIT_FOR_CONCURRENT_GC blocked 12ms
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> WC:35 [0:0] oR : create UI manager : start
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> UIMEM:88 [0:0] getInstance
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> UIMEM:76 [0:0] UIManager : create ui manager
,D/com.samsung.app( 7392): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
,D/com.samsung.app( 7392): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 5334): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7392): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 5334): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/com.samsung.app( 7392): [KK AccuPhone]>>> DBH:3014 [0:0] gADWI : count = 0
,D/daemonapp( 5334): [MSC_Daemon]>>> WCP:1100 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
I/ActivityManager( 2394): Killing 6156:com.sec.android.widgetapp.SPlannerAppWidget/u0a145 (adj 15): empty #43
,D/Headlines( 5869): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5869): getCountryCode(): countryCode = PL
,D/Headlines( 5869): Breath.onCreate
,D/Headlines( 5869): Breath timer started. interval : 30000
,I/SELinux ( 7405): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7405):  
,D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
,D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5869): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5869): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5869): requestUpdateNewsWelcomeCard !!! no welcome card
V/AlarmManager( 2394): waitForAlarm result :8
,I/SELinux ( 7405): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7405):  
I/SELinux ( 7405):  
,I/SELinux ( 7405): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
E/dalvikvm( 7405): >>>>> Normal User
,E/dalvikvm( 7405): >>>>> com.google.android.apps.magazines [ userId:0 | appId:10115 ]
,E/SELinux ( 7405): [DEBUG] seapp_context_lookup: seinfoCategory = untrusted
,D/TimaKeyStoreProvider( 7405): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7405): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7405): Added TimaKesytore provider
,D/dalvikvm( 7405): GC_CONCURRENT freed 2996K, 30% free 9576K/13504K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7405): WAIT_FOR_CONCURRENT_GC blocked 16ms
,V/WebViewChromium( 7405): Binding Chromium to the background looper Looper (main, tid 1) {4223ee08}
,I/chromium( 7405): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 7405): Initializing chromium process, renderers=0
,W/chromium( 7405): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,D/libEGL  ( 7405): loaded /system/lib/egl/libEGL_mali.so
,D/libEGL  ( 7405): loaded /system/lib/egl/libGLESv1_CM_mali.so
,D/libEGL  ( 7405): loaded /system/lib/egl/libGLESv2_mali.so
,I/Mali    ( 7405): Mali API Version : 401
,I/Mali    ( 7405): Mali REVISION: Linux-r4p0-00rel0  BUILD_DATE: 2014-07-08 17:50:42 
,D/libgps  ( 2394): agps_ril_update_network_availability: Waiting for IPC connection - timeout
E/libgps  ( 2394): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2394): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability
,W/GAV2    ( 7405): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/cutils  ( 1911): Failed to mkdirat(/storage/extSdCard/Android): Read-only file system
W/Vold    ( 1911): Returning OperationFailed - no handler for errno 30
,W/ContextImpl( 7405): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,D/WifiP2pService( 2394): InactiveState{ what=143375 }
,D/WifiP2pService( 2394): P2pEnabledState{ what=143375 }
,D/WifiStateMachine( 2394): VerifyingLinkState enter
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/NSApplication( 7405): Starting up...
,D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,D/WifiStateMachine( 2394): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
,D/WifiStateMachine( 2394): CaptivePortalCheckState enter
,I/WifiTrafficPoller( 2394): evaluateTrafficStatsPolling,
,D/WifiStateMachine( 2394): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/ConnectivityService( 2394): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2394): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
,I/WifiTrafficPoller( 2394): evaluateTrafficStatsPolling,
D/ConnectivityService( 2394): ConnectivityChange for WIFI: CONNECTED/CONNECTED
E/ConnectivityService( 2394): net.tcp.usercfg.wifi not found in system properties. Using defaults
E/ConnectivityService( 2394): net.tcp.delack.wifi not found in system properties. Using defaults
D/STATUSBAR-NetworkController( 2581): onReceive() - RSSI_CHANGED_ACTION, WIFI_STATE, NETWORK_STATE
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster - setNWBoosterIndicators(false),
D/STATUSBAR-NetworkController( 2581): refreshSignalCluster: data=-1 bt=false
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,I/iu.Environment( 5934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true,
,D/ConnectivityService( 2394): handleConnectivityChange: setting default proxy info ,
,D/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
I/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a7e8
,V/RouteController( 1915): /system/bin/ip -4 route replace default via 192.168.1.1 dev wlan0 scope global table 2 2>&1
,I/SELinux ( 7466): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7466):  
,V/RouteController( 1915): /system/bin/ip -4 rule del table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such file or directory
,V/RouteController( 1915): /system/bin/ip -4 rule add from 192.168.1.126 lookup 2 prio 150 2>&1
,V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,V/RouteController( 1915): /system/bin/ip route del 192.168.1.0/24 table 2 2>&1
,V/RouteController( 1915): RTNETLINK answers: No such process
,V/RouteController( 1915): /system/bin/ip route add 192.168.1.0/24 dev wlan0 table 2 metric 0 2>&1
I/SELinux ( 7466): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7466):  
I/SELinux ( 7466):  
,I/SELinux ( 7466): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7466): >>>>> Normal User
,E/dalvikvm( 7466): >>>>> com.android.email [ userId:0 | appId:10157 ]
V/RouteController( 1915): /system/bin/ip route flush cached 2>&1
,E/SELinux ( 7466): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,V/NetworkStats( 2394): updateIfacesLocked()
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
V/NetworkStats( 2394): performPollLocked(flags=0x1)
V/NetworkStats( 2394): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/TimaKeyStoreProvider( 7466): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7466): Cannot add TimaSignature Service, License check Failed
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,V/NetworkStats( 2394): performPollLocked() took 18ms
D/ActivityThread( 7466): Added TimaKesytore provider
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/NtpTrustedTime( 2394): currentTimeMillis() cache hit
,D/dalvikvm( 7466): GC_CONCURRENT freed 2993K, 30% free 9586K/13508K, paused 3ms+1ms, total 19ms
,D/dalvikvm( 7466): WAIT_FOR_CONCURRENT_GC blocked 13ms
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,I/SELinux ( 7497): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7497):  
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,D/dalvikvm( 1921): GC_EXPLICIT freed 42K, 10% free 9507K/10484K, paused 2ms+3ms, total 31ms
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
I/SELinux ( 7497): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7497):  
I/SELinux ( 7497):  
,I/SELinux ( 7497): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm( 7497): >>>>> Normal User
E/dalvikvm( 7497): >>>>> com.sec.android.provider.badge [ userId:0 | appId:10076 ]
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,E/SELinux ( 7497): [DEBUG] seapp_context_lookup: seinfoCategory = release
I/ActivityManager( 2394): Killing 6191:com.google.android.music:main/u0a125 (adj 15): empty #43
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10484K, paused 3ms+3ms, total 28ms
,D/TimaKeyStoreProvider( 7497): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7497): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7497): Added TimaKesytore provider
,D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10484K, paused 2ms+4ms, total 27ms
I/ActivityManager( 2394): Killing 6250:com.android.defcontainer/u0a6 (adj 15): empty #43
W/ActivityManager( 2394): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/SELinux ( 7510): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7510):  
,D/dalvikvm( 7497): GC_CONCURRENT freed 3004K, 30% free 9570K/13508K, paused 3ms+1ms, total 20ms
,D/dalvikvm( 7497): WAIT_FOR_CONCURRENT_GC blocked 11ms
,D/BadgeProvider( 7497): onCreate
,D/BadgeProvider( 7497): DatabaseHelper
,I/SELinux ( 7510): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7510):  
I/SELinux ( 7510):  
,I/SELinux ( 7510): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7510): [DEBUG] seapp_context_lookup: seinfoCategory = shared
E/dalvikvm( 7510): >>>>> Normal User
,E/dalvikvm( 7510): >>>>> com.samsung.android.service.travel [ userId:0 | appId:10170 ]
,E/SELinux ( 7510): [DEBUG] seapp_context_lookup: seinfoCategory = shared
,D/BadgeProvider( 7497): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/TimaKeyStoreProvider( 7510): in addTimaSignatureService
D/BadgeProvider( 7497): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/Launcher.Model( 2800): reloadBadges entered.
D/BadgeProvider( 7497): sendNotify, [notify] : null
D/BadgeProvider( 7497): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 7497): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 7497): update, [UpdateCount] : 1
,D/TimaKeyStoreProvider( 7510): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7510): Added TimaKesytore provider
,D/Tethering( 2394): Tethering got CONNECTIVITY_ACTION
,D/Tethering( 2394): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker( 2394): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/STATUSBAR-NetworkController( 2581): onReceive() - CONNECTIVITY_ACTION, INET_CONDITION_ACTION
D/STATUSBAR-NetworkController( 2581): getUpdateDataNetType() - mDataNetType:0
D/STATUSBAR-NetworkController( 2581): updateDataNetType()
,D/STATUSBAR-NetworkController( 2581): NoService, mRoamingIconId = 0
,D/dalvikvm( 7510): GC_CONCURRENT freed 2997K, 30% free 9574K/13504K, paused 2ms+1ms, total 42ms
,D/dalvikvm( 7510): WAIT_FOR_CONCURRENT_GC blocked 40ms
,I/DBG_DM  ( 4755): [3.19.140541][Line:2242][xdmProtoIsWIFIConnected] WiFi Connected
,D/libgps  ( 2394): agps_ril_update_network_state: Waiting for IPC connection...
,D/WaitQueueForNetworkActivate( 6840): notifyNetworkActivated
,W/ContextImpl( 6840): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:529 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
W/ActivityManager( 2394): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,I/System.out( 7321): Thread-662(HTTPLog):isShipBuild true
,I/System.out( 7321): Thread-662(HTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/Babel   ( 7321): connection state changed from UNKNOWN to CONNECTED
,D/hcjo    ( 6840): AutoUpdateManager:IDLE:execute
,I/dalvikvm( 6840): Could not find method android.view.Window.setStatusBarColor, referenced from method com.sec.android.app.samsungapps.CommonActivity.onCreate
W/dalvikvm( 6840): VFY: unable to resolve virtual method 14867: Landroid/view/Window;.setStatusBarColor (I)V
,D/dalvikvm( 6840): VFY: replacing opcode 0x6e at 0x0024
,D/InitializeManagerStateMachine( 6840): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6840): exit::IDLE
,D/InitializeManagerStateMachine( 6840): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6840): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 6840): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6840): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6840): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6840): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6840): entry::SUCCESS
,D/hcjo    ( 6840): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6840): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6840): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 6840): exit::SUCCESS
,D/InitializeManagerStateMachine( 6840): entry::IDLE
,E/SPPClientService( 5538): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5538): [SystemStateMoniter] Current Time : 299985
,E/SPPClientService( 5538): [SystemStateMoniter] No Connect : true
,E/SPPClientService( 5538): [[SystemStateMonitorService]] No Active Internet
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 2394): Killing 6465:com.google.android.partnersetup/u0a14 (adj 15): empty #43
E/SPPClientService( 5538): [a] [ConnectionManager] Connection is already disconnected.
E/SPPClientService( 5538): [a] [ConnectionManager] Connection is already disconnected.
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5869): Breath 1749 latestRequest time : 1454092148371 current time : 1454092150120,
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5538): [[PushClientService]] <<--- deInitPushClientService  END  --->>
,E/SPPClientService( 5538): [[PushClientService]] SPPC Ver : 1.3.3.3, Server Ver : 1, Platform Ver : 19
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 2828): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI: CONNECTED
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 2828): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,E/SPPClientService( 5538): [[PushClientService]] F:false, D:false, E:false, T:false, S:false, R:false
,I/SurfaceFlinger( 1920): id=24 createSurf (1x1),1 flag=4, Uoast
,E/SPPClientService( 5538): [a] [ConnectionManager] Connection is already disconnected.
,E/SPPClientService( 5538): [g] getNetMCC return empty string
D/PowerManagerService( 2394): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2394
,D/NearbySettings( 2828): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 2828): MountReceiver.onReceive - Keep current state
,I/PCWCLIENTTRACE_PushUtil( 6643): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6643): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6643): getPushTypeList : [SPP, GCM]
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6643): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,D/AmoledAdjustTimer( 2394): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4
,I/KLMS-2.3.201 : ( 7368): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.3.201 : ( 7368): MainReciver() : EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1454092150564
,I/KLMS-2.3.201 : ( 7368): KLMSUtility() : isNetworkAvailable() - WIFI : true| MOBILE : false
,D/SO_AGENT( 7380): [AccRegisterReceiver.java(Line:56/Method:onReceive)] Receive broadcast meassage:android.net.conn.CONNECTIVITY_CHANGE
,I/LocationTagReadyService( 3375): onStartCommand : Action = com.samsung.android.app.galaxyfinder.tag.start_location_convert
,D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
,D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
D/GalaxyFinderApplication( 3375): [Slink platform] The state of Slink geocode service is true
,I/SO_AGENT( 7380): [AccRegisterReceiver.java(Line:87/Method:onReceive)] Need to accessory setup...
,I/GallerySearchProvider( 3519): query content://com.sec.android.gallery3d.provider.GallerySearchProvider/search_suggest_tag_query
,D/libgps  ( 2394): agps_ril_update_network_state: Waiting for IPC connection - timeout
E/libgps  ( 2394): LIBGPS: Cannot communicate (write) with a GPSD
E/libgps  ( 2394): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1625 agps_ril_update_network_state
,D/libgps  ( 2394): agps_ril_update_network_availability: Waiting for IPC connection...
,I/dalvikvm( 7356): Total arena pages for JIT: 11
,I/dalvikvm( 7356): Total arena pages for JIT: 12
I/dalvikvm( 7356): Total arena pages for JIT: 13
,I/dalvikvm( 7356): Total arena pages for JIT: 14
I/dalvikvm( 7356): Total arena pages for JIT: 15
,I/dalvikvm( 7356): Total arena pages for JIT: 16
,I/dalvikvm( 7356): Total arena pages for JIT: 17
,I/SA      ( 5802): [OR] onReceive log=[SA = 2.0.0097 V = 19 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = PLS MCC = 0 MNC 0 T = user DEVICE = kminilte P = kminiltexx I = KOT49H M = SM-G800F OKLEFT false DIS KOT49H.G800FXXU1ANG7 PSS = 4.497045606779314  ]
,I/SA      ( 5802): [BDLM] already registered in spp
I/SA      ( 5802): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. ]
,I/SA      ( 5802): [OR] == ACTION_CONNECTIVITY_CHANGE ==
I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [OR] == isSIMCardReady false ==
,I/SA      ( 5802): [SCU] == networkStateCheck == true
I/SA      ( 5802): [DM] getCountryCodeFromCSC : PL
I/SA      ( 5802): isChinaCountryCode : false
,I/SA      ( 5802): [OR] == networkStateCheck true ==
,I/SA      ( 5802): [OR] GetMyCountryZoneTask
,I/SA      ( 5802): [OR] onReceive END
,I/SA      ( 5802): [SRS] prepareGetMyCountryZone
,I/SA      ( 5802): [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,I/SA      ( 5802): [SSP] query invoked
,I/SA      ( 5802): [TPMU] GetMccFromDB : null
I/SA      ( 5802): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5802): [TPM] isNoProxy(default) : true
,I/SA      ( 5802): [RC New] Execute method=[GET] start
D/PhoneNumberLocatorBootCompletedReceiver( 2766): onReceive
,D/PhoneNumberLocatorBootCompletedReceiver( 2766): Phone number locator feature is dsiabled
,I/SCloudBackupReceiver( 6558): Other Intent
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> WC:28 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/com.samsung.app( 7392): [KK_EASY_Accu]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,D/Headlines( 5869): HeadlinesSystemBroadcastReceiver onReceive android.net.conn.CONNECTIVITY_CHANGE
,D/HeadlinesChannelUtil( 5869): getCountryCode(): countryCode = PL
,D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.UPDATE_WELCOME_CARD flag : 0
D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() category size == 0
D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() try to query category list
D/Headlines( 5869): queryCategory.  mRequest is not initialized.
D/HeadlinesCardManager( 5869): updateCategory : HeadlinesCardManager:updateCategory() reponse : false
D/HeadlinesCardManager( 5869): requestUpdateNewsWelcomeCard : request update welcome card to content card.
,D/HeadlinesDataCenter( 5869): requestUpdateNewsWelcomeCard !!! no welcome card
,D/dalvikvm( 2394): GC_EXPLICIT freed 3218K, 53% free 25034K/52672K, paused 10ms+19ms, total 274ms
,I/System.out( 7356): Thread-654(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/iu.Environment( 5934): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true
,I/System.out( 7356): Thread-654(ApacheHTTPLog):isShipBuild true
,I/System.out( 7356): Thread-654(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/SELinux ( 7543): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 7543):  
,I/QuickConnect[1.1][2] ( 5137): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,V/QuickConnect[1.1][2] ( 5137): SconnectManager.getInstance - () return existing instance com.samsung.android.sconnect.SconnectManager@4224a7e8
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,D/RCPManagerService( 2394): exchangeData() failure , invalid userId
,I/SELinux ( 7543): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 7543):  
I/SELinux ( 7543):  
,I/SELinux ( 7543): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm( 7543): >>>>> Normal User
,E/dalvikvm( 7543): >>>>> com.sec.android.app.voicenote [ userId:0 | appId:1000 ]
,E/SELinux ( 7543): [DEBUG] seapp_context_lookup: seinfoCategory = platform
,D/hcjo    ( 6840): AutoUpdateManager:IDLE:execute
,D/TimaKeyStoreProvider( 7543): in addTimaSignatureService
,D/TimaKeyStoreProvider( 7543): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 7543): Added TimaKesytore provider
,D/InitializeManagerStateMachine( 6840): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 6840): exit::IDLE
,D/InitializeManagerStateMachine( 6840): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 6840): execute::NETWORK_CHECK:NETWORK_STATE_OK
,D/InitializeManagerStateMachine( 6840): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 6840): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 6840): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 6840): exit::CHECK_COUNTRY_INFO
,D/InitializeManagerStateMachine( 6840): entry::SUCCESS
,D/hcjo    ( 6840): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/hcjo    ( 6840): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/hcjo    ( 6840): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
D/InitializeManagerStateMachine( 6840): exit::SUCCESS
,D/InitializeManagerStateMachine( 6840): entry::IDLE
,E/SPPClientService( 5538): [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,E/SPPClientService( 5538): [SystemStateMoniter] Current Time : 301045
,E/SPPClientService( 5538): [SystemStateMoniter] No Connect : false
,D/dalvikvm( 7543): GC_CONCURRENT freed 3000K, 30% free 9572K/13500K, paused 2ms+2ms, total 19ms
,D/dalvikvm( 7543): WAIT_FOR_CONCURRENT_GC blocked 16ms
,I/System.out( 7356): AsyncTask #1 calls detatch()
,V/KVNProvider( 7543): query uri : content://com.sec.android.app.voicenote.common.util.VNProvider/search_suggest_tag_query
,V/KVNProvider( 7543): getFindoCursor query string : 
,W/System.err( 7356): com.sec.android.fota.osp.http.RestClientException
W/System.err( 7356): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:293)
W/System.err( 7356): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:50)
W/System.err( 7356): 	at com.sec.android.fotaclient.network.NetConnect$1.doInBackground(NetConnect.java:36)
W/System.err( 7356): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
,W/System.err( 7356): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,W/System.err( 7356): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 7356): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 7356): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,W/System.err( 7356): 	at java.lang.Thread.run(Thread.java:841)
,W/System.err( 7356): Caused by: java.lang.NullPointerException
W/System.err( 7356): 	at com.sec.android.fota.osp.util.AuthUtil.normalizeUrl(AuthUtil.java:239)
W/System.err( 7356): 	at com.sec.android.fota.osp.util.AuthUtil.getSignSourceString(AuthUtil.java:157)
W/System.err( 7356): 	at com.sec.android.fota.osp.util.HeaderUtil.generateAuthorizationHeader(HeaderUtil.java:124)
W/System.err( 7356): 	at com.sec.android.fota.osp.http.RestClient.execute(RestClient.java:132)
,W/System.err( 7356): 	... 8 more
,V/KVNProvider( 7543): getTagSearchCursor() tagSearchCursor count : 0
,W/WifiP2pStateTracker( 2394): WifiP2pStateReceiver : android.net.wifi.LINK_CONFIGURATION_CHANGED
,D/ConnectivityService( 2394): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/ConnectivityService( 2394):    car=removed=[] added=[fe80::2f4:6fff:fe30:e06d/64,]
,D/ConnectivityService( 2394): handleConnectivityChange: setting default proxy info 
,D/ConnectivityService( 2394): updateSourceRoutes : no source routing conditions
,D/dalvikvm( 5538): GC_CONCURRENT freed 2006K, 23% free 10444K/13484K, paused 3ms+4ms, total 39ms
,D/PackageManager( 2394): [MSG] WRITE_PACKAGE_RESTRICTIONS
,I/SA      ( 5802): [RC New] [v2liruge] api execute + 851,
,I/SA      ( 5802): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK,
,I/System.out( 5802): AsyncTask #2 calls detatch(),
,I/SA      ( 5802): [TPMU] getNetworkMcc : ,
,I/SA      ( 5802): [SCU] saveMccToPreferece Start,
I/SA      ( 5802): [SCU] RegionMCC : 260,
,I/SA      ( 5802): [SSP] query invoked,
,I/SA      ( 5802): [TPMU] GetMccFromDB : null,
I/SA      ( 5802): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 5802): [SCU] saveMccToPreferece End
I/SA      ( 5802): [RC New] executeRequest [v2liruge] end. 891
,I/SA      ( 5802): [RC New] Execute end
I/SA      ( 5802): [OR] GetMyCountryZoneTask mcc = 260
,I/SA      ( 5802): [OR] GetMyCountryZoneTask Success,
,D/libgps  ( 2394): agps_ril_update_network_availability: Waiting for IPC connection - timeout,
E/libgps  ( 2394): LIBGPS: Cannot communicate (write) with a GPSD
,E/libgps  ( 2394): IPC Communication Error, /tmp/13242080_206888/customers/samsung/T0EVOLightandroid/../../../proprietary/deliverables/android/gps_interface/../gps_interface/gpsi_client/GpsiClient.cpp:1644 agps_ril_update_network_availability,
,E/SPPClientService( 5538): [b] __InitReply__,
,E/WifiStateMachine( 2394): CAPTIVE_PORTAL_EVENT_AUTHENTICATED,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/SurfaceFlinger( 1920): id=24 Removed Uoast (10/11),
,I/SurfaceFlinger( 1920): id=24 Removed Uoast (-2/11)
I/ActivityManager( 2394): Killing 6615:com.samsung.groupcast/u0a15 (adj 15): empty #43
,D/PowerManagerService( 2394): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 2394) eventTime = 303688
D/PowerManagerService( 2394): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=2394 (0x0)
D/PowerManagerService( 2394): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=2394, ws=WorkSource{1000}) (elapsedTime=3458)
,I/GAV2    ( 7405): Thread[GAThread,5,main]: No campaign data found.
,I/PCWCLIENTTRACE_SYSTEMReceiver( 6643): mConnectivityHandler : connected,
,W/PCWCLIENTTRACE_AccountUtil( 6643): [hasSamungAccount] - No Samsung Account,
,E/PCWCLIENTTRACE_SecurePreferencesJNI( 6643): failed to loading secure library,
I/PCWCLIENTTRACE_SecurePreferencesJNI( 6643): [GetString-S]
W/PCWCLIENTTRACE_SecurePreferencesJNI( 6643): GetString : secure API is not supported!!
,I/PCWCLIENTTRACE_PushUtil( 6643): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6643): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6643): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 6643): [ensureRegistration] - No Samsung account
,I/jxcore-log( 7245): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 7245): 
,I/jxcore-log( 7245): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 7245): 
,I/jxcore-log( 7245): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 7245): 
,I/jxcore-log( 7245): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 7245): 
,I/jxcore-log( 7245): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 7245): 
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4385, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): stay LED for fully charged
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/SSRMv2:SIOP( 2394): SIOP:: AP = 350, Delta = 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/CaptivePortalTracker( 2394): DelayedCaptiveCheckState{ when=-10ms what=2 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService( 2394): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker( 2394): Checking http://216.58.209.46/generate_204
,D/CaptivePortalTracker( 2394): Don't send network conditions - lacking user consent.
D/CaptivePortalTracker( 2394): isCaptivePortal: ret=false rspCode=204
,D/CaptivePortalTracker( 2394): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker( 2394): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false
D/ConnectivityService( 2394): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false captive=false
,D/PreloadUpdateManagerStateMachine( 6840): execute::IDLE:EXECUTE
D/PreloadUpdateManagerStateMachine( 6840): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6840): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6840): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6840): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6840): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6840): entry::IDLE
,D/AmoledAdjustTimer( 2394): prevTemp = 304, currTemp = 305, prevStep = 4, currStep = 4
,D/PreloadUpdateManagerStateMachine( 6840): execute::IDLE:EXECUTE
,D/PreloadUpdateManagerStateMachine( 6840): exit::IDLE
,D/PreloadUpdateManagerStateMachine( 6840): entry::CHECK_TIMEOUT_FOR_UPDATE
D/hcjo    ( 6840): AutoUpdateTriggerManager:IDLE:notifyNextTime
,D/PreloadUpdateManagerStateMachine( 6840): execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
D/PreloadUpdateManagerStateMachine( 6840): exit::CHECK_TIMEOUT_FOR_UPDATE
,D/PreloadUpdateManagerStateMachine( 6840): entry::IDLE
,D/TimaService( 2394): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2394): TimaServiceHandler.handleMessage what =1
,I/TLC_TIMA_PKM_initialize( 2394): initializing...
I/TLC_TIMA_PKM_initialize( 2394): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 2394): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2394): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 2394): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 2394): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 2394): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 2394): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 2394): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 2394): device_id = 0x0
I/TZ: mc_tlc_communication( 2394): tlc_open() was called
,I/TZ: mc_tlc_communication( 2394): Opening MobiCore device
I/TZ: mc_tlc_communication( 2394): Allocating WSM for TCI
,D/TimaService( 2394): TIMA: checkEvent, operation: 50000 subject: 10000
I/TZ: mc_tlc_communication( 2394): Opening the session
,I/TZ: mc_tlc_communication( 2394): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 2394): Trustlet response is completed
,I/PowerManagerService( 2394): [PWL] Off : 105s ago
,I/PowerManagerService( 2394): [PWL]   PowerManagerService.WakeLocks: ref count=1
I/PowerManagerService( 2394): [PWL]     mWakeLockSummary : 0x1
,I/PowerManagerService( 2394): [PWL]       PARTIAL_WAKE_LOCK              'TimaService' (uid=1000, pid=2394, ws=null) (elapsedTime=245)
,I/ActivityManager( 2394): Waited long enough for: ServiceRecord{42f95550 u0 com.samsung.android.app.headlines/com.samsung.android.internal.headlines.HeadlinesService}
,I/jxcore-log( 7245): Test app app.js loaded
I/jxcore-log( 7245): 
,I/dalvikvm( 7245): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.isBleAdvertisingSupported
W/dalvikvm( 7245): VFY: unable to resolve virtual method 54: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 7245): VFY: replacing opcode 0x6e at 0x0002
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 7245): setDiscoveryMode: Mode set to BLE
,I/chromium( 7245): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 7245): BLE advertisement is supported
I/jxcore-log( 7245): 
,I/ActivityManager( 2394): Waited long enough for: ServiceRecord{4305d0c0 u0 com.sec.spp.push/.PushClientService}
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 350, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 305, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,E/Watchdog( 2394): !@Sync 10,
,D/AmoledAdjustTimer( 2394): prevTemp = 305, currTemp = 305, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = -20,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 304, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/BatteryService( 2394): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,V/AlarmManager( 2394): waitForAlarm result :8,
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
,D/Headlines( 5869): Breath 27519 latestRequest time : 1454092150890 current time : 1454092178409,
,D/AmoledAdjustTimer( 2394): prevTemp = 305, currTemp = 304, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2394): prevTemp = 304, currTemp = 304, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2394): [PWL] Off : 140s ago,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 303, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2394): stay LED for fully charged,
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2394): !@Sync 11,
,V/AlarmManager( 2394): waitForAlarm result :8,
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2394): prevTemp = 304, currTemp = 303, prevStep = 4, currStep = 4,
,V/AlarmManager( 2394): waitForAlarm result :4,
,V/AlarmManager( 2394): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,I/SELinux ( 7812): Function: selinux_android_load_priority [0], There is no sepolicy file.,
I/SELinux ( 7812):  
,I/SELinux ( 7812): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046,
I/SELinux ( 7812):  
I/SELinux ( 7812):  
I/SELinux ( 7812): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts,
E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = default
E/dalvikvm( 7812): >>>>> Normal User
,E/dalvikvm( 7812): >>>>> com.blurb.checkout [ userId:0 | appId:10079 ],
,E/SELinux ( 7812): [DEBUG] seapp_context_lookup: seinfoCategory = default,
,D/TimaKeyStoreProvider( 7812): in addTimaSignatureService,
,D/TimaKeyStoreProvider( 7812): Cannot add TimaSignature Service, License check Failed,
,D/ActivityThread( 7812): Added TimaKesytore provider,
,D/dalvikvm( 7812): GC_CONCURRENT freed 2998K, 30% free 9570K/13504K, paused 4ms+2ms, total 28ms,
,D/dalvikvm( 7812): WAIT_FOR_CONCURRENT_GC blocked 22ms,
,I/ActivityManager( 2394): Killing 6629:com.android.musicfx/u0a24 (adj 15): empty #43,
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7817,
W/ProcessCpuTracker( 2394): Skipping unknown process pid 7822
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7827
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7839
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7840
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7842,
W/ProcessCpuTracker( 2394): Skipping unknown process pid 7844
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7847,
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 7850,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 302, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2394): waitForAlarm result :8
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5869): Breath 57508 latestRequest time : 1454092150890 current time : 1454092208398,
,D/AmoledAdjustTimer( 2394): prevTemp = 303, currTemp = 302, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = 0,
,D/AmoledAdjustTimer( 2394): prevTemp = 302, currTemp = 302, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 330, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,E/Watchdog( 2394): !@Sync 12,
,D/AmoledAdjustTimer( 2394): prevTemp = 302, currTemp = 301, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,I/PowerManagerService( 2394): [PWL] Off : 180s ago,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = -10,
,D/AmoledAdjustTimer( 2394): prevTemp = 301, currTemp = 301, prevStep = 4, currStep = 4,
,V/AlarmManager( 2394): waitForAlarm result :4,
,V/AlarmManager( 2394): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP,
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5869): Breath 94722 latestRequest time : 1454092150890 current time : 1454092245612
,I/SELinux ( 8043): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux ( 8043):  
,I/SELinux ( 8043): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux ( 8043):  
I/SELinux ( 8043):  
,I/SELinux ( 8043): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
,E/SELinux ( 8043): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm( 8043): >>>>> Normal User
,E/dalvikvm( 8043): >>>>> com.sec.spp.push:RemoteDlcProcess [ userId:0 | appId:10039 ]
,E/SELinux ( 8043): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
,D/TimaKeyStoreProvider( 8043): in addTimaSignatureService
,D/TimaKeyStoreProvider( 8043): Cannot add TimaSignature Service, License check Failed
,D/ActivityThread( 8043): Added TimaKesytore provider
,D/dalvikvm( 8043): GC_FOR_ALLOC freed 3019K, 30% free 9554K/13504K, paused 25ms, total 25ms
,D/dalvikvm( 8043): GC_CONCURRENT freed 214K, 30% free 9570K/13504K, paused 3ms+4ms, total 22ms
,E/SPPClientService( 8043): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 8043): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 8043): PushLog.txt file is not deleted.
D/SPPClientService( 8043): PushLog.txt file is not deleted.
,D/SPPClientService( 8043): ============PushLog. stop!
,I/ActivityManager( 2394): Killing 6657:com.samsung.android.app.galaxyfinder/u0a35 (adj 15): empty #43
,E/SPPClientService( 5538): [b] __PingReply__,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged,
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 301, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2394): !@Sync 13,
,V/AlarmManager( 2394): waitForAlarm result :8,
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2394): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2394): waitForAlarm result :8
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE
D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0
,D/Headlines( 5869): Breath 117494 latestRequest time : 1454092150890 current time : 1454092268384
,D/AmoledAdjustTimer( 2394): prevTemp = 300, currTemp = 300, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 299, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
,D/BatteryService( 2394): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2394): prevTemp = 300, currTemp = 299, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2394): [PWL] Off : 225s ago,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2394): !@Sync 14,
,D/AmoledAdjustTimer( 2394): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,V/AlarmManager( 2394): waitForAlarm result :8,
,D/Headlines( 5869): HeadlinesBroadcastReceiver onReceive com.samsung.android.internal.headlines.ALIVE,
,D/Headlines( 5869): Breath.onStartCommand : com.samsung.android.internal.headlines.ALIVE flag : 0,
D/Headlines( 5869): Breath 147512 latestRequest time : 1454092150890 current time : 1454092298403
,D/Headlines( 5869): stop ,
,D/Headlines( 5869): Breath.onDestroy : ,
I/ActivityManager( 2394): Killing 6002:com.sec.android.app.shealth/u0a36 (adj 15): empty #43
,D/AmoledAdjustTimer( 2394): prevTemp = 299, currTemp = 299, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 298, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate,
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2394): prevTemp = 299, currTemp = 298, prevStep = 4, currStep = 4,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,E/Watchdog( 2394): !@Sync 15,
,V/AlarmManager( 2394): waitForAlarm result :8,
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK,
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/AmoledAdjustTimer( 2394): prevTemp = 298, currTemp = 298, prevStep = 4, currStep = 4,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 297, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.,
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
,D/HeadsetStateMachine( 4002): Disconnected process message: 10,
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3,
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,D/AmoledAdjustTimer( 2394): prevTemp = 298, currTemp = 297, prevStep = 4, currStep = 4,
,I/PowerManagerService( 2394): [PWL] Off : 275s ago,
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> ,
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0,
,D/AmoledAdjustTimer( 2394): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 16
,D/AmoledAdjustTimer( 2394): prevTemp = 297, currTemp = 297, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 296, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 297, currTemp = 296, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 17
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 330s ago
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 296, currTemp = 296, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 296, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 18
,D/AmoledAdjustTimer( 2394): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 295, currTemp = 295, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 295, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 19
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4085): GC_CONCURRENT freed 2893K, 29% free 9730K/13552K, paused 10ms+3ms, total 58ms
,D/AmoledAdjustTimer( 2394): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 390s ago
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/TimaService( 2394): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2394): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2394): TimaServiceHandler.handleMessage what =1
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): stay LED for fully charged
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 294, currTemp = 294, prevStep = 4, currStep = 4
,D/dalvikvm( 2394): GC_CONCURRENT freed 3889K, 53% free 24939K/52672K, paused 23ms+17ms, total 263ms
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 294, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.absolute.android.persistservice.a.run:1059 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,E/Watchdog( 2394): !@Sync 21
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 455s ago
,V/AlarmManager( 2394): waitForAlarm result :4
,V/AlarmManager( 2394): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,I/GAV2    ( 5628): Thread[disconnect check,5,main]: Disconnecting due to inactivity
,I/GAV2    ( 5628): Thread[disconnect check,5,main]: Disconnected from service
,E/Watchdog( 2394): !@Sync 22
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 293, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 23
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
V/AlarmManager( 2394): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 2394): <AppSync3 Whitelist>
,V/AlarmManager( 2394): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 525s ago
,E/Watchdog( 2394): !@Sync 24
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 320, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = -10
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 25
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 293, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 293, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 26
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 600s ago
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 292, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 27
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 292, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 28
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 291, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 680s ago
,E/Watchdog( 2394): !@Sync 29
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 291, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 291, currTemp = 290, prevStep = 4, currStep = 4
,D/TimaService( 2394): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2394): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2394): TimaServiceHandler.handleMessage what =1
,W/ProcessCpuTracker( 2394): Skipping unknown process pid 9793
,E/Watchdog( 2394): !@Sync 30
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 31
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): stay LED for fully charged
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 290, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 765s ago
,E/Watchdog( 2394): !@Sync 32
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AmoledAdjustTimer( 2394): prevTemp = 290, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 33
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/dalvikvm( 2394): GC_CONCURRENT freed 3789K, 53% free 24908K/52672K, paused 20ms+16ms, total 285ms
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :4
,I/SensorManagerA( 2394): getReportingMode :: sensor.mType = 5
,D/LightsService( 2394): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
D/Sensors ( 2394): LightSensor setDelay = 200000000
D/Sensors ( 2394): LightSensor setSensorDelay = 200000000
D/Sensors ( 2394): Light sensor flush: not enabled 0
D/Sensors ( 2394): LightSensor enable = 1
D/Sensors ( 2394): LightSensor enableSensor = 1
D/SensorManager( 2394): registerListener :: 16, CM36686 Light Sensor, 200000, 0,  
,V/AlarmManager( 2394): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,I/EventLogService( 3571): Aggregate from 1454091078649 (log), 1454091078649 (data)
,D/Sensors ( 2394): LightSensor enable = 0
,D/Sensors ( 2394): LightSensor enableSensor = 0
,D/LightsService( 2394): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 2394): unregisterListener ::   
D/LightsService( 2394): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 34
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 289, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2394): [PWL] Off : 855s ago
,E/Watchdog( 2394): !@Sync 35
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 289, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 36
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/BatteryService( 2394): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 37
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 288, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 2394): [PWL] Off : 950s ago
,E/Watchdog( 2394): !@Sync 38
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 288, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 39
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged,
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/TimaService( 2394): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 2394): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 2394): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 2394): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response_id = 3
,I/TLC_TIMA_PKM_measure_kernel( 2394): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 2394): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
D/TimaService( 2394): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 41
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 1050s ago
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 42
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 2394): waitForAlarm result :4
,V/AlarmManager( 2394): trigger ELAPSED_REALTIME_WAKEUP or RTC_WAKEUP
,E/SPPClientService( 5538): [b] __PingReply__
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 43
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,V/AlarmManager( 2394): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 2394): <AppSync3 Whitelist>
,V/AlarmManager( 2394): (AppSync) ### 0 added ###
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 4085): GC_CONCURRENT freed 2050K, 29% free 9727K/13552K, paused 6ms+14ms, total 78ms
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 44
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 1155s ago
,E/Watchdog( 2394): !@Sync 45
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,E/Watchdog( 2394): !@Sync 46
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/dalvikvm( 2394): GC_CONCURRENT freed 3716K, 53% free 24943K/52672K, paused 20ms+17ms, total 255ms
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 47
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 287, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 287, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 2394): stay LED for fully charged
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 48
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 286, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 286, currTemp = 285, prevStep = 4, currStep = 4
,I/PowerManagerService( 2394): [PWL] Off : 1265s ago
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4387, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 2394): !@Sync 49
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,V/AlarmManager( 2394): waitForAlarm result :8
,V/AlarmManager( 2394): ClockReceiver onReceive() ACTION_TIME_TICK
,D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 2581): handleTimeUpdate
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/dalvikvm( 2800): GC_CONCURRENT freed 7281K, 35% free 19074K/28964K, paused 9ms+8ms, total 82ms
,D/dalvikvm( 2800): WAIT_FOR_CONCURRENT_GC blocked 72ms
,D/AmoledAdjustTimer( 2394): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4388, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false,
,D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
,D/UiModeManager( 2394): mCoverManager.getCoverState() : true
,D/BatteryService( 2394): stay LED for fully charged
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 4002): Disconnected process message: 10
,D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
,D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRMv2:SIOP( 2394): SIOP:: AP = 310, Delta = 0
,D/AmoledAdjustTimer( 2394): prevTemp = 285, currTemp = 285, prevStep = 4, currStep = 4
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime(11910): 
D/AndroidRuntime(11910): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11910): CheckJNI is OFF
D/AndroidRuntime(11910): setted country_code = Poland
D/AndroidRuntime(11910): setted countryiso_code = PL
D/AndroidRuntime(11910): setted sales_code = PLS
D/AndroidRuntime(11910): readGMSProperty: start
D/AndroidRuntime(11910): readGMSProperty: already setted!!
D/AndroidRuntime(11910): readGMSProperty: end
D/AndroidRuntime(11910): addProductProperty: start
D/dalvikvm(11910): Trying to load lib libjavacore.so 0x0
D/dalvikvm(11910): Added shared lib libjavacore.so 0x0
D/dalvikvm(11910): Trying to load lib libnativehelper.so 0x0
D/dalvikvm(11910): Added shared lib libnativehelper.so 0x0
D/dalvikvm(11910): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
E/memtrack(11910): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug(11910): failed to load memtrack module: -2
D/dalvikvm(11910): Note: class Landroid/app/ActivityManagerNative; has 192 unimplemented (abstract) methods
D/AndroidRuntime(11910): Calling main entry com.android.commands.pm.Pm
D/PackageManager( 2394): START PACKAGE DELETE: observer{1123643600}
D/PackageManager( 2394): pkg{<packageName>}
D/PackageManager( 2394): user{0}
D/PackageManager( 2394): deletePackageAsUser : uid = 2000 userId = 0
D/PackageManager( 2394): [MSG] DELETE_PACKAGE_AS_USER
D/ApplicationPolicy( 2394): getApplicationUninstallationEnabled
D/ApplicationPolicy( 2394): getApplicationUninstallationEnabled :  enabled true
D/PackageManagerService( 2394): deletePackageX- pkg:com.test.thalitest, userId:0
D/PackageManager( 2394): !@killApplicatoin: 10616, uninstall pkg
I/ActivityManager( 2394): Killing 7245:com.test.thalitest/u0a616 (adj 0): stop com.test.thalitest
D/PointerIcon( 2394): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2394): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2394): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2394): setHoveringSpenCustomIcon IconType is same.1
I/SurfaceFlinger( 1920): id=22 Removed EimLayer (5/10)
I/SurfaceFlinger( 1920): id=22 Removed EimLayer (-2/10)
I/SurfaceFlinger( 1920): id=21 Removed EimLayer (4/9)
I/SurfaceFlinger( 1920): id=21 Removed EimLayer (-2/9)
V/WindowManager( 2394): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false mAccelerometerDefault=false gripRotationLock=false
D/Launcher( 2800): onRestart, Launcher: 1109802656
D/Launcher( 2800): onStart, Launcher: 1109802656
D/Launcher.HomeView( 2800): onStart
I/SurfaceFlinger( 1920): id=23 Removed NainActivit (6/8)
I/SurfaceFlinger( 1920): id=23 Removed NainActivit (-2/8)
I/WindowState( 2394): WIN DEATH: Window{42ee86d8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/SurfaceFlinger( 1920): id=25 createSurf (720x1280),1 flag=4, Mauncher
D/STATUSBAR-StatusBarManagerService( 2394): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/STATUSBAR-StatusBarManagerService( 2394): manageDisableList what=0x0 pkg=WindowManager.LayoutParams
D/PointerIcon( 2394): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 2394): setMouseCustomIcon IconType is same.101
D/PointerIcon( 2394): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 2394): setHoveringSpenCustomIcon IconType is same.1
D/StatusBarManagerService( 2394): tr p:2800,o:f
D/PhoneStatusBar( 2581): setTransGradationMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/PhoneStatusBar( 2581): setSemiTransparentMode=false, mTransparentMode=false, mSemiTransparentMode=false, mMultiWindowMode=false
D/StatusBarManagerService( 2394): semi p:2800,o:f
W/ContextImpl( 2394): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1501 com.android.server.InputMethodManagerService$4.run:2728 java.lang.Thread.run:841 <bottom of call stack> <bottom of call stack> 
W/PackageSettings( 2394): Skipping PackageSetting{42962b18 com.example.hello/10614} due to missing metadata
W/InputMethodManagerService( 2394): Got RemoteException sending setActive(false) notification to pid 7245 uid 10616
D/PackageManager( 2394): checkUidPermission - Execution time: 155 ms
D/PackageManager( 2394): checkUidPermission - Execution time: 126 ms
D/PackageManager( 2394): Sending to user 0: act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10616, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
D/dalvikvm( 6809): GC_EXPLICIT freed 199K, 28% free 9963K/13720K, paused 12ms+6ms, total 85ms
D/PackageManager( 2394): Sending to user 0: act=android.intent.action.PACKAGE_FULLY_REMOVED dat=package:com.test.thalitest flg=0x4000000 Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10616, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
I/FPMS_FingerprintManagerService( 2601): onReceive: android.intent.action.PACKAGE_REMOVED
D/dalvikvm( 2953): GC_EXPLICIT freed 1474K, 26% free 10040K/13504K, paused 21ms+11ms, total 144ms
E/SamsungIME( 3004): mOCRHelper is null
D/QuickConnect[1.1][2] ( 5137): SconnectManager.onReceiver - action : android.intent.action.PACKAGE_REMOVED, package : com.test.thalitest
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "sms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/GeofencerStateMachine( 2736): Ignoring removeGeofence because network location is disabled.
D/dalvikvm( 6443): GC_EXPLICIT freed 574K, 27% free 9988K/13572K, paused 30ms+4ms, total 219ms
D/dalvikvm( 3571): GC_EXPLICIT freed 1722K, 19% free 12591K/15416K, paused 17ms+13ms, total 253ms
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "smsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/SELinux (11941): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11941):  
I/SELinux (11941): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11941):  
I/SELinux (11941):  
I/SELinux (11941): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11941): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11941): >>>>> Normal User
E/dalvikvm(11941): >>>>> com.sec.esdk.elm [ userId:0 | appId:10098 ]
E/SELinux (11941): [DEBUG] seapp_context_lookup: seinfoCategory = platform
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "mms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/TimaKeyStoreProvider(11941): in addTimaSignatureService
D/TimaKeyStoreProvider(11941): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11941): Added TimaKesytore provider
D/dalvikvm( 2394): GC_EXPLICIT freed 2041K, 53% free 25016K/52672K, paused 15ms+24ms, total 316ms
D/dalvikvm( 2394): WAIT_FOR_CONCURRENT_GC blocked 48ms
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "mmsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/EnterpriseDeviceManagerService( 2394): Package has changed for user 0
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "sms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/RCPManagerService( 2394): PackageReceiver onReceive()
I/HarmonyEASService( 2394): onReceive : android.intent.action.PACKAGE_REMOVED for 0
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "smsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "mms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "mmsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/dalvikvm( 2394): GC_EXPLICIT freed 614K, 53% free 25061K/52672K, paused 9ms+24ms, total 258ms
D/RegisteredServicesCache( 2778): empty dynamic service
I/InputReader( 2394): Reconfiguring input devices.  changes=0x00000010
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/dalvikvm(11941): GC_CONCURRENT freed 3005K, 30% free 9563K/13504K, paused 3ms+2ms, total 36ms
D/dalvikvm(11941): WAIT_FOR_CONCURRENT_GC blocked 27ms
D/PackageManager( 2394): delete sourFile : 
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/elm:14132(11941): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14132(11941): ELMEngine.ELMEngine( context ).
D/elm:14132(11941): MDMBridge.setEnterpriseBridge()
D/elm:14132(11941): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/BackupManagerService( 2394): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService( 2394): removePackageParticipantsLocked: uid=10616 #1
I/SELinux (11954): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11954):  
D/elm:14132(11941): ElmAgentService : onCreate()
D/elm:14132(11941): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14132(11941): MainReceiver.listeningToPackageRemoved()
D/elm:14132(11941): MDMBridge.getInstance()
D/elm:14132(11941): MDMBridge.getAllLicenseInfoFromSDK()
I/SELinux (11954): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11954):  
I/SELinux (11954):  
I/SELinux (11954): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
D/PackageManager( 2394): delete native library directory: 
E/SELinux (11954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11954): >>>>> Normal User
E/dalvikvm(11954): >>>>> com.sec.android.service.health [ userId:0 | appId:10016 ]
D/elm:14132(11941): MDMBridge.getAllLicenseInfoFromSDK()
E/SELinux (11954): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/PackageManager( 2394): return delete result to caller: 1123643600
D/PackageManager( 2394): returnCode: 1
D/elm:14132(11941): MainReceiver.listeningToPackageRemoved(). SEND to KLMS. Remove All KNOX/ONS License
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/AndroidRuntime(11910): Shutting down VM
D/elm:14132(11941): ElmAgentService : onDestroy().
D/dalvikvm(11910): GC_CONCURRENT freed 96K, 14% free 668K/768K, paused 0ms+0ms, total 4ms
I/ActivityManager( 2394): Killing 6687:com.samsung.android.sdk.samsunglink/u0a43 (adj 15): empty #43
D/dalvikvm( 2778): GC_CONCURRENT freed 2336K, 25% free 10262K/13524K, paused 9ms+2ms, total 107ms
D/TimaKeyStoreProvider(11954): in addTimaSignatureService
D/TimaKeyStoreProvider(11954): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11954): Added TimaKesytore provider
D/BatteryService( 2394): level:100, scale:100, status:5, health:2, present:true, voltage: 4378, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303692, invalid charger:0, online:4, current avg:1, charge type:1, power sharing:false
D/BatteryService( 2394): stay LED for fully charged
D/BatteryService( 2394): Sending ACTION_BATTERY_CHANGED.
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "sms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/UiModeManager( 2394): mCoverManager.getCoverState() : true
D/KeyguardUpdateMonitor( 2581): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 2581): handleBatteryUpdate
D/STATUSBAR-PhoneStatusBar( 2581):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
V/HeadsetService( 4002): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 4002): Disconnected process message: 10
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "smsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
D/STATUSBAR-IconMerger( 2581): checkOverflow(288), More:false, Req:false Child:3
D/BatteryMeterView( 2581): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
I/PackageManager( 2394):   Scheme: "mms"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
I/PackageManager( 2394):   Action: "android.intent.action.SENDTO"
I/PackageManager( 2394):   Category: "android.intent.category.DEFAULT"
D/dalvikvm(11954): GC_CONCURRENT freed 3010K, 30% free 9566K/13508K, paused 2ms+5ms, total 25ms
D/dalvikvm(11954): WAIT_FOR_CONCURRENT_GC blocked 23ms
I/PackageManager( 2394):   Scheme: "mmsto"
I/PackageManager( 2394): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ConversationComposer} for user 0 :
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (11971): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11971):  
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/ActivityManager( 2394): Killing 6384:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #43
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/SELinux (11971): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11971):  
I/SELinux (11971):  
I/SELinux (11971): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(11971): >>>>> Normal User
E/dalvikvm(11971): >>>>> com.sec.android.app.mss [ userId:0 | appId:10021 ]
E/SELinux (11971): [DEBUG] seapp_context_lookup: seinfoCategory = platform
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 2394): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
I/CrashAnrDetector( 2394): onPackageRemoved : com.test.thalitest
D/TimaKeyStoreProvider(11971): in addTimaSignatureService
D/UsbSettingsManager( 2394): clearDefaults: com.test.thalitest
D/TimaKeyStoreProvider(11971): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11971): Added TimaKesytore provider
W/ApplicationsProvider( 2953): Could not fetch usage stats
W/ApplicationsProvider( 2953): java.lang.SecurityException: Neither user 10020 nor current process has android.permission.PACKAGE_USAGE_STATS.
W/ApplicationsProvider( 2953): 	at android.os.Parcel.readException(Parcel.java:1465)
W/ApplicationsProvider( 2953): 	at android.os.Parcel.readException(Parcel.java:1419)
W/ApplicationsProvider( 2953): 	at com.android.internal.app.IUsageStats$Stub$Proxy.getAllPkgUsageStats(IUsageStats.java:317)
W/ApplicationsProvider( 2953): 	at android.app.ActivityManager.getAllPackageUsageStats(ActivityManager.java:2543)
W/ApplicationsProvider( 2953): 	at com.android.providers.applications.ApplicationsProvider.fetchUsageStats(ApplicationsProvider.java:681)
W/ApplicationsProvider( 2953): 	at com.android.providers.applications.ApplicationsProvider.updateApplicationsList(ApplicationsProvider.java:519)
W/ApplicationsProvider( 2953): 	at com.android.providers.applications.ApplicationsProvider.access$300(ApplicationsProvider.java:70)
W/ApplicationsProvider( 2953): 	at com.android.providers.applications.ApplicationsProvider$UpdateHandler.handleMessage(ApplicationsProvider.java:209)
W/ApplicationsProvider( 2953): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ApplicationsProvider( 2953): 	at android.os.Looper.loop(Looper.java:146)
W/ApplicationsProvider( 2953): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/AtomicFile( 2394): Couldn't rename file /data/system/users/0/appwidgets.xml to backup file /data/system/users/0/appwidgets.xml.bak
W/AppWidgetServiceImpl( 2394): Failed open state file for write: java.io.IOException: Couldn't create directory /data/system/users/0/appwidgets.xml
D/dalvikvm(11971): GC_CONCURRENT freed 2996K, 30% free 9576K/13504K, paused 3ms+2ms, total 25ms
D/dalvikvm(11971): WAIT_FOR_CONCURRENT_GC blocked 21ms
E/SQLiteDatabase(11971): Failed to open database '/data/data/com.sec.android.app.mss/databases/user.db'.
E/SQLiteDatabase(11971): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(11971): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(11971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase(11971): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase(11971): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/SQLiteDatabase(11971): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/SQLiteDatabase(11971): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/SQLiteDatabase(11971): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/SQLiteDatabase(11971): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase(11971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(11971): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(11971): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(11971): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(11971): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(11971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(11971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(11971): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(11971): Shutting down VM
W/dalvikvm(11971): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(11971): FATAL EXCEPTION: main
E/AndroidRuntime(11971): Process: com.sec.android.app.mss, PID: 11971
E/AndroidRuntime(11971): java.lang.RuntimeException: Unable to start receiver com.sec.android.app.mss.receiver.VerificationReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11971): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2713)
E/AndroidRuntime(11971): 	at android.app.ActivityThread.access$1800(ActivityThread.java:172)
E/AndroidRuntime(11971): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime(11971): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(11971): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(11971): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(11971): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(11971): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(11971): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(11971): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(11971): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(11971): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(11971): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(11971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11971): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime(11971): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime(11971): 	at com.sec.android.app.mss.b.h.b(Unknown Source)
E/AndroidRuntime(11971): 	at com.sec.android.app.mss.receiver.VerificationReceiver.onReceive(Unknown Source)
E/AndroidRuntime(11971): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2698)
E/AndroidRuntime(11971): 	... 10 more
I/SELinux (11988): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (11988):  
I/ActivityManager( 2394): Killing 6714:com.sec.android.service.cm/u0a82 (adj 15): empty #43
E/DropBoxManagerService( 2394): Can't write: system_app_crash
E/DropBoxManagerService( 2394): java.io.FileNotFoundException: /data/system/dropbox/drop225.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2394): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2394): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2394): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2394): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2394): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2394): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2394): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2394): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2394): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2394): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2394): 	... 5 more
I/Process (11971): Sending signal. PID: 11971 SIG: 9
I/ActivityManager( 2394): Process com.sec.android.app.mss (pid 11971) (adj 9) has died.
I/SELinux (11988): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (11988):  
I/SELinux (11988):  
I/SELinux (11988): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (11988): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(11988): >>>>> Normal User
E/dalvikvm(11988): >>>>> com.android.musicfx [ userId:0 | appId:10024 ]
E/SELinux (11988): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(11988): in addTimaSignatureService
D/TimaKeyStoreProvider(11988): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(11988): Added TimaKesytore provider
D/dalvikvm(11988): GC_CONCURRENT freed 2999K, 30% free 9574K/13508K, paused 2ms+2ms, total 24ms
D/dalvikvm(11988): WAIT_FOR_CONCURRENT_GC blocked 22ms
I/PCWCLIENTTRACE_PushUtil( 6643): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 6643): sales region : global
I/PCWCLIENTTRACE_PushUtil( 6643): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 6643): [onReceive] - android.intent.action.PACKAGE_REMOVED
I/SELinux (12003): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12003):  
I/SELinux (12003): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12003):  
I/SELinux (12003):  
I/SELinux (12003): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12003): [DEBUG] seapp_context_lookup: seinfoCategory = platform
E/dalvikvm(12003): >>>>> Normal User
E/dalvikvm(12003): >>>>> com.samsung.android.app.galaxyfinder [ userId:0 | appId:10035 ]
E/SELinux (12003): [DEBUG] seapp_context_lookup: seinfoCategory = platform
D/TimaKeyStoreProvider(12003): in addTimaSignatureService
D/TimaKeyStoreProvider(12003): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12003): Added TimaKesytore provider
D/dalvikvm(12003): GC_CONCURRENT freed 2997K, 30% free 9574K/13504K, paused 4ms+2ms, total 26ms
D/dalvikvm(12003): WAIT_FOR_CONCURRENT_GC blocked 16ms
W/System.err(12003): java.io.FileNotFoundException: /system/finder_cp/cpdata.xml: open failed: ENOENT (No such file or directory)
W/System.err(12003): 	at libcore.io.IoBridge.open(IoBridge.java:409)
W/System.err(12003): 	at java.io.FileInputStream.<init>(FileInputStream.java:78)
W/System.err(12003): 	at java.io.FileInputStream.<init>(FileInputStream.java:105)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.cp.CPFileLoad.loadDataFile(CPFileLoad.java:20)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.cp.CPDomParser.getCPData(CPDomParser.java:83)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.getSearchCPList(CategoryPreferences.java:112)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateWebCpList(CategoryPreferences.java:76)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.init(CategoryPreferences.java:44)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.init(GalaxyFinderApplication.java:104)
W/System.err(12003): 	at com.samsung.android.app.galaxyfinder.GalaxyFinderApplication.onCreate(GalaxyFinderApplication.java:88)
W/System.err(12003): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
W/System.err(12003): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
W/System.err(12003): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
W/System.err(12003): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
W/System.err(12003): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err(12003): 	at android.os.Looper.loop(Looper.java:146)
W/System.err(12003): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
W/System.err(12003): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err(12003): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err(12003): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
W/System.err(12003): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
W/System.err(12003): 	at dalvik.system.NativeStart.main(Native Method)
W/System.err(12003): Caused by: libcore.io.ErrnoException: open failed: ENOENT (No such file or directory)
W/System.err(12003): 	at libcore.io.Posix.open(Native Method)
W/System.err(12003): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
W/System.err(12003): 	at libcore.io.IoBridge.open(IoBridge.java:393)
W/System.err(12003): 	... 21 more
D/GalaxyFinderApplication(12003): [Slink platform] Version = 29011
D/GalaxyFinderApplication(12003): [Slink platform] use state of slink location service is [false] to [true]
I/SELinux (12017): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12017):  
I/ActivityManager( 2394): Killing 6727:com.samsung.android.app.watchmanagerstub/u0a104 (adj 15): empty #43
I/SELinux (12017): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12017):  
I/SELinux (12017):  
I/SELinux (12017): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12017): [DEBUG] seapp_context_lookup: seinfoCategory = release
E/dalvikvm(12017): >>>>> Normal User
E/dalvikvm(12017): >>>>> com.sec.android.app.shealth [ userId:0 | appId:10036 ]
E/SELinux (12017): [DEBUG] seapp_context_lookup: seinfoCategory = release
D/TimaKeyStoreProvider(12017): in addTimaSignatureService
D/TimaKeyStoreProvider(12017): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12017): Added TimaKesytore provider
D/dalvikvm(12017): GC_CONCURRENT freed 3000K, 30% free 9573K/13508K, paused 2ms+2ms, total 23ms
D/dalvikvm(12017): WAIT_FOR_CONCURRENT_GC blocked 21ms
W/ContextImpl(12017): Implicit intents with startService are not safe: Intent { act=com.sec.android.service.health.cp.accesscontrol } android.content.ContextWrapper.bindService:529 com.samsung.android.sdk.health.content.ShealthAccessControl.startService:274 com.samsung.android.sdk.health.content.ShealthAccessControl.requestPermission:212 
E/Device Type Shared Preferences(12017): Device Type Shared Preferences - getDeviceTypeChecked -true
E/Device Type Shared Preferences(12017): Device Type Shared Preferences - not connecting to service
E/com.sec.android.app.shealth.SHealthApplication(12017): ContentProvider is not null
W/ResourceType(12017): No package identifier when getting value for resource number 0x00000000
I/System.out(12017): resource Id::2131361807
E/SQLiteDatabase(12017): Failed to open database '/data/data/com.sec.android.app.shealth/databases/base.db'.
E/SQLiteDatabase(12017): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/SQLiteDatabase(12017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/SQLiteDatabase(12017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/SQLiteDatabase(12017): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/SQLiteDatabase(12017): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/SQLiteDatabase(12017): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/SQLiteDatabase(12017): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/SQLiteDatabase(12017): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/SQLiteDatabase(12017): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/SQLiteDatabase(12017): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/SQLiteDatabase(12017): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/SQLiteDatabase(12017): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/SQLiteDatabase(12017): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/SQLiteDatabase(12017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase(12017): 	at android.os.Looper.loop(Looper.java:146)
E/SQLiteDatabase(12017): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/SQLiteDatabase(12017): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/SQLiteDatabase(12017): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/SQLiteDatabase(12017): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/SQLiteDatabase(12017): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/SQLiteDatabase(12017): 	at dalvik.system.NativeStart.main(Native Method)
D/AndroidRuntime(12017): Shutting down VM
W/dalvikvm(12017): threadid=1: thread exiting with uncaught exception (group=0x4180ac08)
E/AndroidRuntime(12017): FATAL EXCEPTION: main
E/AndroidRuntime(12017): Process: com.sec.android.app.shealth, PID: 12017
E/AndroidRuntime(12017): java.lang.RuntimeException: Unable to create application com.sec.android.app.shealth.SHealthApplication: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12017): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4793)
E/AndroidRuntime(12017): 	at android.app.ActivityThread.access$1600(ActivityThread.java:172)
E/AndroidRuntime(12017): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1368)
E/AndroidRuntime(12017): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime(12017): 	at android.os.Looper.loop(Looper.java:146)
E/AndroidRuntime(12017): 	at android.app.ActivityThread.main(ActivityThread.java:5694)
E/AndroidRuntime(12017): 	at java.lang.reflect.Method.invokeNative(Native Method)
E/AndroidRuntime(12017): 	at java.lang.reflect.Method.invoke(Method.java:515)
E/AndroidRuntime(12017): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1291)
E/AndroidRuntime(12017): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1107)
E/AndroidRuntime(12017): 	at dalvik.system.NativeStart.main(Native Method)
E/AndroidRuntime(12017): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:338)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:232)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:889)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:859)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:696)
E/AndroidRuntime(12017): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1322)
E/AndroidRuntime(12017): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteSecureOpenHelper.getDatabaseLocked(SQLiteSecureOpenHelper.java:211)
E/AndroidRuntime(12017): 	at android.database.sqlite.SQLiteSecureOpenHelper.getWritableDatabase(SQLiteSecureOpenHelper.java:151)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.framework.repository.database.DBManager.getWritableDatabase(DBManager.java:121)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.handleGenericQuery(BaseContentProvider.java:296)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.framework.repository.BaseContentProvider.query(BaseContentProvider.java:231)
E/AndroidRuntime(12017): 	at android.content.ContentProvider.query(ContentProvider.java:857)
E/AndroidRuntime(12017): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:200)
E/AndroidRuntime(12017): 	at android.content.ContentResolver.query(ContentResolver.java:470)
E/AndroidRuntime(12017): 	at android.content.ContentResolver.query(ContentResolver.java:413)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.framework.app.AppRegistryDbManagerWithProvider.getPluginRegistryData(AppRegistryDbManagerWithProvider.java:197)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.SHealthApplication.getPreloadedAppRegistryData(SHealthApplication.java:363)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.SHealthApplication.loadPreInstalledPLuginsData(SHealthApplication.java:597)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.SHealthApplication.loadAppRegistryData(SHealthApplication.java:443)
E/AndroidRuntime(12017): 	at com.sec.android.app.shealth.SHealthApplication.onCreate(SHealthApplication.java:186)
E/AndroidRuntime(12017): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
E/AndroidRuntime(12017): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4790)
E/AndroidRuntime(12017): 	... 10 more
E/DropBoxManagerService( 2394): Can't write: system_app_crash
E/DropBoxManagerService( 2394): java.io.FileNotFoundException: /data/system/dropbox/drop226.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2394): 	at libcore.io.IoBridge.open(IoBridge.java:409)
E/DropBoxManagerService( 2394): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService( 2394): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService( 2394): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:218)
E/DropBoxManagerService( 2394): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService( 2394): 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12546)
E/DropBoxManagerService( 2394): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService( 2394): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService( 2394): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService( 2394): 	at libcore.io.IoBridge.open(IoBridge.java:393)
E/DropBoxManagerService( 2394): 	... 5 more
I/SELinux (12037): Function: selinux_android_load_priority [0], There is no sepolicy file.
I/SELinux (12037):  
I/Process (12017): Sending signal. PID: 12017 SIG: 9
I/ActivityManager( 2394): Process com.sec.android.app.shealth (pid 12017) (adj 0) has died.
D/dalvikvm( 1921): GC_EXPLICIT freed 43K, 10% free 9507K/10484K, paused 3ms+4ms, total 38ms
I/SELinux (12037): Function: selinux_android_load_priority , spota verifySig and checkHash pass. priority version is VE=SEPF_SM-G800F_4.4.2_0046
I/SELinux (12037):  
I/SELinux (12037):  
I/SELinux (12037): selinux_android_seapp_context_reload: seapp_contexts file is loaded from /data/security/spota/seapp_contexts
E/SELinux (12037): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
E/dalvikvm(12037): >>>>> Normal User
E/dalvikvm(12037): >>>>> com.samsung.android.sdk.samsunglink [ userId:0 | appId:10043 ]
E/SELinux (12037): [DEBUG] seapp_context_lookup: seinfoCategory = samsung
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10484K, paused 3ms+4ms, total 33ms
D/TimaKeyStoreProvider(12037): in addTimaSignatureService
D/TimaKeyStoreProvider(12037): Cannot add TimaSignature Service, License check Failed
D/ActivityThread(12037): Added TimaKesytore provider
D/dalvikvm( 1921): GC_EXPLICIT freed <1K, 10% free 9507K/10484K, paused 3ms+4ms, total 32ms
D/dalvikvm(12037): GC_CONCURRENT freed 3005K, 30% free 9574K/13508K, paused 2ms+1ms, total 24ms

```
